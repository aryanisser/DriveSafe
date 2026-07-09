# 🛣️ DriveSafe – AI Road Crack Detection & Severity Analysis System

<p align="center">

<img src="https://img.shields.io/badge/Python-3.11+-blue?logo=python"/>
<img src="https://img.shields.io/badge/FastAPI-Backend-green?logo=fastapi"/>
<img src="https://img.shields.io/badge/YOLOv8-Computer%20Vision-red"/>
<img src="https://img.shields.io/badge/OpenCV-Image%20Processing-blue?logo=opencv"/>
<img src="https://img.shields.io/badge/React-Frontend-61DAFB?logo=react"/>
<img src="https://img.shields.io/badge/Docker-Containerized-2496ED?logo=docker"/>
<img src="https://img.shields.io/badge/License-MIT-success"/>

</p>

---

# 🚀 Overview

DriveSafe is an AI-powered Road Crack Detection System designed to automate pavement inspection using Computer Vision and Deep Learning.

The platform analyzes uploaded road images, detects pavement cracks using a YOLOv8 segmentation model, estimates crack severity, generates actionable maintenance recommendations, and provides a modern web dashboard for visualization.

The objective is to assist municipalities, highway authorities, and infrastructure companies in performing faster, more accurate, and cost-effective road inspections.

---

# 🌐 Live Demo

**Frontend**

🔗https://drivesafe-qu0p.onrender.com/frontend/
---

# 📸 Screenshots

Create an **assets/** folder.

```
assets/
│
├── dashboard.png
├── upload.png
├── detection.png
├── severity.png
├── recommendation.png
```

Then use

```md
## Dashboard

![Dashboard](assets/dashboard.png)

## Detection

![Detection](assets/detection.png)

## Severity Analysis

![Severity](assets/severity.png)
```

---

# ✨ Features

- 🛣️ AI Road Crack Detection
- 🎯 YOLOv8 Segmentation Model
- 📷 Image Upload
- ⚡ Real-Time Prediction
- 📊 Crack Severity Analysis
- 🧠 Intelligent Maintenance Recommendation
- 📈 Detection Statistics
- 📂 Image Storage
- 💾 SQLite Database
- 🌐 REST API using FastAPI
- 🎨 Modern React Dashboard
- 🐳 Docker Support
- 📱 Responsive Interface

---

# 🧠 AI Pipeline

```
Road Image
      │
      ▼
YOLOv8 Segmentation
      │
      ▼
Crack Detection
      │
      ▼
Area & Length Measurement
      │
      ▼
Severity Classification
      │
      ▼
Maintenance Recommendation
      │
      ▼
Dashboard Visualization
```

---

# 🏗️ System Architecture

```
Frontend (React)

        │

        ▼

FastAPI Backend

        │

        ▼

YOLOv8 Segmentation Model

        │

        ▼

Severity Analysis Engine

        │

        ▼

SQLite Database
```

---

# 🛠 Tech Stack

## Frontend

- React.js
- Vite
- Axios
- CSS

---

## Backend

- Python
- FastAPI
- OpenCV
- NumPy
- SQLite

---

## AI & Deep Learning

- YOLOv8
- Ultralytics
- Computer Vision
- Image Segmentation

---

## Deployment

- Docker
- GitHub
- Vercel (Frontend)

---

# 📂 Project Structure

```
DriveSafe
│
├── frontend
│
├── backend
│
│── api
│── services
│── storage
│── db
│── weights
│
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
└── README.md
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/aryanisser/DriveSafe.git
```

```
cd DriveSafe
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Backend

```bash
uvicorn backend.main:app --reload
```

---

## Run Frontend

```bash
cd frontend

npm install

npm run dev
```

---

# 🐳 Docker

Build

```bash
docker build -t drivesafe .
```

Run

```bash
docker run -p 8000:8000 drivesafe
```

---

# 📊 API Endpoints

| Method | Endpoint | Description |
|----------|----------------|------------------------|
| POST | /process | Detect Road Crack |
| GET | /health | Health Check |

---

# 🎯 Output

The application provides

✅ Original Image

✅ Segmentation Mask

✅ Crack Detection Overlay

✅ Severity Level

- Low
- Medium
- High

✅ AI Maintenance Recommendation

---

# 📈 Future Improvements

- Live Camera Detection
- Drone Inspection Support
- Video Processing
- Multi-Crack Classification
- GPS Integration
- PDF Report Generation
- Cloud Deployment
- Mobile Application
- Historical Inspection Records

---

# 👨‍💻 Developed By

# Aryan Isser

**B.Tech Computer Science Engineering**

### Connect with Me

📧 Email

aryanisser@gmail.com

💻 GitHub

https://github.com/aryanisser

💼 LinkedIn

https://linkedin.com/in/aryanisser

---

# ⭐ Support

If you found this project helpful, please consider giving it a **Star ⭐** on GitHub.

---

# 📄 License

Licensed under the **MIT License**.
