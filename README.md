# MLOps Journey 🚀

A hands-on, step-by-step learning path from ML experimentation to production-ready systems.

> "The goal is not to learn everything. The goal is to build real things."

---

## About

This repository documents my practical MLOps learning journey — real projects, real deployments, real mistakes.

No fluff. No tutorial clones. Each section contains working code with notes on what broke and how I fixed it.

**Background:** Computer Engineering graduate | IT Support & System Administration | DevOps path

---

## Roadmap

| # | Topic | Status | Tools |
|---|-------|--------|-------|
| 01 | Experiment Tracking | 🔄 In Progress | MLflow |
| 02 | Model Serving | 📋 Planned | FastAPI |
| 03 | CI/CD | 📋 Planned | GitHub Actions |
| 04 | Model Monitoring | 📋 Planned | Evidently AI |
| 05 | Infrastructure | ✅ Done | Terraform, LocalStack |

**Legend:** ✅ Done | 🔄 In Progress | 📋 Planned

---

## Projects

### ✅ Real-Time Object Detection (YOLOv8)
> End-to-end ML deployment — from local prototype to cloud production

- **v1.0** → Streamlit Cloud deployment
- **v2.0** → Dockerized, deployed on Oracle Cloud (1GB RAM + 2GB swap)
- Solved: Python/OpenCV dependency conflicts, memory optimization on low-resource server

🔗 [github.com/yunusemreerken/real-time-object-detection-yolov8](https://github.com/yunusemreerken/real-time-object-detection-yolov8)

---

### ✅ Infrastructure as Code (Terraform + LocalStack)
> AWS infrastructure simulation locally before touching real cloud

- Provisioned S3 buckets and IAM roles via Terraform
- Used LocalStack to simulate AWS services without cloud costs
- Practiced destroy/apply cycles, state management

📁 See: [05-infrastructure/](./05-infrastructure/)

---

### 🔄 Experiment Tracking (MLflow)
> Reproducible ML experiments — no more "which model was that?"

- Track parameters, metrics, and artifacts per run
- Compare experiments with MLflow UI
- Model registry basics

📁 See: [01-experiment-tracking/](./01-experiment-tracking/)

---

### 📋 Model Serving (FastAPI)
> Expose ML models as REST APIs

- Wrap trained model in FastAPI endpoint
- Request validation with Pydantic
- Dockerize the API for deployment

📁 See: [02-model-serving/](./02-model-serving/)

---

### 📋 CI/CD for ML (GitHub Actions)
> Automate testing and deployment pipelines

- Lint and test on every push
- Automated model validation before deploy
- Docker image build and push to registry

📁 See: [03-cicd/](./03-cicd/)

---

### 📋 Model Monitoring (Evidently AI)
> Know when your model starts to drift

- Data drift detection
- Model performance monitoring over time
- Alerting basics

📁 See: [04-monitoring/](./04-monitoring/)

---

## Stack

```
ML:            Python, YOLOv8, scikit-learn
Experiment:    MLflow
Serving:       FastAPI, Docker
CI/CD:         GitHub Actions
Infra:         Terraform, LocalStack (AWS simulation)
Cloud:         Oracle Cloud (ARM64)
Monitoring:    Evidently AI (planned)
```

---

## Connect

- GitHub: [github.com/yunusemreerken](https://github.com/yunusemreerken)
- LinkedIn: [linkedin.com/in/yunus-emre-erken](https://linkedin.com/in/yunus-emre-erken)
