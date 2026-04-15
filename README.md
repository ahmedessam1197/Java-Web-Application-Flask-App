# Java Web Application with Flask Integration

This project is a Java-based web application integrated with a Python Flask microservice.
It demonstrates how different technologies can work together in a modern distributed system.

The application simulates a real-world architecture where:

A Java backend communicates with
A Python Flask API via REST calls

---

# Architecture

The system consists of:

Java Web Application
Flask Microservice
REST API Communication between services

---

# Tech Stack

#Backend

Java (Spring Boot / Servlet-based)
  Python (Flask)

# DevOps & Tools

* Docker & Docker Compose
* GitHub Actions (CI/CD)
* Maven / Gradle

---

# Features

Integration between Java and Flask services
RESTful API communication
Containerized using Docker
CI/CD pipeline integration
Easy to test and extend

---

# Installation & Setup

## Clone the repository

```bash
git clone https://github.com/ahmedessam1197/Java-Web-Application-Flask-App.git
cd Java-Web-Application-Flask-App
```

# Run Flask App

```bash
cd flask-app
pip install -r requirements.txt
python app.py
```

# Run Java App

```bash
cd java-app
mvn clean install
mvn spring-boot:run
```
---

# CI/CD Pipeline

This project includes a CI/CD pipeline that:
Builds the application
Runs automated tests
Builds Docker images
Deploys services
---

Future Improvements

Add authentication (JWT)
Integrate a database
Add monitoring tools (Prometheus & Grafana)
Improve logging and error handling

---
