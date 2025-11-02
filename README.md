# 🌾 Crop Recommendation System

An AI-powered **Crop Recommendation System** that helps farmers determine the **most suitable crop** to grow based on environmental and soil conditions.  
This project leverages **Machine Learning** techniques to predict the optimal crop for a given set of parameters.

---

## 🧭 Overview

The project supports **smart agriculture** by recommending crops using features like:
- 🧪 Soil nutrients — Nitrogen (N), Phosphorus (P), Potassium (K)
- 🌡️ Temperature
- 💧 Humidity
- 🌱 Soil pH value
- 🌦️ Rainfall

It uses a **supervised ML model** trained on a **UCI dataset** to predict the most profitable crop.

---

## 💻 Tech Stack

| Category | Technology |
|-----------|-------------|
| 🐍 Language | Python |
| 📚 Libraries | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| 🧠 Model | Random Forest / Decision Tree / SVM |
| 📂 Dataset | UCI Machine Learning Repository |
| 🧩 IDE | Jupyter Notebook / VS Code |
| 🌐 Optional | Streamlit (for web deployment) |

---

## 📊 Dataset Details

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/)
- **Attributes:**

| Feature | Description |
|----------|-------------|
| N | Nitrogen content ratio in soil |
| P | Phosphorus content ratio in soil |
| K | Potassium content ratio in soil |
| temperature | Average temperature (°C) |
| humidity | Relative humidity (%) |
| ph | Soil pH value |
| rainfall | Average rainfall (mm) |
| label | Recommended crop name |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone this repository
```bash
git clone https://github.com/your-username/Crop-Recommendation-System.git
cd Crop-Recommendation-System
