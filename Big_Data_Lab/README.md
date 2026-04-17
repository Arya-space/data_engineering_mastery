# Big Data – All Labs (NYU BD1004)

![Big Data](https://img.shields.io/badge/Big%20Data-Apache%20Spark-blue)
![Course](https://img.shields.io/badge/Course-NYU%20BD1004-orange)
![Status](https://img.shields.io/badge/Status-Complete-green)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)

Comprehensive Big Data course from **NYU (BD1004)** covering Apache Spark, distributed computing, 
real-world data processing challenges, and scalable system design using NYU Data Processing infrastructure.

---

## 📖 Table of Contents

- [Course Overview](#-course-overview)
- [What's Covered](#-whats-covered)
- [Lab Structure](#-lab-structure)
- [Technologies & Tools](#-technologies--tools)
- [How to Use This Repo](#-how-to-use-this-repo)
- [Quick Start](#-quick-start)
- [Lab Details](#-lab-details)
- [Key Learnings](#-key-learnings)
- [Prerequisites](#-prerequisites)
- [Real-World Applications](#-real-world-applications)
- [Getting Help](#-getting-help)
- [Resources](#-resources)
- [Attribution](#-attribution)

---

## 🎯 Course Overview

### What is BD1004?

**BD1004** is a comprehensive Big Data course offered at **New York University** that teaches modern data engineering 
and distributed computing principles. This course equips students with the skills to:

- Build and optimize distributed data processing systems
- Master Apache Spark ecosystem
- Design scalable data pipelines
- Work with real-world big data challenges
- Implement production-grade data solutions

### Course Information

| Attribute | Details |
|-----------|---------|
| **Institution** | New York University (NYU) |
| **Course Code** | BD1004 |
| **Course Name** | Big Data Processing & Systems |
| **Focus Area** | Data Engineering & Distributed Computing |
| **Labs Included** | Lab 4, Lab 5, Lab 6, Lab 7, Lab 8, Lab 9 |
| **Skill Level** | Beginner → Advanced |
| **Tech Stack** | Apache Spark, PySpark, Hadoop, SQL, Python |

### NYU Data Processing Infrastructure

These labs leverage **NYU's data processing infrastructure**, which provides:
- Access to Spark clusters
- Pre-configured Hadoop environments
- Real-world datasets for experimentation
- Enterprise-grade tools and frameworks

**Note**: While these labs are built on NYU infrastructure, the concepts and code are transferable 
to other platforms including cloud providers (AWS, GCP, Azure) and open-source Spark deployments.

---

## 📚 What's Covered

### Lab 4: Hadoop & MapReduce Basics
**Focus**: Foundational distributed computing concepts

**Topics Covered**:
- Hadoop ecosystem overview
- HDFS (Hadoop Distributed File System) architecture
- MapReduce programming model
- Job submission and monitoring
- Distributed data locality

**Key Skills Gained**:
- ✅ Understanding distributed file systems
- ✅ Writing MapReduce jobs
- ✅ Debugging distributed applications
- ✅ Performance monitoring

**Technologies**:
- Hadoop
- Java/Python MapReduce
- HDFS


---

### Lab 5: Apache Spark Fundamentals ⭐
**Focus**: Core Spark concepts and RDD programming

**Topics Covered**:
- Spark architecture and components
- RDD (Resilient Distributed Dataset) basics
- RDD transformations (map, filter, flatMap, reduceByKey, etc.)
- RDD actions (collect, count, take, saveAsTextFile, etc.)
- Lazy evaluation and Spark's execution model
- Introduction to DataFrames
- Basic Spark SQL

**Key Skills Gained**:
- ✅ Creating and manipulating RDDs
- ✅ Understanding Spark's lazy evaluation
- ✅ Writing efficient Spark transformations
- ✅ Working with structured data using DataFrames
- ✅ Basic SQL queries on Spark data

**Technologies**:
- Apache Spark
- PySpark
- Python 3.8+
- Jupyter Notebooks


### Lab 6: Advanced PySpark Operations
**Focus**: Complex transformations and performance optimization

**Topics Covered**:
- Advanced DataFrame operations
- Window functions and partitioning
- Complex joins (inner, outer, cross)
- Aggregations and groupBy operations
- User-defined functions (UDFs)
- Performance tuning and optimization
- Caching and persistence strategies
- Broadcast variables and accumulators

**Key Skills Gained**:
- ✅ Writing complex data transformations
- ✅ Optimizing join operations
- ✅ Using window functions for analytics
- ✅ Creating reusable UDFs
- ✅ Performance profiling and tuning
- ✅ Understanding Spark's query optimizer

**Technologies**:
- PySpark
- Pandas integration
- SQL
- Python


---

### Lab 8: Data Storage & Formats Optimization
**Focus**: Storage formats, compression, and data management

**Topics Covered**:
- Parquet file format and optimization
- ORC (Optimized Row Columnar) format
- CSV vs columnar formats comparison
- Compression techniques (snappy, gzip, lz4)
- Partitioning strategies
- Bucketing for performance
- Delta Lake and ACID transactions
- Data lake architecture
- Storage optimization best practices

**Key Skills Gained**:
- ✅ Choosing appropriate storage formats
- ✅ Optimizing file sizes and compression
- ✅ Designing partition strategies
- ✅ Understanding columnar vs row-based storage
- ✅ Implementing data lake architecture
- ✅ ACID compliance in big data systems

**Technologies**:
- Apache Spark
- Parquet
- Delta Lake
- Python
- SQL



---

### Lab 9: GPU Computing & Advanced Optimization
**Focus**: Advanced computing techniques and performance optimization

**Topics Covered**:
- GPU acceleration with Spark
- RAPIDS GPU acceleration
- Distributed machine learning on Spark
- Advanced performance tuning
- Memory management in Spark
- Shuffle optimization
- Cluster configuration tuning
- Monitoring and profiling tools
- Cost optimization strategies

**Key Skills Gained**:
- ✅ Leveraging GPU acceleration
- ✅ Advanced performance profiling
- ✅ Optimizing memory usage
- ✅ Tuning cluster parameters
- ✅ Cost optimization in cloud
- ✅ Scaling to massive datasets

**Technologies**:
- Apache Spark
- RAPIDS
- PySpark ML
- GPU computing frameworks
- Profiling tools


---

## 🛠️ Technologies & Tools

### Core Technologies

| Technology | Version | Purpose | Labs |
|-----------|---------|---------|------|
| **Apache Spark** | 2.4+ | Distributed data processing | All |
| **PySpark** | 2.4+ | Python API for Spark | 5-9 |
| **Hadoop** | 2.7+ | Distributed file system | 4, 7-8 |
| **Python** | 3.8+ | Programming language | All |
| **SQL** | Standard | Data querying | 5-6, 8 |
| **Jupyter** | Latest | Notebook environment | All |
| **Delta Lake** | Latest | ACID transactions | 8 |
| **RAPIDS** | Latest | GPU acceleration | 9 |

### Supporting Tools

- **pandas**: Data manipulation in Python
- **numpy**: Numerical computing
- **matplotlib/seaborn**: Data visualization
- **pytest**: Unit testing
- **git**: Version control
- **Docker**: Containerization (optional)

### NYU Data Processing Platform

- Access to Spark clusters
- Pre-configured Hadoop environments
- Real-world datasets
- Enterprise monitoring tools
- Notebook servers

---



## 🚀 Quick Start

### Prerequisites

Before starting, ensure you have:
- Python 3.8 or higher installed
- Spark 2.4+ installed and configured
- Java 8 or 11 (required for Spark)
- Jupyter Notebook
- Basic understanding of SQL and Python

---
## 📋 Prerequisites

### Before Starting These Labs

You should be comfortable with:

**Programming**:
- ✅ Python fundamentals (loops, functions, classes)
- ✅ Command line / terminal basics
- ✅ Version control with git
- ✅ IDE or code editor usage

**Data & Databases**:
- ✅ SQL basics (SELECT, WHERE, JOIN)
- ✅ Database concepts (tables, schemas, keys)
- ✅ Data types and structures
- ✅ CSV and JSON formats

**Systems**:
- ✅ Linux/Unix command line
- ✅ File systems and directories
- ✅ Environment variables
- ✅ Basic networking concepts

**Math/Statistics**:
- ✅ Basic statistics (mean, median, distribution)
- ✅ Probability fundamentals
- ✅ Basic algebra

### Optional (Helpful But Not Required)

- Java programming experience
- Hadoop or MapReduce knowledge
- Machine learning basics
- Cloud platform experience (AWS, GCP)

### Verification

Test your readiness:
```bash
# Check Python version (should be 3.8+)
python --version

# Check pip is installed
pip --version

# Verify git is installed
git --version

# Test basic Python
python -c "print('Python works!')"
```

---

## 🌍 Real-World Applications

### Why These Skills Matter

The skills taught in BD1004 are used across industries:

**Finance**:
- Stock market data analysis (billions of records)
- Risk modeling and forecasting
- Fraud detection systems
- Trading infrastructure

**E-commerce**:
- Recommendation systems (Netflix, Amazon)
- Customer behavior analysis
- Inventory optimization
- Supply chain analytics

**Healthcare**:
- Patient data analysis
- Drug discovery pipelines
- Medical imaging processing
- Epidemiological modeling

**Social Media**:
- Real-time feed processing
- User analytics and insights
- Content recommendation
- Trend detection

**IoT & Sensors**:
- Sensor data ingestion
- Real-time anomaly detection
- Predictive maintenance
- Time-series analysis

### Real-World Project Examples

**Example 1: E-commerce Analytics**
```
Raw Data (Billions of events)
    ↓ (Lab 4-5)
Hadoop Storage
    ↓ (Lab 5-6)
Spark Processing
    ↓ (Lab 7)
ETL Pipeline
    ↓ (Lab 8)
Data Warehouse
    ↓ (Lab 9)
Real-time Recommendations
```

**Example 2: IoT Data Processing**
```
IoT Sensors (Millions of devices)
    ↓ (Lab 5)
Stream Processing
    ↓ (Lab 6)
Real-time Analytics
    ↓ (Lab 7)
Anomaly Detection
    ↓ (Lab 8-9)
Optimized Storage & GPU ML
```

---



### Interview Preparation

Use these labs for interview prep:
- Practice coding in Spark
- Explain architectural decisions
- Discuss performance optimization
- Demo projects from these labs

---



*Big Data – All Labs | NYU BD1004 | Apache Spark | Data Engineering*