# 🚀 Visitor Counter Application (CI/CD Pipeline)

> A full-stack web application to track visitor counts with a complete automated CI/CD pipeline.

This project is designed to implement and showcase modern DevOps best practices, focusing on automated build and deployment pipelines (CI/CD).

---

## 🚀 Technology Stack

| Category         | Technology          |
| ---------------- | ------------------- |
| Application      | Node.js, Express.js |
| Containerization | Docker              |
| Orchestration    | Kubernetes (Helm)   |
| CI/CD            | GitHub Actions      |
| Registry         | Docker Hub          |

---

## 🏗 Project Architecture

The project follows an automated CI/CD pipeline workflow:

* **Source Control:**
  Code changes are pushed to the GitHub repository.

* **Continuous Integration (CI):**
  GitHub Actions automatically builds the Docker image and pushes it to Docker Hub.

* **Continuous Deployment (CD):**
  Helm charts are used to manage and deploy the application to a Kubernetes cluster.

---

## 🛠 Local Setup

### 🔧 Prerequisites

Ensure you have the following installed:

* Docker Desktop / Minikube
* kubectl
* Helm

---

## 🚀 Deployment

To deploy the application to your local Kubernetes cluster:

```bash
helm upgrade --install my-visitor ./visitor-chart
```

---



## 👨‍💻 Developed By

**Mazid Hossain**
