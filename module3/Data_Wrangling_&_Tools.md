# 🧹 Data Wrangling & Cleansing: Making Data Analytics-Ready

Raw data is rarely usable as-is. **Data wrangling** (also called data munging) involves **transforming, validating, and cleaning** data to make it suitable for analytics.

---

## 🔄 Key Data Transformations

### 1. 🧱 **Structuring**
- Adjusts schema and format for consistency.
- Required when merging data from sources like:
  - Relational databases
  - Web APIs

#### 🔗 Common Structural Techniques:
- **Joins**: Combine columns from two tables (same row).
- **Unions**: Stack rows from two tables (same columns).
- **Normalization**: 
  - Reduces redundancy and inconsistency.
  - Typical in transactional systems (OLTP).
- **Denormalization**:
  - Combines data from multiple tables for faster queries.

---

## 🧽 Data Cleaning Tasks

### 2. 🔎 **Detection**
Use tools for **data profiling** and **visualization** to:
- Identify nulls, blanks, duplicates
- Spot outliers and anomalies
- Understand data structure and interrelationships

### 3. 🛠️ **Cleaning Techniques**
| Issue Type        | Description / Fix                                |
|-------------------|--------------------------------------------------|
| **Missing Values** | - Drop rows<br>- Source missing info<br>- Imputation (mean, median, etc.) |
| **Duplicates**     | Remove repeated entries                         |
| **Irrelevant Data**| Discard fields not useful for your analysis     |
| **Data Type Mismatch** | Convert to correct types (e.g., string → date) |
| **Standardization**| e.g., lowercase strings, consistent date formats |
| **Syntax Errors**  | Fix typos, trim whitespace, format consistency   |
| **Outliers**       | Identify and assess if valid or erroneous       |

#### 🧠 Example Scenarios:
- A **5-year-old voter** in a voting dataset → invalid outlier.
- A **$1M income** in a $100K-$200K range → valid but needs context review.

---

## 📊 Tools for Detection & Cleaning
- **Scripts** (e.g., Python, R)
- **Data Profiling Tools**: Explore structure and completeness.
- **Data Visualization**: Spot statistical anomalies using graphs.

---

## ✅ Summary
- Data wrangling is **iterative and contextual**.
- Cleaning improves **accuracy**, **reliability**, and **analytical value**.
- Techniques vary depending on the **data quality issues** and the **analytics use case**.

  # 🛠️ Popular Tools for Data Wrangling

Data wrangling tools help transform raw data into clean, usable formats for analysis. Tools vary in complexity, automation, and technical depth. Here's a breakdown:

---

## 🧾 Spreadsheet Tools

### **Excel / Google Sheets**
- Manual wrangling with formulas, filters, and formatting.
- **Add-ins**:
  - **Microsoft Power Query** (Excel)
  - **Google Sheets Query function**
- Suitable for small datasets and beginner users.

---

## 🔧 Menu-Based GUI Tools

### **OpenRefine**
- Open-source desktop tool.
- Handles formats: CSV, TSV, JSON, XML, Excel.
- Menu-driven (no coding required).
- Allows transformation, cleaning, and extending data via web services.

### **Google DataPrep**
- Cloud-based visual wrangling.
- Automatically detects schema, types, and anomalies.
- Suggests next steps interactively.
- Fully managed—no setup or infrastructure required.

### **IBM Watson Studio – Data Refinery**
- Enterprise-grade data wrangling platform.
- Supports large-scale cleansing, transformation, and governance.
- Auto detects classifications and applies governance policies.
- Available via Watson Studio and Cloud Pak for Data.

### **Trifacta Wrangler**
- Cloud-based and interactive.
- Real-time collaboration features.
- Cleans and reshapes data for export to Excel, Tableau, R.
- Suitable for team environments and fast iterations.

---

## 🐍 Python Ecosystem

Python offers a powerful, code-driven approach to wrangling.

### Key Libraries:
- **Jupyter Notebook**: Interactive coding and visualization.
- **NumPy**: Core package for numerical operations and arrays.
- **Pandas**: High-level data manipulation with commands for:
  - Merging
  - Joining
  - Filtering
  - Transforming
  - Handling misaligned data

---

## 📊 R Ecosystem

R is widely used in statistics and analytics.

### Key Packages:
- **Dplyr**: Elegant, chainable syntax for transforming data.
- **Data.table**: Fast aggregation and transformation of large datasets.
- **Jsonlite**: Simplified JSON parsing, especially useful for web API data.

---

## ✅ Choosing the Right Tool

Select based on your:
| Factor                        | Considerations                                      |
|------------------------------|-----------------------------------------------------|
| **Data Size**                | Excel for small, Python/R for large datasets        |
| **Data Type**                | Structured (Excel, Pandas), Semi/Unstructured (OpenRefine, JSON tools) |
| **Automation**              | Python, R, DataPrep, Trifacta for pipelines         |
| **Team Collaboration**       | Trifacta, Google Sheets, Watson Studio              |
| **Infrastructure**           | Cloud vs On-premise options                         |
| **Ease of Use & Learning**   | GUI tools (OpenRefine, DataPrep) are beginner-friendly |

