# 👤 User Data Pipeline with Airflow (Dockerized)

This project is a simple ETL pipeline using **Apache Airflow**.
It fetches random user data from an external API, processes the data, and stores it in a **PostgreSQL** database. 
Everything runs inside Docker containers for easy setup.

---

## 🚀 What This Project Does

1. **Checks** if an external API is available  
2. **Fetches** random user data from the API  
3. **Processes** and cleans the data (using pandas)  
4. **Saves** the data into a PostgreSQL database  

---

## 🛠️ Tech Stack

- **Apache Airflow**
- **PostgreSQL**
- **Python**
- **pandas**
- **Docker + Docker Compose**

---

## 📂 Project Files
├── dags/ 
│ └── user_processing_dag.py
├── logs/ # Airflow logs
├── .env 
├── docker-compose.yaml # Docker setup
├── requirements.txt # Python dependencies
└── README.md 
