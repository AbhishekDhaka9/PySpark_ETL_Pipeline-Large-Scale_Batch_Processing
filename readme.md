# ⚡ PySpark ETL Pipeline — Large-Scale Batch Processing
---

## 📌 Overview
Designed and built a **PySpark ETL pipeline** for large-scale structured datasets (simulating Amazon-scale order/transaction logs).  
The pipeline ingests raw **CSV/JSON**, applies transformations, and loads data into a **partitioned Parquet data warehouse** optimized for analytical queries.

---

## 🛠️ Tech Stack
- **Python**
- **PySpark / Apache Spark**
- **Parquet**
- **Docker**
- **GitHub Actions (CI/CD)**
- **Pandas**

---

## 🚀 Features
- **Schema Enforcement**: Ensures consistent data structure.  
- **Data Quality Checks**: Null handling, deduplication, type validation.  
- **Partitioned Writes**: Optimized for downstream queries.  
- **Performance Benchmarking**:
  - Measured partition count impact on shuffle time.
  - Applied broadcast joins for dimension tables.
  - Documented execution plan analysis via Spark UI.  
- **Containerization**: Packaged in Docker with configurable parameters.  
- **CI/CD**: Automated testing on every commit via GitHub Actions.  

---

## 📈 Outcomes (to be updated)
- ETL design demonstration.  
- Distributed batch processing at scale.  
- Data quality & schema design validation.  
- Spark performance tuning insights.  
- Core **Amazon DE competencies** showcased.  

---

## 📂 Project Structure
```bash
├── data/                # Raw CSV/JSON datasets
├── etl/                 # PySpark ETL scripts
├── warehouse/           # Partitioned Parquet outputs
├── docker/              # Docker setup files
├── tests/               # Unit & integration tests
├── .github/workflows/   # CI/CD pipeline configs
└── README.md            # Project documentation
