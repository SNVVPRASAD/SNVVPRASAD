# Hey there, I'm Siva Prasad Mandalapu | Machine Learning Engineer.

**Production ML | MLOps | Fraud & Healthcare AI**

---

## About Me

**Machine learning engineer** who gets models into production and keeps them healthy there. **5 years** running real-time ML in regulated industries: **5M+ fraud scores/day at 99.9% uptime** at HDFC Bank and **13x faster medical-imaging inference** at Philips Healthcare. **AWS Certified Machine Learning – Specialty.**

**At Philips Healthcare**: Rebuilt model serving with TensorRT & containerized FastAPI on GPU edge devices, cutting inference latency **13x (2s → 150ms per scan)** at **10K+ scans/day**, and shortened release-candidate turnaround from **4 weeks to 1**.

**At HDFC Bank**: Served **5M+ real-time fraud scores/day** at under **100 ms** and **99.9% uptime**, cutting false-positive alerts **30%** and fraud losses **35%**.

**Based in**: Irving, TX | **+1 (943) 300-8560** | **msprasadm.1996@gmail.com**

---

## Technical Arsenal

### MLOps
![MLflow](https://img.shields.io/badge/-MLflow-0193E3?style=flat&logo=mlflow&logoColor=white) ![Kubeflow](https://img.shields.io/badge/-Kubeflow-326CE5?style=flat&logo=kubernetes&logoColor=white) ![Airflow](https://img.shields.io/badge/-Airflow-017CEE?style=flat&logo=apache-airflow&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white) ![Jenkins](https://img.shields.io/badge/-Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)

CI/CD for ML · model registry · experiment tracking · automated retraining · drift monitoring · rollback

### Model Serving
![TensorRT](https://img.shields.io/badge/-TensorRT-76B900?style=flat&logo=nvidia&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) ![AWS SageMaker](https://img.shields.io/badge/-AWS%20SageMaker-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![Azure ML](https://img.shields.io/badge/-Azure%20ML-0078D4?style=flat&logo=microsoft-azure&logoColor=white)

Real-time inference · GPU optimization

### Observability
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat&logo=grafana&logoColor=white) ![LangSmith](https://img.shields.io/badge/-LangSmith-1C3C3C?style=flat&logo=langchain&logoColor=white) ![Weights & Biases](https://img.shields.io/badge/-Weights%20%26%20Biases-FFBE00?style=flat&logo=weightsandbiases&logoColor=black)

### Data & Cloud
![Apache Spark](https://img.shields.io/badge/-Apache%20Spark-E25A1C?style=flat&logo=apache-spark&logoColor=white) ![Kafka](https://img.shields.io/badge/-Apache%20Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white) ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white) ![Dask](https://img.shields.io/badge/-Dask-FCA121?style=flat&logo=python&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white) ![AWS S3](https://img.shields.io/badge/-AWS%20S3-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![AWS EC2](https://img.shields.io/badge/-AWS%20EC2-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![AWS Lambda](https://img.shields.io/badge/-AWS%20Lambda-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![AWS EKS](https://img.shields.io/badge/-AWS%20EKS-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)

### ML & Languages
![Python](https://img.shields.io/badge/-Python%203.x-3776ab?style=flat&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat&logo=postgresql&logoColor=white) ![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white) ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) ![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/-XGBoost-FF6B35?style=flat&logo=python&logoColor=white) ![LightGBM](https://img.shields.io/badge/-LightGBM-1F77B4?style=flat&logo=python&logoColor=white) ![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white) ![SHAP](https://img.shields.io/badge/-SHAP-FF6B35?style=flat&logo=python&logoColor=white) ![Flower](https://img.shields.io/badge/-Flower-F2B705?style=flat&logo=python&logoColor=black)

---

##  Professional Experience

###  **Philips Healthcare** | AI/ML Engineer (Contract)
**Remote | Dec 2023 - Present**

- Cut inference latency **13x (2s → 150ms per scan)** at **10K+ scans/day** with no loss in precision by converting PyTorch models to **TensorRT** and rebuilding model serving as containerized **FastAPI** services on on-prem GPU edge devices
- Cut model release-candidate turnaround from **4 weeks to 1** by building ML CI/CD with **GitHub Actions, Jenkins, Docker and Kubernetes**, an **MLflow** model registry, and regression tests on a locked validation set
- Monitored drift and model health for the 10K+ scans/day service with **Prometheus and Grafana**, tracking data drift, service health, and per-subgroup model performance
- Made every training run reproducible over **500GB+** of imaging data with **Spark and Kafka** pipelines, schema validation and automated data-quality gates feeding **AWS SageMaker** training jobs
- Trained models across **5 hospitals** with **zero patient images moved** by building the client-side training and evaluation pipeline for a **federated learning** pilot (Flower)
- Helped cut radiologist review time **35%** in an LLM pilot by building the **LLMOps** layer for a **LangGraph** report-drafting pipeline on Azure OpenAI: LangSmith tracing and automated checks for unsupported statements

**Tech Stack:** ![Python](https://img.shields.io/badge/-Python%203.x-3776ab?style=flat&logo=python&logoColor=white) ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![TensorRT](https://img.shields.io/badge/-TensorRT-76B900?style=flat&logo=nvidia&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) ![MLflow](https://img.shields.io/badge/-MLflow-0193E3?style=flat&logo=mlflow&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat&logo=github-actions&logoColor=white) ![Jenkins](https://img.shields.io/badge/-Jenkins-D24939?style=flat&logo=jenkins&logoColor=white) ![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat&logo=grafana&logoColor=white) ![Apache Spark](https://img.shields.io/badge/-Apache%20Spark-E25A1C?style=flat&logo=apache-spark&logoColor=white) ![Kafka](https://img.shields.io/badge/-Apache%20Kafka-231F20?style=flat&logo=apache-kafka&logoColor=white) ![AWS SageMaker](https://img.shields.io/badge/-AWS%20SageMaker-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![Flower](https://img.shields.io/badge/-Flower-F2B705?style=flat&logo=python&logoColor=black) ![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white) ![LangSmith](https://img.shields.io/badge/-LangSmith-1C3C3C?style=flat&logo=langchain&logoColor=white) ![Azure OpenAI](https://img.shields.io/badge/-Azure%20OpenAI-0078D4?style=flat&logo=microsoft-azure&logoColor=white)


###  **HDFC Bank** | AI/ML Engineer, Fraud & Risk
**Bengaluru, India | Dec 2019 - Nov 2022**

- Served **5M+ real-time fraud scores/day** at under **100 ms** and **99.9% uptime** by deploying containerized model endpoints on **Azure ML and Kubernetes**
- Turned model updates into scheduled, automated releases by building **Kubeflow** retraining pipelines with **MLflow** experiment tracking and model versioning, feature and score drift detection, and automated rollback
- Cut false-positive alerts **30%** at **95% recall** and fraud losses **35%** by partnering with data scientists and fraud analysts to productionize an **LSTM, Transformer and graph neural network** ensemble
- Cut fraud investigation time **40%** by attaching **SHAP** explanations to every flagged transaction and auto-generating case summaries in the format required by RBI auditors
- Improved model **F1 by 22%** with **Pandas and Dask** feature engineering pipelines over **1M+** labeled transactions

**Tech Stack:** ![Python](https://img.shields.io/badge/-Python%203.x-3776ab?style=flat&logo=python&logoColor=white) ![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white) ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white) ![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white) ![XGBoost](https://img.shields.io/badge/-XGBoost-FF6B35?style=flat&logo=python&logoColor=white) ![LightGBM](https://img.shields.io/badge/-LightGBM-1F77B4?style=flat&logo=python&logoColor=white) ![Azure ML](https://img.shields.io/badge/-Azure%20ML-0078D4?style=flat&logo=microsoft-azure&logoColor=white) ![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Kubeflow](https://img.shields.io/badge/-Kubeflow-326CE5?style=flat&logo=kubernetes&logoColor=white) ![MLflow](https://img.shields.io/badge/-MLflow-0193E3?style=flat&logo=mlflow&logoColor=white) ![SHAP](https://img.shields.io/badge/-SHAP-FF6B35?style=flat&logo=python&logoColor=white) ![Pandas](https://img.shields.io/badge/-Pandas-150458?style=flat&logo=pandas&logoColor=white) ![Dask](https://img.shields.io/badge/-Dask-FCA121?style=flat&logo=python&logoColor=white)


## Education

 - **Master of Science in Information Systems** — Marist College, Poughkeepsie, NY (Jan 2023 - Dec 2024)  
 - **Bachelor of Technology in Mechanical Engineering** — Sir C.R.R. College of Engineering, India

---

## Certifications

![AWS](https://img.shields.io/badge/-AWS%20Certified%20Machine%20Learning%20–%20Specialty-FF9900?style=flat&logo=amazon-aws&logoColor=white) ![TensorFlow](https://img.shields.io/badge/-TensorFlow%20Developer%20Certificate%20(Google)-FF6F00?style=flat&logo=tensorflow&logoColor=white) ![DeepLearning.AI](https://img.shields.io/badge/-Generative%20AI%20with%20LLMs%20(DeepLearning.AI%20%26%20AWS)-0056D2?style=flat&logo=coursera&logoColor=white)

---

## Key Achievements

✅ **13x faster inference** (2s → 150ms per scan) | **10K+ scans/day** | no loss in precision  
✅ **5M+ fraud scores/day** at **<100 ms** and **99.9% uptime**  
✅ **35% fraud loss reduction** | **30% fewer false positives** at **95% recall**  
✅ Release-candidate turnaround cut from **4 weeks to 1** with ML CI/CD  
✅ **40% faster fraud investigations** with SHAP explanations | **35% less radiologist review time** in an LLM pilot  
✅ Federated training across **5 hospitals** with **zero patient images moved**  

---

## Let's Connect!

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/siva-prasad-mandalapu)  
[![Email](https://img.shields.io/badge/-Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:msprasadm.1996@gmail.com)  
[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/SNVVPRASAD)  
[![Phone](https://img.shields.io/badge/-Phone-25D366?style=flat&logo=whatsapp&logoColor=white)](tel:+19433008560)

---

## What I'm Currently Exploring

- **LLMOps**: tracing, evaluation & guardrails for agentic pipelines (LangGraph, LangSmith)  
- **Federated learning** for privacy-preserving healthcare AI  
- **GPU inference optimization** for real-time serving at the edge  
- **Trustworthy AI**: drift monitoring, explainability & per-subgroup model performance  

---

*If you find my work interesting, feel free to star my repositories and reach out for collaboration!*  

**Last Updated**: 2026-10-11
