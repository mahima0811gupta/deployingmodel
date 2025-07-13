 Multiple Disease Prediction App

A Streamlit-based web application that uses machine learning models to predict the likelihood of the following diseases:

- 🩸 **Diabetes**
- ❤️ **Heart Disease**
- 🧬 **Breast Cancer**
- 🧠 **Parkinson's Disease**

## 🚀 Live Demo

🔗 [Live App on Streamlit Cloud](https://your-live-app-link-here.com)

## 📂 Repository Structure

├── app.py # Main Streamlit app
├── diabetes_model.sav 
├── heart_model.sav 
├── breast_cancer.sav 
├── parkinsons_model.sav 
├── requirements.txt
├── Procfile
├── runtime.txt 
└── README.md 

## 💡 Features

- 📊 User-friendly multi-page interface via `streamlit_option_menu`
- 🔒 Robust input validation with user-friendly error messages
- ⚙️ Multiple disease predictions in a single app
- 🧠 Predictive models trained using Scikit-learn


---

## 💡 Features

- 📊 User-friendly multi-page interface via `streamlit_option_menu`
- 🔒 Robust input validation with user-friendly error messages
- ⚙️ Multiple disease predictions in a single app
- 🧠 Predictive models trained using Scikit-learn

---

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/mahima0811gupta/multiple-disease-prediction-app.git
   cd multiple-disease-prediction-app

2.Install dependencies:
pip install -r requirements.txt

3.Run the Streamlit app:
streamlit run app.py



 Tech Stack
Frontend: Streamlit

Backend/ML: Python, Scikit-learn, Pickle

UI Components: streamlit-option-menu

Deployment: Streamlit Cloud / Heroku (Procfile included)

Models Used
Each disease module uses a pre-trained .sav model built using Scikit-learn algorithms. These models were trained on well-known public datasets.
