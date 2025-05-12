# 737-2025-t1-prac7p

## Overview
This project demonstrates the integration of MongoDB into a containerized Node.js calculator microservice deployed on Kubernetes. The application performs backend calculations and stores results in MongoDB for persistence.

---

## 🛠 Tech Stack
- Node.js (Express)
- MongoDB
- Docker
- Kubernetes (via Docker Desktop)
- kubectl CLI
- GitHub

---

## 🧩 Features Implemented
- MongoDB running in Kubernetes with Persistent Volume
- Secrets for secure database credentials
- Node.js microservice reads credentials via env vars
- Logs each calculation result in `calculator.logs` collection
- API endpoint: `POST /api/calculate`

---

## 📂 Project Structure
├── Dockerfile
├── server.js
├── deployment.yaml
├── mongo-deployment.yaml
├── service.yaml
├── package.json
├── README.md
