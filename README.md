# 🌍 ImExIQ — AI-Powered Cross-Border Trade Risk Intelligence Platform

**ImExIQ (Import–Export Intelligence Quotient)** is an end-to-end trade analytics platform that quantifies and predicts cross-border deal risk by combining **policy, market, logistics, geopolitical, and compliance signals** into a unified intelligence dashboard.

The system enables exporters, importers, and supply-chain operators to evaluate trade corridors, understand risk drivers, and make optimized sourcing and routing decisions.

---

## 🚀 Key Features

### 📊 Market Intelligence

* Multi-currency FX monitoring dashboard
* Synthetic FX volatility modeling
* Currency exposure analytics

### 🏛 Policy & Tariff Intelligence

* Bilateral tariff risk scoring engine
* Trade agreement awareness
* Corridor-level policy risk modeling

### 📦 Product & Compliance Intelligence

* HS category-based compliance scoring
* Product regulatory complexity assessment
* Category-driven operational risk signals

### 🌐 Geopolitical Intelligence

* Country-level political stability mapping
* Corridor macro-risk aggregation
* Bilateral stability index feature engineering

### 🤖 AI Risk Prediction

* Composite trade risk label generation (weak supervision)
* Random Forest risk prediction model
* Feature importance explainability
* ML-ready feature engineering pipeline

### 🖥 Product Experience

* Interactive frontend dashboard
* Backend inference API
* Scenario-driven trade risk exploration

---

## 🧠 Risk Modeling Framework

ImExIQ models trade risk as a multi-dimensional function:

```
Trade Risk = f(
  Tariff Risk,
  FX Volatility,
  Compliance Risk,
  Political Stability,
  Logistics Signals
)
```

A synthetic composite label is first generated using domain-weighted aggregation, after which machine learning models learn latent relationships between features and risk outcomes.

---

## 🏗 System Architecture

```
Frontend (React Dashboard)
        ↓
Backend API (Inference & Data Layer)
        ↓
ML Model (Risk Prediction Engine)
```

* **Frontend** → Visualizes FX, corridor analytics, and risk outputs
* **Backend** → Handles data processing, scoring, and inference
* **Model Layer** → Predicts final trade risk score

---

## 📁 Project Structure

```
ImExIQ/
│
├── backend/
│   ├── api/
│   └── main.py
│
├── frontend/
│   └── src/
│
├── ml/
│   └── risk_scoring/
│
├── data/
│
├── artifacts/
│   └── trade_risk_model.pkl
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone repository

```bash
git clone <repo-url>
cd ImExIQ
```

### 2️⃣ Backend setup

```bash
pip install -r requirements.txt
uvicorn backend.main:app --reload
```

### 3️⃣ Frontend setup

```bash
cd frontend
npm install
npm run dev
```

---

## 🤖 Model Training

Train the risk prediction model:

```bash
python ml/risk_scoring/train_risk_model.py
```

Outputs:

* trained model artifact
* evaluation metrics
* feature importance

---

## 📡 Deployment

Recommended stack:

| Layer    | Deployment          |
| -------- | ------------------- |
| Frontend | Vercel              |
| Backend  | Render              |
| Model    | Embedded in backend |

---

## 📈 Example Use Case

1. User inputs trade corridor (origin, destination, product)
2. System computes engineered risk signals
3. ML model predicts composite risk score
4. Dashboard visualizes risk and underlying drivers

---

## 🎯 Project Vision

ImExIQ aims to evolve into a **global trade intelligence layer** that continuously ingests market, policy, and supply-chain signals to deliver predictive trade risk insights and optimization recommendations.

---

## 👨‍💻 Contributors

* Tanmay Singh
* Tanveer Singh
* Tanuj Lohani

---

## 📜 License

MIT License

---

**ImExIQ — Intelligent decisions for global trade.**
