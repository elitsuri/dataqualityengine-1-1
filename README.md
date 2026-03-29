# DataQualityEngine 1

> Data quality validation engine with rules, scoring, and anomaly detection

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
Python, Airflow, PostgreSQL, Redis

## 🏗️ Architecture
Backend service with Python, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/dataqualityengine-1
cd dataqualityengine-1

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
