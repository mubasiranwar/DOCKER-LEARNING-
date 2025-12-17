# 💻 Laptop Price Predictor

### 📊 Machine Learning Regression Model | 🐳 Dockerized Application

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-Regression-blue" />
  <img src="https://img.shields.io/badge/Python-3.x-yellow" />
  <img src="https://img.shields.io/badge/Docker-Containerized-blue" />
  <img src="https://img.shields.io/badge/Status-Completed-success" />
</p>

---

## 📌 Overview

**Laptop Price Predictor** is an **end-to-end Machine Learning regression project** designed to predict laptop prices based on hardware and specification features.
The project was built as part of my **hands-on Docker learning journey**, focusing on **containerizing ML models for production use**.

This repository demonstrates:

* Practical ML model development
* Clean project structure
* Model serialization
* Docker-based deployment readiness

---

## 🧠 Machine Learning Details

* **Learning Type:** Supervised Learning
* **Task:** Regression
* **Algorithm:** Regression Model (via Scikit-Learn Pipeline)
* **Dataset:** Laptop specifications dataset
* **Output:** Predicted laptop price

📒 Model training and experimentation are fully documented in:

```
laptop-price-predictor.ipynb
```

---

## 🐳 Docker Integration (Core Learning Objective)

This project focuses on **real-world Docker usage for ML projects**, including:

* Writing a production-ready `Dockerfile`
* Dependency management using `requirements.txt`
* Containerized ML inference
* Image publishing to Docker Hub

🔗 **Docker Hub Image:**
👉 [https://hub.docker.com/repository/docker/mubasir123/laptop/general](https://hub.docker.com/repository/docker/mubasir123/laptop/general)

---

## 📂 Project Structure

```
laptop-price-predictor-regression-project/
│
├── app.py                      # Application entry point
├── laptop_data.csv              # Dataset
├── laptop-price-predictor.ipynb # Model training notebook
├── pipe.pkl                     # Trained ML pipeline
├── df.pkl                       # Processed dataframe
├── requirements.txt             # Dependencies
├── Dockerfile                   # Docker configuration
├── Procfile                     # Deployment process file
├── setup.sh                     # Setup script
├── .gitignore                   # Git ignore rules
└── README.md                    # Documentation
```

---

## ⚙️ Run with Docker (Recommended)

### 🔽 Pull the Image

```bash
docker pull mubasir123/laptop
```

### ▶️ Run the Container

```bash
docker run -p 5000:5000 mubasir123/laptop
```

### 🌐 Open in Browser

```
http://localhost:5000
```

---

## 🧪 Run Locally (Without Docker)

```bash
pip install -r requirements.txt
python app.py
```

---

## 🎯 Key Learnings

✔ Regression modeling using Scikit-Learn
✔ Feature preprocessing with pipelines
✔ Model serialization using `.pkl`
✔ Dockerizing ML applications
✔ Understanding ML deployment workflows

---

## 🚀 Future Enhancements

* REST API endpoints for predictions
* Enhanced feature engineering
* CI/CD pipeline integration
* Cloud deployment (Render / AWS / Azure)
* Model monitoring and logging

---

## 👨‍💻 Author

**Mubasir Anwar**
🎓 Machine Learning Enthusiast | System Engineering Student<br>
🔍 Focused on **ML, Docker, and Model Deployment**

---

## ⭐ Support

If you find this project useful:

* ⭐ Star the repository
* 🐳 Pull the Docker image
* 🍴 Fork and experiment

