# Data Modeling Interview Questions — Excalidraw Diagrams

This folder contains data modeling interview case studies with diagrams drawn in Excalidraw.

---

## Q1 — Library Management System

**File:** `Q1_library_management_system.excalidraw` | `Q1.svg`

### Problem Statement

Design a data model for a library management system.

The system should support day-to-day library operations such as:

- Managing books and physical book copies
- Managing members
- Borrowing and returning books
- Tracking whether a book copy is currently available
- Identifying overdue books
- Finding popular books
- Supporting member-level borrowing analytics

The design should cover both:

**1. OLTP Requirements**
Operational transactions such as borrowing, returning, checking availability, and preventing double booking.

**2. OLAP Requirements**
Analytical queries such as most borrowed books, active members, overdue trends, borrowing history, and monthly usage patterns.

The system should be scalable enough to handle multiple users borrowing books at the same time.

### Key Entities

| Entity | Purpose |
|---|---|
| `Book` | Master record for a title (ISBN, title, author, genre) |
| `BookCopy` | Physical copy of a book — tracks availability status |
| `Member` | Library member profile |
| `Loan` | Borrow/return transaction linking a member to a copy |
| `Overdue` | Derived view or flag for copies not returned by due date |

### OLTP Design Decisions

- `BookCopy` has a `status` field (`available` / `borrowed` / `lost`) updated atomically on borrow/return
- `Loan` table records `borrowed_at`, `due_date`, `returned_at` — null `returned_at` means still out
- Concurrent borrows prevented by locking the `BookCopy` row on status check + update (optimistic or pessimistic locking)
- One loan per active copy enforced via unique constraint on `(copy_id, returned_at IS NULL)`

### OLAP Design Decisions

- Fact table: `fact_loans` — grain is one row per loan event
- Dimensions: `dim_book`, `dim_member`, `dim_date`
- Metrics derivable: total borrows per book, active members per month, overdue rate, avg loan duration
- Popular books: `COUNT(loan_id) GROUP BY book_id` over a time window
- Overdue trend: `COUNT(*) WHERE returned_at IS NULL AND due_date < CURRENT_DATE GROUP BY due_date`

### Diagram

![Q1 Library Management System](Q1.svg)

---

> More questions coming soon.
