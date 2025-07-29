# superNova_2177/ ⚡️🌌🎶🚀🌸🔬
STRICTLY A SOCIAL MEDIA PLATFORM  
Intellectual Property & Artistic Inspiration  
Legal & Ethical Safeguards
[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/BP-H/community_guidelines/blob/main/LICENSE)
[![Python 3.11](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/downloads/release/python-3110/)
[![Open Source](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-red.svg)](https://opensource.org/)

**A scientifically grounded social metaverse engine for collaborative creativity**

This repository hosts `superNova_2177` — an experimental protocol merging computational sociology, quantum-aware simulation logic, and creative systems engineering. It models symbolic influence, interaction entropy, and network resonance across users and content.

⚠️ This is *not* a financial product, cryptocurrency, or tradable asset. All metrics (e.g., Harmony Score, Resonance, Entropy) are symbolic — for modeling, visualization, and creative gameplay only. Symbolic tokens and listings introduced in the gameplay modules have **no real-world monetary value**.

The repository includes a *patch monitor* that scans new contributions for these required disclaimers. If added files or lines don't contain the required phrases, the commit will fail in CI and locally if pre-commit hooks are installed.

---

## 🚀 Local Quick Start

### 1. Set Up Environment
First, clone the repository and navigate into the project directory.
```bash
git clone [https://github.com/BP-H/superNova_2177.git](https://github.com/BP-H/superNova_2177.git)
cd superNova_2177
```
Create and activate a Python virtual environment. This requires Python 3.11+.
```bash
# Create the environment
python -m venv venv

# Activate on Windows
venv\Scripts\activate

# Activate on macOS/Linux
source venv/bin/activate
```

### 2. Install Dependencies
Install the required packages using the `requirements.txt` file. This file should contain all packages needed for the application to run.
```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit App
Launch the Streamlit user interface.
```bash
streamlit run ui.py
```
The application will open in your web browser, typically at `http://localhost:8501`.

---

## ☁️ Deploying on Streamlit Cloud

You can deploy the user interface online using Streamlit Cloud.

1.  **Fork this repository** on GitHub.
2.  **Create a clean `requirements.txt` file** in the root of your repository. It must contain only the essential packages for the deployed app to run. Streamlit Cloud **only** uses this single file.
3.  Sign in to [Streamlit Cloud](https://streamlit.io/cloud) and select **New app**.
4.  Choose your forked repository and set the **Main file path** to `ui.py`.
5.  Under **Advanced settings > Secrets**, add any required secrets like `SECRET_KEY` and `DATABASE_URL`.
    ```toml
    SECRET_KEY = "your-strong-random-secret"
    DATABASE_URL = "your-database-connection-string"
    ```
6.  Click **Deploy**.

---

## 🐳 Docker

You can build a standalone Docker image or run the API with Postgres and Redis via `docker-compose`.

Build the image:
```bash
docker build -t supernova-2177 .
```

Or bring up the full stack:
```bash
cp .env.example .env  # set your own secrets
docker-compose up
```
The application will be available at `http://localhost:8000`, and the Streamlit UI at `http://localhost:8888`.

---

## 🧪 Running Tests

For local development, you can install testing-specific dependencies. `requirements-dev.txt` is intended for this purpose.

```bash
# Install packages for running tests
pip install -r requirements-dev.txt

# Run the test suite
pytest
```
You can also run static type checks with `mypy`:
```bash
mypy .
```

---

## ✨ Features

* **🧠 Smart Scoring** — Combines confidence, signal strength, and NLP sentiment
* **🛡️ Manipulation Detection** — Flags collusion, bias, and temporal anomalies
* **📊 Multi-Factor Analysis** — Diversity, reputation, coordination, timing
* **📋 Actionable Reports** — Output includes flags, scores, certification level
* **🧵 Fully Modular** — Each analysis step is plug-and-play

---

## 🏗️ Architecture (v4.6)

* `validation_integrity_pipeline.py` — Orchestrator for full validation logic
* `reputation_influence_tracker.py` — Tracks and scores validators over time
* `diversity_analyzer.py` — Detects echo chambers and affiliation bias
* `temporal_consistency_checker.py` — Tracks time-based volatility
* `network_coordination_detector.py` — Spots suspicious group behavior using sentence‑embedding similarity

---

*Built for scientific integrity in a world of noise.*
