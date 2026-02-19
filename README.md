# ☁️ Cloud-Native Monitoring Dashboard (Dockerized)

## 📌 Overview

This project is a two-tier cloud-native web application built using Flask and MySQL, containerized using Docker and managed with Docker Compose.

It simulates a simple infrastructure monitoring dashboard that displays:

* Cloud Environment Status
* Container Service Status
* Database Health
* Deployment Pipeline Initialization

---

## 🛠️ Tech Stack

* Python
* Flask
* MySQL
* Docker
* Docker Compose

---

## 📂 Project Structure

```
two-tier-docker-app/
│── app.py
│── requirements.txt
│── Dockerfile
│── docker-compose.yml
│── templates/index.html
│── static/style.css
│── static/cloud.jpg
```

---

## ⚙️ Run Application

```
docker-compose up --build
```

Open:

```
http://localhost:5000
```

---

## 🎯 Key Concepts

* Containerization using Docker
* Multi-container setup
* Two-tier architecture
* Internal container networking


