# 🚀 Kubernetes Hands-On Course | Zero to Production | DevOps • GitOps • MLOps

> 🎥 This repository contains all manifests, commands, diagrams, and projects used in my **Kubernetes course**.

📌 Learn Kubernetes with **real hands-on labs**, not just theory  
📌 Structured in **numerical sequence** for step-by-step learning  
📌 Covers **CI/CD, GitOps, Observability, Security, MLOps, and Production Operations**

---

# 📚 Course Flow (Follow in Order)

| # | Module | Folder |
|---|--------|--------|
00 | Environment Setup | `00-SETUP/` |
01 | Core Workloads | `01-CORE-WORKLOADS/` |
02 | Networking | `02-NETWORKING/` |
03 | Configuration & RBAC | `03-CONFIGURATION/` |
04 | Storage | `04-STORAGE/` |
05 | Scaling & Autoscaling | `05-SCALING/` |
06 | Package Management | `06-PACKAGE-MANAGEMENT/` |
07 | Observability | `07-OBSERVABILITY/` |
08 | Security | `08-SECURITY/` |
09 | CI/CD Pipelines | `09-CI-CD/` |
10 | GitOps with ArgoCD | `10-GITOPS/` |
11 | Deployment Strategies | `11-DEPLOYMENT-STRATEGIES/` |
12 | Production Operations | `12-PRODUCTION-OPERATIONS/` |
13 | MLOps on Kubernetes | `13-MLOPS/` |
14 | Real Projects | `14-PROJECTS/` |
15 | Interview Preparation | `15-INTERVIEW-PREP/` |
16 | Cheatsheets | `16-CHEATSHEETS/` |
17 | Architecture Diagrams | `17-ARCHITECTURE-DIAGRAMS/` |

📄 Full video index → **COURSE-INDEX.md**

---

# 🔥 What You Will Learn

✔ Pods, ReplicaSets, Deployments, DaemonSets, StatefulSets  
✔ Jobs & CronJobs  
✔ Services, Ingress, DNS, Network Policies  
✔ ConfigMaps, Secrets, Namespaces, RBAC  
✔ Persistent Volumes, StorageClasses, Dynamic Provisioning  
✔ HPA, VPA, Cluster Autoscaler  
✔ Helm & Kustomize  
✔ Prometheus, Grafana, EFK Logging, Alertmanager  
✔ Pod Security, Zero Trust Networking, Image Scanning (Trivy)  
✔ CI/CD → GitHub Actions & GitLab CI  
✔ GitOps → ArgoCD App of Apps  
✔ Blue-Green, Canary (Argo Rollouts), Rolling Updates  
✔ Resource Quotas, LimitRanges, PDB, Cluster Upgrades  
✔ Kubeflow, KServe, GPU Workloads, Batch Training  
✔ Production-Grade Kubernetes Architecture  

---

# 🧪 Hands-On Projects

## 🔹 Full Stack Application
- Frontend + Backend + MySQL  
- Ingress + ConfigMaps + Secrets  
- PVC + StorageClass  

## 🔹 Microservices with Observability
- Prometheus + Grafana dashboards  
- EFK logging stack  
- HPA autoscaling  

## 🔹 CI/CD + GitOps Pipeline
- Build → Scan → Push → Deploy  
- ArgoCD auto-sync  
- Trivy image scanning  

## 🔹 MLOps Pipeline
- Training Jobs  
- Scheduled batch training (CronJobs)  
- Model serving with KServe  
- GPU scheduling  

---

# ⚙️ Prerequisites

- Basic Docker knowledge  
- kubectl installed  
- Kind or Minikube cluster  
- 8GB RAM minimum  

📂 Setup guide → `00-SETUP/`

---

# 🛠️ Tools Covered

- Kubernetes  
- Docker  
- Helm  
- Kustomize  
- ArgoCD  
- Prometheus  
- Grafana  
- EFK Stack  
- Trivy  
- HashiCorp Vault  
- Kubeflow  
- KServe  

---

# ▶️ YouTube Playlist

📺 **Watch the Full Course:**  
👉 _[Add Playlist Link]_  

Each video maps directly to a numbered folder in this repo.

---

# 📈 Who Is This For?

✅ DevOps Engineers  
✅ SREs  
✅ Cloud Engineers  
✅ Platform Engineers  
✅ MLOps Engineers  
✅ Kubernetes Interview Preparation  

---

# 🧠 Interview Preparation

Includes:

- Scenario-based questions  
- Troubleshooting labs  
- Real production cases  

📂 Check: `INTERVIEW-PREP/`

---

# 🧩 How to Use This Repo

1️⃣ Watch the YouTube video  
2️⃣ Go to the mapped folder  
3️⃣ Apply the YAML:

```bash
kubectl apply -f deployment.yaml
```
4️⃣ Verify:
```bash
kubectl get pods -A
```
5️⃣ Debug using:
```bash
kubectl describe pod <pod-name>
kubectl logs <pod-name>
```

---

# ⭐ GitHub Support

If this repository helped you:

⭐ Star the repo  
🔔 Subscribe to the YouTube channel  
📢 Share with your DevOps friends  

---

# 🧑‍💻 Author

**Vishal Sen**  
DevOps • MLOps • AIOps  

📺 YouTube: [Add Channel Link]  
💼 LinkedIn: https://www.linkedin.com/in/vishalsen-connect/  
📧 Contact: vishalsen.connect@gmail.com  