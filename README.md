# Advanced Machine Learning Continuous Delivery

This repository contains a containerized machine learning application developed to demonstrate **Continuous Delivery (CD) practices for ML models**. The project packages a pre-trained ONNX sentiment analysis model into a web service, integrates automated testing, and simulates an edge deployment using Docker.

---

## Project Overview

The application exposes an HTTP API for sentiment analysis. Text inputs are processed and passed to a pre-trained ONNX model, and predictions are returned in JSON format. The project demonstrates best practices in:

- Model packaging
- Containerization
- CI/CD automation
- Robust input handling
- Edge-style deployment

---

##  Technology Stack

- **Python 3.11**
- **FastAPI**
- **ONNX Runtime**
- **Transformers (RoBERTa tokenizer)**
- **Docker**
- **GitHub Actions (CI/CD)**

---

##  Prerequisites

Ensure the following are installed on your system:

- Python 3.10+
- Docker Desktop
- Git
- PowerShell (Windows) or Bash (Linux/macOS)

---


##  Running the Application Locally

### 1️ Clone the repository
```bash
git clone https://github.com/<your-username>/advanced-ml-cd.git
cd advanced-ml-cd
