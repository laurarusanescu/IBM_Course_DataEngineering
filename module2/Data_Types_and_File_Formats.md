# 🧩Types of Data by Structure

## 📌 What is Data?
- **Data** is unorganized information processed to make it meaningful.
- It includes facts, observations, perceptions, numbers, characters, symbols, and images.

---

## 📚 Categories of Data by Structure

### 1. **Structured Data**
- **Definition**: Has a well-defined format; follows a strict schema.
- **Storage**: Relational (SQL) databases; tables with rows and columns.
- **Examples/Sources**:
  - SQL Databases (OLTP systems)
  - Spreadsheets (Excel, Google Sheets)
  - Online forms
  - GPS & RFID sensor data
  - Web server logs
- **Tools**: Easily analyzed with standard data tools (e.g., SQL, Excel)

---

### 2. **Semi-Structured Data**
- **Definition**: Has organizational properties but no rigid schema.
- **Structure**: Uses tags/elements (e.g., XML, JSON) to create a hierarchy.
- **Storage**: Not in rows and columns; stored in hierarchical or tree-based formats.
- **Examples/Sources**:
  - Emails
  - XML, JSON
  - TCP/IP packets
  - Zipped files
  - Binary executables
- **Usage**: Widely used in data exchange and web services.

---

### 3. **Unstructured Data**
- **Definition**: Lacks a predefined structure or format.
- **Characteristics**: Cannot be easily stored in relational databases.
- **Storage**: Files, documents, NoSQL databases (e.g., MongoDB, Cassandra)
- **Examples/Sources**:
  - Social media feeds
  - Web pages
  - Images (JPEG, PNG, GIF)
  - Videos and audio
  - PDF/Word documents
  - Surveys & media logs
  - Presentations
- **Tools**: Analyzed via specialized tools for multimedia, NLP, and big data analytics.

---

## 🧠 Quick Comparison Table

| Feature                | Structured          | Semi-Structured      | Unstructured          |
|------------------------|---------------------|----------------------|------------------------|
| Schema                 | Fixed               | Flexible             | None                  |
| Format                 | Tabular             | Hierarchical (XML/JSON) | Freeform             |
| Example Storage        | SQL Databases       | XML, JSON files      | NoSQL, File Systems   |
| Ease of Analysis       | High                | Moderate             | Complex               |
| Common Sources         | OLTP, Forms, Logs   | Emails, APIs         | Media, Social Feeds   |

---

# 📁 Common Data File Formats for Data Professionals

As a data professional, working with a variety of file formats is inevitable. Understanding the structure, pros, and limitations of these formats will help you choose the best one for your data and performance needs.

---

## 1. **Delimited Text Files (CSV, TSV, etc.)**
- **Structure**: Plain text; values separated by delimiters (comma, tab, colon, etc.).
- **Common Types**:
  - **CSV** (Comma-Separated Values)
  - **TSV** (Tab-Separated Values)
- **Key Features**:
  - Widely supported by data tools and applications.
  - First row often serves as column headers.
  - Each row = one record.
  - Supports various data types (dates, strings, integers).
- **Use Cases**: Data exchange, logs, tabular datasets.
- **Benefits**: Lightweight, simple, human-readable.
- **Limitations**: No support for metadata or complex hierarchies; issues with delimiters inside values.

---

## 2. **Microsoft Excel Open XML Spreadsheet (.XLSX)**
- **Structure**: XML-based format for Excel workbooks.
- **Key Features**:
  - Multiple worksheets per file.
  - Rows and columns form cells to hold data.
  - Supports formulas, formatting, and charts.
  - Cannot embed malicious code (secure).
- **Use Cases**: Business reporting, tabular data with calculations.
- **Benefits**: Widely used in enterprise settings; open format.
- **Limitations**: Heavier than plain text files; not ideal for large-scale automated processing.

---

## 3. **Extensible Markup Language (.XML)**
- **Structure**: Markup language using custom tags to encode data hierarchically.
- **Key Features**:
  - Human- and machine-readable.
  - Platform- and language-independent.
  - Self-descriptive data format.
- **Use Cases**: Web data exchange, configuration files, structured documents.
- **Benefits**: Flexible, interoperable, extensible.
- **Limitations**: Verbose; more complex than JSON; slower parsing.

---

## 4. **Portable Document Format (.PDF)**
- **Structure**: Fixed-layout format that preserves document presentation.
- **Key Features**:
  - Consistent viewing across devices.
  - Supports forms, images, text, and hyperlinks.
  - Secure and non-editable (unless form-enabled).
- **Use Cases**: Legal, financial, academic documents; forms.
- **Benefits**: Universal readability; secure.
- **Limitations**: Not designed for structured data extraction or manipulation.

---

## 5. **JavaScript Object Notation (.JSON)**
- **Structure**: Lightweight, text-based format for representing structured data.
- **Key Features**:
  - Easy to read and write.
  - Ideal for key-value pair data and nested structures.
  - Language-independent and widely used in web APIs.
- **Use Cases**: Web services, APIs, configuration files, data exchange.
- **Benefits**: Compact, fast to parse, supports complex and nested data.
- **Limitations**: No support for comments; not ideal for tabular data.

---

## 🧠 Quick Comparison Table

| Format | Structure | Readability | Best Use Case | Common Limitation |
|--------|-----------|-------------|----------------|--------------------|
| CSV/TSV | Tabular | High | Simple data exchange | No nested data |
| XLSX | Tabular w/ features | Medium | Business reports | Slower parsing |
| XML | Hierarchical | Medium | Web & system data exchange | Verbose |
| PDF | Fixed Layout | Low (machine) | Document sharing | Hard to extract data |
| JSON | Hierarchical | High | Web APIs, configs | No schema enforcement |

---
