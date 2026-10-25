# 🏗️ ConstructIQ AI Enterprise

> **AI-Powered Construction Intelligence, Estimation & Risk Analytics Platform**  
> *Developed for Infosys Springboard Internship Project*

---

## 📌 Overview

**ConstructIQ AI Enterprise** is a comprehensive, AI-driven construction management system designed to streamline portfolio governance, cost & material estimation, delay forecasting, safety compliance, and risk analytics for modern infrastructure projects.

Equipped with an intelligent LLM assistant powered by **Ollama (Llama 3.2)**, executive dashboards, and automated PDF report generation, ConstructIQ AI delivers actionable insights for engineering, financial, and executive leadership teams.

---

## ✨ Key Features

- **🏠 Executive & Operational Dashboards**: Real-time KPI metrics, active projects tracking, portfolio expenditure, and progress visualizers.
- **💰 AI Cost Estimation**: Detailed budget allocation, breakdown by labour/equipment/materials, and variance tracking.
- **🧱 Material Estimation & Inventory**: Automated bill of quantities (BOQ) calculation, vendor rate comparisons, and stock monitoring.
- **⏳ Schedule & Delay Prediction**: Predictive analytics identifying delay-prone activities and bottleneck mitigation pathways.
- **🔧 Construction Rework Management**: Root-cause analysis, rework cost impact evaluation, and quality audit workflows.
- **⚠️ Risk Intelligence & Safety**: Dynamic site safety scores, risk matrices, and compliance tracking.
- **🤖 ConstructIQ AI Assistant**: Context-aware construction domain chatbot powered by **Ollama (Llama 3.2)** with domain guardrails.
- **📄 Executive Reports & Documentation**: Instant PDF/Excel report downloads and document status tracking.

---

## 🛠️ Technology Stack

- **Frontend & App Framework**: [Streamlit](https://streamlit.io/) (v1.45+)
- **Data & Analytics**: Python 3.13, Pandas, NumPy, Scikit-Learn
- **Visualization**: Plotly Interactive Charts, Matplotlib
- **Document & Export**: ReportLab, OpenPyXL, Pillow
- **AI / LLM Engine**: [Ollama](https://ollama.com/) running `llama3.2`

---

## 🚀 Quick Start Guide

### 1. Prerequisites
- Python 3.10+
- (Optional for AI Chatbot) [Ollama](https://ollama.com/) with `llama3.2`:
  ```bash
  ollama run llama3.2
  ```

### 2. Installation
Clone the repository and install the dependencies:
```bash
git clone https://github.com/lakshana-gs/ConstructIQ_AI.git
cd ConstructIQ_AI
pip install -r requirements.txt
```

### 3. Run the Application
```bash
streamlit run app.py
```
Open your browser and navigate to `http://localhost:8501`.

---

## 🔐 Login Credentials

| Role | Email | Password |
| :--- | :--- | :--- |
| **Administrator** | `lakshana@constructiq.com` | `1234` |
| **Project Manager** | `manager@constructiq.com` | `manager123` |
| **Site Engineer** | `engineer@constructiq.com` | `engineer123` |

---

## 📂 Project Structure

```text
ConstructIQ_AI/
├── app.py                  # Main Streamlit application entry point
├── config.py               # Global configurations, theme & settings
├── requirements.txt        # Python package dependencies
├── style.css               # Custom enterprise UI stylesheet
├── LICENSE                 # MIT License
├── README.md               # Project documentation
├── assets/                 # Brand assets and imagery
├── auth/                   # Authentication logic and role management
├── components/             # Reusable UI components & sidebar navigation
├── data/                   # Construction datasets (CSV/JSON)
├── modules/                # Core analytical & dashboard modules
└── utils/                  # Analytics engine, LLM integration & report generators
```

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).
