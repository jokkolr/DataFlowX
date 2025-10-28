# 🚀 DataFlowX

**DataFlowX** is a cloud-ready **data ingestion and validation API** built with **FastAPI**, **Pandas**, and **MongoDB**.  
It allows users to upload raw datasets (CSV, Excel), automatically validate and clean them, then store the structured data in MongoDB or blob storage.  

Designed for scalability, DataFlowX is ideal for teams that need reliable and automated data pipelines for analytics, dashboards, or machine learning.

---

## 🌟 Features

- 📤 Upload CSV files via REST API
- 🧠 Automatic schema validation using **Pandas** & **Pydantic**
- 🧹 Data cleaning utilities for missing or invalid entries
- 💾 MongoDB integration for structured data storage
- ☁️ Cloud-ready (deployable to Render, Railway, or Azure)
- 🧩 Modular codebase for easy extension
- 🧪 Unit tests using **pytest**

---

## 🧠 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Backend Framework** | FastAPI |
| **Data Processing** | Pandas |
| **Database** | MongoDB (via PyMongo) |
| **Validation** | Pydantic |
| **Testing** | Pytest |
| **Deployment** | Uvicorn / Docker / Azure (optional) |

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/DataFlowX.git
cd DataFlowX
