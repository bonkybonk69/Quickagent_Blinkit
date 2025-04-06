# Quickagent_Blinkit
# QuickAgents.AI – GenAI Inventory Optimization for Blinkit 🚚🧠

A GenAI-powered multi-agent system designed for Blinkit to solve stockouts, overstocking, and inventory delays across micro-warehouses using real-world data and predictive intelligence.

---

## 🚨 Problem Statement

Blinkit frequently experiences:
- Stockouts of high-demand items during peak times (rain, festivals, IPL)
- Overstock and wastage of perishables
- Poor coordination between local hubs
- Supplier delays due to reactive decisions

This results in refund losses, delivery delays, and customer dissatisfaction.

---

## 💡 Our Solution – QuickAgents.AI

We built a 5-agent architecture using GenAI to handle inventory management proactively:

- 🏪 **Hub Agent** – Monitors low stock and expiry
- 📊 **Demand Agent** – Predicts demand using trends, weather & events
- 🔁 **Inter-Hub Agent** – Moves stock across hubs in real-time
- 📦 **Supplier Agent** – Automates supplier reordering with lead-time logic
- 🧠 **GenAI Advisor** – Optimizes product pricing & app visibility

---

## 📊 Datasets Used

From the hackathon:
- `inventory_monitoring.csv`
- `pricing_optimization.csv`
- `demand_forecasting.csv`

We also use:
- Public Weather API
- IPL/Event triggers

---

## 🧱 Tech Stack

- Python
- Streamlit (for dashboard)
- SQLite (for hub-wise local memory)
- Ollama LLMs (for GenAI-based insights)
- Matplotlib/Plotly for data visuals

---

## 📽️ Demo Video

[Add video link here after upload]

---

## 📁 Repository Contents

- `data/`: Provided datasets
- `visuals/`: Diagrams & dashboard mockups
- `notebooks/`: EDA & forecasting logic
- `dashboard_app/`: Streamlit-based prototype

---

## 👩‍💻 Team Lead

**Abhinav – Team QuickAgents.AI**
