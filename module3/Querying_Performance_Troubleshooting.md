## 🧮 Basic Querying Techniques (SQL)

### 📏 1. Counting and Aggregation

| Function      | Description                         |
|---------------|-------------------------------------|
| `COUNT()`     | Counts rows                         |
| `DISTINCT()`  | Returns unique values               |
| `SUM()`       | Total of numeric column             |
| `AVG()`       | Average of numeric column           |
| `STDDEV()`    | Spread of values (standard deviation) |


# 📊 Data Engineering: Performance Tuning, Monitoring & Troubleshooting

## 🎯 Key Responsibilities of a Data Engineer
- Monitor and optimize systems and data flows
- Ensure performance and availability throughout the data lifecycle

---

## 🚀 Data Pipelines: Performance Considerations

### ⚠️ Performance Threats
- **Scalability** challenges with growing datasets and workloads
- **Application failures**
- **Scheduling issues** (e.g., job dependencies, missed tasks)
- **Tool incompatibilities** across the pipeline stack

### 📏 Performance Metrics
| Metric          | Description                                       |
|-----------------|---------------------------------------------------|
| **Latency**     | Time taken to fulfill a request                   |
| **Failures**    | Rate of service or process failures               |
| **Utilization** | CPU, memory, and resource usage patterns          |
| **Traffic**     | Volume of user or system requests per time unit   |

---

## 🛠️ Troubleshooting Pipeline Issues

### 🧭 General Troubleshooting Steps
1. **Collect incident details** (alerts, reports, logs)
2. **Verify versions** (software, source code, recent deployments)
3. **Analyze logs and metrics** (errors, CPU, memory, traffic)
4. **Reproduce in test environment** if needed
5. **Validate root cause hypothesis**
6. **Deploy fix** as per team protocol

---

## 🗄️ Database Performance Optimization

### 🎯 Metrics to Monitor
- System **outages**
- **Capacity** utilization
- **Slowdowns** in application performance
- **Query performance**
- **Conflicting** operations (e.g., user vs. batch jobs)

### 📌 Best Practices

#### 📏 Capacity Planning
- Forecast current and future system loads
- Allocate optimal hardware/software resources

#### 🔍 Indexing
- Speeds up data lookups
- Reduces disk I/O during queries

#### 🧩 Partitioning
- Splits large tables for faster querying
- Enhances data management

#### 🧬 Normalization
- Eliminates redundancy and anomalies
- Improves efficiency in querying and analytics

---

## 📡 Monitoring & Alerting Systems

| Tool Type                | Functionality                                                                 |
|--------------------------|-------------------------------------------------------------------------------|
| **Database Monitoring**  | Tracks performance over time; aids root cause analysis                        |
| **App Monitoring**       | Monitors response time, errors, and resource usage                            |
| **Query Monitoring**     | Tracks execution stats and resource use                                       |
| **Job Monitoring**       | Observes task-level performance and completion time                           |
| **Volume Monitoring**    | Monitors data workload sizes to evaluate performance impact                   |

---

## 🧹 Maintenance Routines

### 🔁 Types of Maintenance
- **Time-Based**: Scheduled at regular intervals
- **Condition-Based**: Triggered by detected performance drop or system issue

### 🧰 Purpose
- Prevent faults and outages
- Improve system reliability and uptime
- Collect data for system diagnostics and tuning

---

## 📘 Conclusion

- Performance applies to all stages of the data lifecycle: pipelines, databases, applications, and scheduled jobs.
- Use metrics like latency, failure rates, resource use, and traffic for evaluation.
- Troubleshooting and optimization involve systematic diagnosis, validation, and deployment.
- Monitoring tools and preventive maintenance are essential for proactive performance management.

---
