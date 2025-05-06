# 🧩 Relational Databases (RDBMS) Overview

---

## 📌 What is a Relational Database?

- A **relational database** stores data in **tables** made up of **rows (records)** and **columns (attributes)**.
- Tables can be **linked (related)** by common fields (e.g., `CustomerID`).
- This structure allows:
  - Efficient querying
  - Minimal redundancy
  - Strong data consistency

---

## 🔗 Example of Table Relationship

- **Customer Table**: Stores customer info (ID, Name, Address, Phone)
- **Transaction Table**: Stores transactions (Date, Customer ID, Amount)
- These tables are linked using **Customer ID**.

You can run **SQL queries** to generate reports like customer transaction summaries.

---

## 🧠 Key Concepts

| Concept           | Description                                                  |
|------------------|--------------------------------------------------------------|
| **SQL**          | Structured Query Language for defining, manipulating, and querying data |
| **Schema**       | Predefined structure for data organization                   |
| **ACID Compliance** | Ensures reliable and consistent transactions: Atomicity, Consistency, Isolation, Durability |
| **Normalization**| Minimizes redundancy and improves data integrity             |
| **Security**     | Role-based access and policy enforcement                      |

---

## 🧱 Popular Relational Databases

| Type                | Examples                                                   |
|---------------------|------------------------------------------------------------|
| **Open Source**     | MySQL, PostgreSQL                                          |
| **Commercial**      | Oracle DB, IBM DB2, Microsoft SQL Server                   |
| **Cloud-Based (DBaaS)** | Amazon RDS, Google Cloud SQL, SQL Azure, IBM DB2 on Cloud, Oracle Cloud |

---

## ✅ Advantages of RDBMS

- **Data Consistency & Integrity** (ACID-compliant)
- **Optimized for Structured Data**
- **Easy Backups & Disaster Recovery**
- **Flexibility** (schema changes on-the-fly)
- **Mature & Well-Supported** (broad community and talent pool)
- **Ideal for OLTP & OLAP**

---

## 🔄 Common Use Cases

| Use Case             | Description                                                                       |
|----------------------|-----------------------------------------------------------------------------------|
| **OLTP**             | Online Transaction Processing: frequent, high-volume transactions (e.g., banking, eCommerce) |
| **Data Warehousing (OLAP)** | Analytical processing of historical data                                  |
| **IoT**              | Lightweight relational databases for edge data ingestion and processing          |

---

## ⚠️ Limitations of RDBMS

- Poor handling of **semi-structured** or **unstructured** data
- **Migration** challenges between systems due to schema rigidity
- **Field length limitations**
- **Scalability** is usually **vertical**, which can be costly
- Less suited for **big data** analytics and modern distributed workloads

---


# 🧩 NoSQL Databases Overview

---

## 📌 What is NoSQL?

- **NoSQL** stands for **"Not Only SQL"** (not "No SQL").
- It refers to **non-relational databases** with **flexible schemas**, designed to store and retrieve:
  - **Structured**
  - **Semi-structured**
  - **Unstructured** data
- Ideal for **cloud-based**, **big data**, and **high-velocity applications**.

NoSQL databases do **not** follow traditional row/column tables and often do **not use SQL**, though some support SQL-like querying.

---

## 🔄 Why NoSQL?

- Gained popularity due to needs in **scalability**, **performance**, and **agility**.
- Excellent fit for **modern applications**:
  - Social media
  - IoT
  - Real-time analytics
  - Mobile/web apps

---

## 🔢 Common Types of NoSQL Databases

| Type           | Description | Use Cases | Examples |
|----------------|-------------|-----------|----------|
| **Key-Value Store** | Stores data as key-value pairs. Simple and fast. | Session data, caching, real-time personalization | Redis, Memcached, DynamoDB |
| **Document-Based** | Stores data in documents (e.g., JSON). Allows flexible queries and indexing. | eCommerce, CRM, analytics platforms | MongoDB, CouchDB, DocumentDB, Cloudant |
| **Column-Based** | Stores data by columns (column families) rather than rows. Efficient for large write-heavy workloads. | Time-series, sensor data, heavy write systems | Cassandra, HBase |
| **Graph-Based** | Data is stored in nodes and edges (relationships). Optimized for connections and relationships. | Social networks, fraud detection, recommendation engines | Neo4j, CosmosDB |

---

## ✅ Advantages of NoSQL

- Handles **large volumes** of all data types (structured, semi-, unstructured)
- Built for **distributed**, **cloud-native** environments
- **Scales horizontally** with **cost-effective hardware**
- **Flexible design** allows rapid iteration and development
- Greater **availability** and **fault tolerance**

---

## 🔁 NoSQL vs. Relational Databases

| Feature | RDBMS (Relational) | NoSQL (Non-relational) |
|--------|--------------------|------------------------|
| **Schema** | Rigid, pre-defined | Flexible or schema-less |
| **Data Format** | Tabular (rows/columns) | Document, key-value, graph, etc. |
| **Query Language** | SQL | Varies (some use SQL-like) |
| **ACID Compliance** | Full ACID compliance | Often eventual consistency |
| **Scalability** | Vertical | Horizontal |
| **Cost** | High (often proprietary) | Lower cost, commodity hardware |
| **Maturity** | Very mature, widely adopted | Newer, rapidly evolving |

---

