# 🏔️ mountAIn – AI-Powered Ski Safety Assistant

**mountAIn** is an AI assistant that helps skiers make safer decisions on the slopes by analyzing weather, snow, and wind conditions. Whether you're planning a weekend trip or checking conditions in real time, mountAIn provides personalized safety insights.

---

## 🎯 Purpose

Skiing is thrilling—but it comes with risks. This project aims to:

- Assess mountain safety using environmental data  
- Provide go/no-go recommendations based on current conditions  
- Raise awareness of potential hazards before heading out  

---

## 🧠 How It Works

mountAIn gathers environmental data (weather, snowpack, wind) from public sources and applies rule-based logic or machine learning models to assess risk levels.

### Core components:
- **Data ingestion** from weather and snow APIs or datasets  
- **Risk assessment logic** based on rules or AI  
- **User interface** via CLI (and possibly web, in future)

---

## 📁 Project Structure

mountAIn/
├── data/ # Raw and processed datasets
├── notebooks/ # Exploration and prototype notebooks
├── src/ # Main application code
│ ├── data/ # Data handling scripts
│ ├── models/ # Risk scoring logic or ML models
│ └── main.py # Entry point for assistant
├── tests/ # Unit tests
├── requirements.txt # Python dependencies
├── README.md # Project overview
└── .gitignore


---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/dorianied/mountAIn.git
cd mountAIn

pip install -r requirements.txt

python src/main.py --location "Chamonix" --date "2025-01-14"


---



