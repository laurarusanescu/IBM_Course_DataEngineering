# 📥 Data Collection and Importing into Repositories

In this section, we explore **methods and tools** for gathering data from diverse sources and importing it into appropriate data repositories for analysis.

---

## 🔍 Data Gathering Methods

### 📊 1. **SQL for Relational Databases**
- **SQL (Structured Query Language)** is used to:
  - Retrieve, filter, group, and sort structured data.
  - Limit query results and manage transactional records.
  
### 📂 2. **Querying Non-Relational Databases**
- Use **custom query tools** depending on the database type:
  - **CQL** for Cassandra
  - **GraphQL** for Neo4j
  - Some support SQL-like languages

### 🔌 3. **APIs (Application Programming Interfaces)**
- Access structured/unstructured data from:
  - Databases, web services, and data marketplaces
- Also used for **data validation** (e.g., postal codes)

### 🌐 4. **Web Scraping**
- Extract specific data from websites:
  - Text, contact info, images, videos, product listings
- Tools parse HTML pages based on user-defined rules

### 📡 5. **RSS Feeds**
- Continuously fetch updated data from:
  - News sites, forums, and blogs

### 🔄 6. **Data Streams**
- Collect real-time data from:
  - IoT devices, GPS systems, social media, sensors

### 🔁 7. **Data Exchange Platforms**
- Provide secure data trading and collaboration
- Include standards, legal frameworks, and de-identification
- Examples:
  - **AWS Data Exchange**
  - **Crunchbase**
  - **Lotame**
  - **Snowflake**

### 📚 8. **Research & Advisory Firms**
- Provide domain-specific datasets:
  - **Forrester**, **Gartner**, **Business Insider** for market insights
  - Other firms for user behavior, demographic, and ad-spending data

---

## 🗄️ Importing Data into Repositories

### 🔧 Types of Repositories and Data They Support

| Repository Type        | Data Type           | Examples                            |
|------------------------|---------------------|-------------------------------------|
| **Relational DB**      | Structured           | OLTP, spreadsheets, web logs        |
| **NoSQL DB**           | Semi/Unstructured    | JSON, XML, emails, zipped files     |
| **Data Lakes**         | All data types       | Images, social feeds, video, docs   |

> **JSON** is commonly used for **web services**; **XML** for structured communication formats.

---

## ⚙️ Importing Tools & Languages

- **ETL Tools**: Automate Extract → Transform → Load
  - Examples: **Talend**, **Informatica**
- **Languages**: 
  - **Python** and **R** with powerful data libraries
  - Ideal for scripting and custom integrations

---

## ✅ Summary
- Data sources vary widely—from SQL databases to IoT streams.
- Choose your data import method and destination based on:
  - **Data structure** (structured, semi, or unstructured)
  - **Volume and velocity**
  - **End-use** (analytics, real-time processing, storage)
- Use appropriate **tools, formats, and repositories** for efficient data management.
