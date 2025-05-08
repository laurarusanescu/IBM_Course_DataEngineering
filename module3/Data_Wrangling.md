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
