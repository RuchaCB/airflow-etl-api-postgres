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

## 📸 Output 
Here are some screenshots showcasing the key outputs and results from running the pipeline.

![Airflow DAG output GRAPH screenshot](https://github.com/user-attachments/assets/e617e327-d9a8-461b-8cd1-8ad8862983c8)

![Airflow DAG output GRID screenshot]](https://github.com/user-attachments/assets/df53841d-7196-4e22-b73a-326958b37341)

![Airflow DAG output GRANTT screenshot](https://github.com/user-attachments/assets/34f80021-033a-49c8-9751-15d7038429a8)


## 📚 Acknowledgment

This project is based on a learning exercise from the Udemy course:  
**[The Complete Hands-On Course to Master Apache Airflow](https://www.udemy.com/course/the-complete-hands-on-course-to-master-apache-airflow/)** by *Marc Lamberti*.

I recreated and extended the project for practice and personal learning. All credits for the original project structure and logic go to the course instructor.

