# Simple Java Docker Practice Project

This repository is part of my **Docker learning journey**.
In this project, I practiced **containerizing a simple Java application using Docker**.

The goal of this project was to understand:

* How Docker works with Java applications
* How to write a Dockerfile
* How to build and run Docker images and containers

---

## Project Objective

* Clone an existing Java application repository
* Write a Dockerfile for the Java application
* Build a Docker image
* Run the application inside a Docker container
* Understand the complete Docker workflow as a beginner

---

## Tech Stack Used

* **Java**
* **Docker**
* **Git**
* **Linux (Ubuntu)**

---

## Dockerfile Explanation

The Dockerfile is used to containerize the Java application.

### Key steps performed:

1. Use a Java-based image
2. Copy application files into the container
3. Compile the Java program
4. Run the Java application inside the container

This helped me understand how Java applications run inside Docker containers.

---

## Steps I Performed

### 1️⃣ Clone the Repository

```bash
git clone < repo-URL >
cd <project>
```

---

### 2️⃣ Build Docker Image

```bash
docker build -t simple-java-app .
```

---

### 3️⃣ Run Docker Container

```bash
docker run simple-java-app
```

---

## Output

After running the container, the Java application executes successfully inside Docker, confirming that the containerization was done correctly.

---

## Learning Outcomes

Through this project, I learned:

* How to write a basic Dockerfile
* How Docker images and containers work
* How to containerize a Java application
* Docker commands like `build`, `run`, and `ps`
* Practical hands-on experience with Docker

---

## Why This Project?

As a **DevOps learner**, this project helped me build strong fundamentals of Docker before moving to advanced topics like:

* Docker Compose
* Kubernetes
* CI/CD Pipelines
* Cloud Deployments (AWS / EKS)

---

## 👩‍💻 Author

**Shipra**
DevOps & Cloud Enthusiast 🌱
Learning Docker | Kubernetes | AWS
