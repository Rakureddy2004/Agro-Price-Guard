# 🍅 Agro-Price Guard: AI-Powered Agricultural Price Prediction

## 📌 Project Overview
Agro-Price Guard is a machine learning-based application designed to estimate agricultural prices using weather information. It provides a predicted price, market alert level, and suggested selling action through an interactive dashboard.

## 🎯 Objectives
- Estimate agricultural prices using machine learning.
- Analyze weather inputs such as temperature and humidity.
- Display market alerts and suggested actions.
- Support data-driven agricultural decision-making.

## 📸 Project Dashboard

![Agro-Price Guard Dashboard](agro-price-guard-dashboard.png)

**Example Output:**
- **Location:** Krishnagiri, Tamil Nadu
- **Temperature:** 34.85°C
- **Humidity:** 22.37%
- **Predicted Price:** ₹1,248.60
- **Alert Level:** Normal
- **Suggested Action:** Mandi Sale

*Note: These are example dashboard values, not guaranteed market predictions.*

## ✨ Key Features
- Interactive weather input sliders.
- Machine learning-based price estimation.
- Market alert display.
- Suggested market action.
- User-friendly dashboard.

## 🛠️ Technologies Used
- Python
- Machine Learning
- XGBoost and Scikit-learn, if used in the final pipeline
- Pandas and NumPy, if used
- Streamlit or FastAPI, depending on the application implementation

## ⚙️ How It Works
1. Enter temperature and humidity values.
2. Run the prediction engine.
3. Generate an estimated agricultural price.
4. Display the alert level and suggested action.

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Agro-Price-Guard.git
cd Agro-Price-Guard
```

Create a virtual environment:

```bash
python -m venv venv
venv\Scripts\activate
```

Install the dependencies:

```bash
python -m pip install -r requirements.txt
```

Run the application using the command appropriate for your implementation. For example, if it uses Streamlit:

```bash
python -m streamlit run app.py
```

Replace `app.py` with your actual dashboard filename.

## 🔮 Future Enhancements
- Real-time weather integration.
- Live agricultural market prices.
- Support for multiple crops.
- Historical price analysis.
- Improved prediction accuracy and model evaluation.

## ⚠️ Disclaimer
This project is intended for educational and research purposes. Predictions should be verified against actual market prices before making agricultural selling decisions.

## 👩‍💻 Author
**Rakshitha V**  
MCA – Artificial Intelligence and Machine Learning  
Jain (Deemed-to-be University), Bengaluru, India
