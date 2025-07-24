# Career-Prediction-System
Sure! Here's the **updated README** with badges added at the top for a more professional and visually appealing look. You can customize the badges based on your actual project status (like license, build status, version, etc.). I'll include placeholders that you can update accordingly.

---

# 🌟 Career Path Predictor

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](#)
[![Version](https://img.shields.io/badge/version-1.0.0-brightgreen)](#)
[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](#)
[![GitHub stars](https://img.shields.io/github/stars/vaishnavsinha/career-path-predictor?style=social)](https://github.com/Sinhavaishnavi/career-path-predictor)

**A smart, interactive web application that predicts a suitable career path based on a user's skills, interests, and personality traits.**

This project leverages **four different machine learning models** to provide accurate and robust career recommendations. Built with **Streamlit**, the app offers a clean, intuitive user interface and an intelligent backend powered by a complete machine learning pipeline.

---

## 🚀 Features

✅ **Multi-Model Prediction System**  
- Uses **four classification models**:  
  - Decision Tree  
  - Support Vector Machine (SVM)  
  - Random Forest  
  - XGBoost  
- Predictions are combined for more reliable and well-rounded career suggestions.

✅ **Interactive & User-Friendly UI**  
- Built using **Streamlit**  
- Clean layout with organized tabs  
- Wide range of input fields to capture detailed user profiles (skills, interests, personality traits)

✅ **End-to-End ML Pipeline**  
- Data preprocessing, feature engineering, model training, and prediction all handled in one cohesive workflow  
- Designed for easy extension and retraining

---

## 🧪 How It Works

1. The user fills out a detailed questionnaire covering:
   - Skills (e.g., coding, writing, designing)
   - Hobbies and interests
   - Personality traits (e.g., introverted/extroverted, analytical/creative)

2. Input is processed and passed to all four models.

3. Each model predicts a career path based on the input profile.

4. The app aggregates the results and suggests the most suitable career options.

---

## 🛠️ Technologies Used

- **Streamlit** – For the web interface
- **Scikit-learn** – For ML models and preprocessing
- **Pandas, NumPy** – For data manipulation
- **Matplotlib, Seaborn** – For data visualization
- **Requests** – Optional (for future API integrations)

---

## 📦 Installation

### Step 1: Clone the repository
```bash
git clone https://github.com/Sinhavaishnavi/career-path-predictor.git
cd career-path-predictor
```

### Step 2: Install dependencies
```bash
pip install -r requirements.txt
```

### Step 3: Run the app
```bash
streamlit run app.py
```

> 🌐 The app will automatically open in your browser at `http://localhost:8501`.

---

## 📁 Project Structure

```
career-path-predictor/
│
├── app.py                # Main Streamlit app
├── pkl.py              # ML model definitions and training logic
├── data/mldata.csv                 # Dataset and preprocessing scripts
├── pythonFunctions/GUI.py,predict.py,training.py 
|__db.py     # database
├── requirements.txt      # Python dependencies
└── README.md             # This file
```

---

## 🙌 Acknowledgements

- **Developed by**: [Vaishnav Sinha](https://github.com/Sinhavaishnavi)


---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve the models, add new features, or enhance the UI, feel free to open an issue or submit a pull request.

---

## 📬 Feedback & Support

If you have any questions, suggestions, or want to collaborate, feel free to reach out via GitHub or email.

---


# Career-Prediction-System
