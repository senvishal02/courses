# MLOps Course Repository – Complete Learning Guide

Welcome to the **MLOps Course Repo**, a hands-on, step-by-step repository designed for students and beginners to advanced learners to build a **full production-grade MLOps pipeline**.

This repository covers **real-world tools, secure practices, and best practices** used in the industry.

---

## 🚀 Course Roadmap

This course takes you from the basics of ML and DevOps to full production-grade MLOps:

1. **Environment Setup** – Python, Docker, Kind, MLflow  
2. **Data Management** – Raw & processed datasets, version control with **DVC**  
3. **Source Code & Pipelines** – Modular ML pipelines: data ingestion, preprocessing, features, training, evaluation, prediction  
4. **Experiment Tracking** – MLflow experiments and reproducibility  
5. **Model Serving** – REST API with **FastAPI**, serverless with **KServe** and **Seldon**  
6. **Testing & CI/CD** – Unit tests, integration tests, GitHub Actions  
7. **Orchestration** – Airflow DAGs & Kubeflow pipelines  
8. **Deployment** – Kubernetes manifests, autoscaling, secure namespaces & RBAC  
9. **GitOps** – Continuous deployment using **ArgoCD**  
10. **Monitoring** – Infrastructure & application monitoring with Prometheus & Grafana  
11. **Model Monitoring** – Drift detection with Evidently AI  
12. **Feature Store** – Production-grade features using **Feast**  
13. **Infrastructure as Code** – Terraform for AWS EKS, S3, IAM, and KMS  
14. **End-to-End Projects** – Resume-ready, fully functional ML pipelines  

---

## 📂 Folder Structure & Learning Index

| Folder | Description | Learning Outcomes |
|--------|-------------|-----------------|
| `01-setup` | Environment setup for Python, Docker, Kind, MLflow | Learn to create a local dev environment and containerized Kubernetes cluster |
| `02-data` | Raw & processed datasets | Data management, preprocessing, and DVC versioning |
| `03-src` | ML source code | Data ingestion, validation, preprocessing, feature engineering, training, evaluation, prediction |
| `03-src/01-data` | Data ingestion & validation | Use **Great Expectations** for data quality checks |
| `03-src/02-features` | Feature engineering | Integrate with **Feast Feature Store** |
| `03-src/03-models` | Training & evaluation | Log metrics & artifacts using **MLflow** |
| `03-src/04-pipelines` | Pipeline scripts | Modular pipelines for local, Airflow, and Kubeflow execution |
| `03-src/05-utils` | Utility scripts | Logging, configuration, security (secrets management, encryption) |
| `04-notebooks` | EDA & prototyping | Jupyter notebooks for exploring datasets & features |
| `05-dvc` | DVC pipelines | Version datasets and maintain reproducibility |
| `06-experiments` | MLflow experiment tracking | Track parameters, metrics, artifacts, and compare models |
| `07-serving` | Model serving | Build production-ready REST APIs with **FastAPI**, **KServe**, and **Seldon** |
| `08-tests` | Unit & integration tests | Test data processing, models, pipelines, and APIs |
| `09-ci-cd` | GitHub Actions workflows | Automate training, testing, and deployment |
| `10-k8s` | Kubernetes manifests | Deploy models securely with Namespaces, RBAC, Network Policies, HPA autoscaling |
| `11-kubeflow` | Kubeflow pipelines | Orchestrate ML workflows for production |
| `12-gitops` | ArgoCD GitOps deployment | Automate deployment using GitOps practices |
| `13-monitoring` | Prometheus & Grafana | Monitor infrastructure and applications |
| `14-monitoring-ml` | Model monitoring & drift detection | Detect data/model drift and generate reports using **Evidently AI** |
| `15-feature-store` | Feast Feature Store | Manage and serve production-grade features |
| `16-terraform` | AWS infrastructure as code | Provision EKS cluster, S3, IAM, KMS securely |
| `17-projects` | End-to-end ML projects | Hands-on projects for practice and portfolio building |

---

## ⚡ Quick Start Guide

```bash
# Clone repository
git clone https://github.com/username/mlops.git
cd mlops

# Setup Python environment
bash 01-setup/01-python/setup-venv.sh

# Optional: Start MLflow tracking server
bash 01-setup/04-mlflow/start-mlflow.sh
```


> Follow the folders in **numerical order** for a sequential, hands-on learning experience.

---

## 🛠 Tools & Security Features

| Layer            | Tools / Practices                                                                 |
|-----------------|----------------------------------------------------------------------------------|
| ML Tracking      | MLflow                                                                           |
| Data Versioning  | DVC                                                                              |
| Feature Store    | Feast                                                                            |
| Orchestration    | Airflow, Kubeflow                                                                |
| Model Serving    | FastAPI, KServe, Seldon                                                          |
| CI/CD            | GitHub Actions, Argo Workflows, ArgoCD                                           |
| Deployment       | Kubernetes: Namespaces, RBAC, Network Policies, HPA                               |
| Monitoring       | Prometheus, Grafana, Evidently AI                                                |
| Infrastructure   | Terraform: AWS EKS, S3, IAM, KMS                                                |
| Security         | Secrets encryption, RBAC, Network Policies                                       |
| Testing          | Pytest for unit, integration, and API tests                                      |
| Containerization | Docker with secure images                                                        |

---

## 💡 Learning Tips for Students

1. **01-setup** → Ensure your environment is ready.  
2. **02-data** → Practice data ingestion, preprocessing, and DVC.  
3. **03-src** → Implement models, pipelines, and experiment logging.  
4. **04-notebooks** → Visualize data and models.  
5. **07-serving** → Deploy your first ML model API.  
6. **08-tests** → Ensure code quality.  
7. **09-ci-cd** → Automate training & deployment.  
8. **10-k8s** → Learn secure Kubernetes practices.  
9. **11-kubeflow** → Build end-to-end production pipelines.  
10. **12-gitops** → Automate deployments via GitOps.  
11. **13-monitoring** & **14-monitoring-ml** → Monitor infrastructure and models.  
12. **15-feature-store** → Manage features effectively.  
13. **16-terraform** → Provision cloud infrastructure.  
14. **17-projects** → Build real projects for practice & portfolio.  

---

**Note:** Each folder contains placeholder scripts to be filled in while following the course. Follow the sequence for maximum learning efficiency.