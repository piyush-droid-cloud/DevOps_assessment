# DevOps Assessment Project

## Overview

This project demonstrates a basic DevOps setup:
- Python Flask web app
- Dockerized container
- GitHub Actions CI/CD pipeline
- Kubernetes deployment configuration

## How to Run Locally
```bash
pip install -r requirements.txt
python app/app.py
```

## Build Docker Image
```bash
docker build -t flask-app .
docker run -p 5000:5000 flask-app
```
