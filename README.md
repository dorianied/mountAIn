# 🏔️ mountAIn – AI-Powered Ski Safety Assistant

**mountAIn** is an AI assistant designed to help skiers make safer decisions on the slopes by analyzing weather, snow, and wind conditions. Whether you're planning a weekend trip or checking conditions in real time, mountAIn gives you personalized safety insights.

---

## 🎯 Purpose

Skiing is thrilling—but it comes with risks. This project aims to:

- Assess mountain safety using environmental data
- Provide go/no-go recommendations based on conditions
- Raise awareness of potential hazards before heading out

---

## 🧠 How It Works

mountAIn gathers environmental data (weather, snowpack, wind) from public sources and applies simple rules or models to assess risk.

Core components:
- **Data ingestion** from weather/snow APIs or datasets
- **Risk assessment logic** (rules or machine learning)
- **User interface** via CLI or web app (planned)

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

2. Install dependencies

pip install -r requirements.txt

3. Run the assistant (example)

python src/main.py --location "Chamonix" --date "2025-01-14"

🤝 Contributing
Feel free to fork the project and submit pull requests, or open an issue to discuss ideas or bugs. Contributions are very welcome!

📄 License
MIT License – see the LICENSE file for details.

👋 About
Created by Dorian in Amsterdam – combining AI, weather data, and a love for snow sports.

