# 🔄 Understanding Data Movement: ETL, ELT, and Data Pipelines

---

## 🚚 Introduction

In this video, we explore tools and processes used to move data from source to destination systems, including:

- **ETL** (Extract, Transform, Load)
- **ELT** (Extract, Load, Transform)
- **Data Pipelines**

---

## ⚙️ ETL: Extract, Transform, Load

ETL is the core process for converting raw data into analysis-ready data through an automated workflow.

### 1. **Extract**
- **Purpose**: Gather data from various source systems.
- **Methods**:
  - **Batch Processing**: Large chunks of data are moved at scheduled intervals.
    - Tools: *Stitch*, *Blendo*
  - **Stream Processing**: Real-time data transfer and transformation in transit.
    - Tools: *Apache Samza*, *Apache Storm*, *Apache Kafka*

### 2. **Transform**
- Apply rules/functions to convert raw data into a usable format:
  - Standardize date formats and units
  - Remove duplicates
  - Filter unnecessary data
  - Enrich data (e.g., splitting full names)
  - Establish key relationships across tables
  - Apply business rules and validations

### 3. **Load**
- Move processed data into a data repository.
- **Types**:
  - **Initial Loading**: Load all data for the first time
  - **Incremental Loading**: Periodic updates/modifications
  - **Full Refresh**: Delete existing data and reload from scratch
- **Load Verification**: Checks for:
  - Missing/null values
  - Server performance
  - Load failures and recovery

> ✅ **Popular ETL Tools**: IBM Infosphere, AWS Glue, Improvado, Skyvia, HEVO, Informatica PowerCenter

---

## 🔁 ELT: Extract, Load, Transform

In ELT, data is loaded into the destination system first, and then transformations are applied **within** the target environment.

### 🔍 Why Use ELT?
- Suited for large, **unstructured or non-relational data**
- Ideal for **data lakes**
- Offers **greater flexibility** for analysts and data scientists
- Supports **exploratory analytics** and multiple use cases

### 🆚 ETL vs ELT
| Feature | ETL | ELT |
|--------|-----|-----|
| Transformation Location | Before loading | After loading |
| Best For | Structured data | Big data, unstructured |
| Flexibility | Less | More |
| Speed | Longer cycle | Shorter cycle |
| Example Target | Data warehouse | Data lake |

---

## 🌐 Data Pipelines

**Data pipelines** are a broader concept that includes ETL/ELT as subsets. They handle the **entire data journey** from source to destination.

### Features
- Can be:
  - **Batch-oriented**
  - **Stream-oriented**
  - **Hybrid** (batch + streaming)
- Enables:
  - Long-running batch queries
  - Smaller, real-time interactive queries

### Typical Destinations:
- Data Lakes
- Other applications
- Visualization tools

> 🔧 **Popular Data Pipeline Tools**: Apache Beam, Apache Airflow, Google Dataflow

---

## 📌 Summary

- **ETL**: Extract → Transform → Load
- **ELT**: Extract → Load → Transform
- **Data Pipelines**: Encompass both ETL/ELT and more; define the full movement and transformation of data across systems.

