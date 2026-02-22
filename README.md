<div align="center">

<img src="public/logo.png" alt="RIFT Forensics Logo" width="220" />

# 🛡️ RIFT Forensics Engine
### *Next-Generation Money Muling & AML Detection Network*

[![Live Interactive Demo](https://img.shields.io/badge/🔴_LIVE_DEMO-Online-00e5a0?style=for-the-badge&logo=vercel)](https://rift-forensic.vercel.app/)
[![GitHub Repository](https://img.shields.io/badge/📂_SOURCE-GitHub-1e293b?style=for-the-badge&logo=github)](https://github.com/Kowalskiye/Riftforensic)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React_18-20232A?style=flat-square&logo=react&logoColor=61DAFB)]() [![Three.js](https://img.shields.io/badge/Three.js-black?style=flat-square&logo=three.js&logoColor=white)]()[![Python](https://img.shields.io/badge/Python_3.11-14354C?style=flat-square&logo=python&logoColor=white)]() [![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)]() [![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)]() [![NetworkX](https://img.shields.io/badge/NetworkX-005C84?style=flat-square)]() [![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)]() [![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=white)]()

<br>

> **🏆 RIFT 2026 Hackathon · Deep Graph Analytics / RegTech Track 🏆**
>
> *An enterprise-grade, high-throughput topological intelligence system engineered to autonomously untangle multi-layered financial crime and fraud syndicates.*

<br>
</div>

---

## ⚡ The Challenge & The RIFT Solution

**The Crisis:** Global financial institutions hemorrhage trillions of dollars annually to increasingly sophisticated, obfuscated money laundering networks. Traditional rules-based Anti-Money Laundering (AML) systems are plagued by catastrophic false-positive rates and fundamentally fail to detect non-linear, multi-hop syndicates.

**The Solution:** We engineered the **RIFT Forensics Engine**—a real-time, high-throughput RegTech platform that ingests massive, unstructured transactional datasets and transforms them into actionable topological intelligence. By leveraging deep graph-theoretic algorithms and vectorized memory processing, the engine autonomously detects cyclic layering, fan-in/fan-out smurfing, and shadow shell networks in **sub-30-second execution windows**.

---

## 🛠️ Enterprise Tech Stack & Infrastructure

| Domain | Core Technologies | Strategic Purpose |
| :--- | :--- | :--- |
| 🎨 **Frontend & WebGL** | React 18, Three.js | GPU-accelerated WebGL spatial rendering mapping thousands of vertices in a force-directed topology without frame drops. |
| 🧠 **Backend Core API** | Python 3.11, FastAPI | Ultra-low-latency asynchronous API layer for massive data ingestion and real-time response. |
| 📊 **Deep Analytics** | Pandas, NetworkX | Vectorized in-memory processing for tabular-to-graph restructuring and complex network heuristic computations. |
| ☁️ **Cloud DevOps** | Vercel, Render | CI/CD pipelines deploying to Vercel's Global Edge Network for UI, and Render's containerized compute for the backend. |

---

## 🧬 Algorithmic Core & Graph Theory

* 🌐 **Multi-Dimensional Topological Ingestion:** Raw transactional ledgers are mapped into a Directed Graph — entities become weighted vertices, transactions become directed edges.
* 🌀 **Deep Cycle Enumeration (Layering Detection):** Optimized depth-first search targeting elementary cycles of lengths **3, 4, and 5**.
* 🕸️ **Structural Smurfing Identification:** Analyzes asymmetric vertex degrees to expose placement and integration hubs (*Aggregation mules vs. Dispersal distributors*).
* 🛡️ **Proprietary Temporal Heuristics (Zero-Tolerance FP Filter):** Identifies super-nodes (`degree > 50`) and cross-references them chronologically, neutralizing legitimate corporate bulk processors to a threat score of `0.0`.

### 🚨 AI-Ready Threat Matrix

| Vector Signal | Algorithmic Threat Weight | Impact Level |
| :--- | :--- | :---: |
| **Deep Cycle Participation** | Base +50 (Critical Breach), +10 per overlapping cycle | 🔴 **Critical** |
| **Layered Shell Sub-Graph** | +40 (Identifies obfuscation proxy chains) | 🟠 **High** |
| **Fan-Out (Dispersal)** | +35 (Identifies integration laundering) | 🟡 **Medium** |
| **High Centrality Bridge Node** | +15 (Betweenness Centrality factor > 0.1) | 🟣 **Elevated** |

---

## 🏗️ Decoupled System Architecture

<details>
<summary><b>👁️ Click to view the Data Flow Architecture Diagram</b></summary>
<br>

```text
[ Secure Client Environment ]
   │
   ▼ Multipart Form Data Stream (CSV)
┌────────────────────────────────────────────────────────┐
│  Presentation & WebGL Engine (Vercel Global Edge)      │
│  · Client-side Sanitization & State Management         │
│  · Three.js 3D Force-Directed Topology Renderer        │
│  · Dynamic Risk-Matrix Dashboard & SAR Export          │
└──────────────────────────┬─────────────────────────────┘
                           │ Asynchronous POST /analyze
                           ▼
┌────────────────────────────────────────────────────────┐
│  Analytics & ML Heuristics API (Render Cloud Compute)  │
│  · High-Speed Vectorized Normalization (Pandas)        │
│  · Directed Acyclic/Cyclic Graph Generation (NetworkX) │
│  · Sub-Graph Isomorphism & Deep Cycle Enumeration      │
│  · O(1) Look-up Temporal Heuristic Filtering Engine    │
└────────────────────────────────────────────────────────┘
```

</details>

---

## 🚀 Local Deployment Guide

### Prerequisites
- Python 3.11+
- Node.js installed at `C:\Program Files\nodejs`

### Terminal 1 — Backend (FastAPI)

```powershell
cd c:\Users\Furqan970\OneDrive\Desktop\rift-forensic-pwioii-main\backend
.\venv\Scripts\python.exe -m uvicorn main:app --reload --port 8000
```

The backend will be running at `http://127.0.0.1:8000`

### Terminal 2 — Frontend (Vite)

```powershell
cd c:\Users\Furqan970\OneDrive\Desktop\rift-forensic-pwioii-main
$env:PATH = "C:\Program Files\nodejs;" + $env:PATH
npm run dev
```

> ⚠️ **Note:** The `$env:PATH` line is required because Node.js is not in the system PATH by default. You must run this line every time you open a new terminal. To fix this permanently, add `C:\Program Files\nodejs` to your system Environment Variables.

The frontend will be running at `http://localhost:5173`

### Permanent PATH Fix (One-Time Setup)

1. Press **Win + S** → search **"Environment Variables"**
2. Click **"Edit the system environment variables"**
3. Click **"Environment Variables"**
4. Under **System Variables**, find **Path** → click **Edit**
5. Click **New** → paste `C:\Program Files\nodejs`
6. Click **OK** on all windows
7. Restart your terminal — `npm` will now work without the `$env:PATH` line

---

## ☁️ Production Deployment

| Service | Platform | URL |
| :--- | :--- | :--- |
| Frontend | Vercel | https://rift-forensic.vercel.app |
| Backend | Render | https://riftforensic-backend.onrender.com |

> ⚠️ The Render free tier spins down after 15 minutes of inactivity. The first request after inactivity may take up to 50 seconds to respond — this is normal.

---

## 🔬 Detection Algorithm Flowchart

```text
                        ┌─────────────────────┐
                        │   CSV File Upload    │
                        └──────────┬──────────┘
                                   │
                                   ▼
                        ┌─────────────────────┐
                        │  Data Normalization  │
                        │  (Pandas Vectorized) │
                        └──────────┬──────────┘
                                   │
                                   ▼
                        ┌─────────────────────┐
                        │  Build Directed      │
                        │  Transaction Graph   │
                        │  (NetworkX DiGraph)  │
                        └──────────┬──────────┘
                                   │
               ┌───────────────────┼───────────────────┐
               ▼                   ▼                   ▼
   ┌──────────────────┐ ┌──────────────────┐ ┌──────────────────┐
   │  Cycle Detection │ │ Smurfing Check   │ │  Shell Network   │
   │  DFS — lengths   │ │ Fan-in / Fan-out │ │  Sub-graph       │
   │  3, 4, and 5     │ │ degree analysis  │ │  Isomorphism     │
   └────────┬─────────┘ └────────┬─────────┘ └────────┬─────────┘
            │                    │                     │
            └────────────────────┼─────────────────────┘
                                 │
                                 ▼
                      ┌─────────────────────┐
                      │  Super-Node Filter   │
                      │  degree > 50?        │
                      │  → Score set to 0.0  │
                      │  (Legit Payroll)     │
                      └──────────┬──────────┘
                                 │
                                 ▼
                      ┌─────────────────────┐
                      │  Threat Score        │
                      │  Aggregation         │
                      │  (0 – 100 Index)     │
                      └──────────┬──────────┘
                                 │
               ┌─────────────────┴─────────────────┐
               ▼                                   ▼
   ┌──────────────────┐                 ┌──────────────────┐
   │  🔴 HIGH RISK    │                 │  🟢 CLEAR        │
   │  Flag & Report   │                 │  No Action       │
   │  SAR Export      │                 │  Required        │
   └──────────────────┘                 └──────────────────┘
```

---

<div align="center">
<i>Engineered with precision for the future of decentralized financial security.</i>
</div>
