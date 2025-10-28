# 🩺 Multiple Disease Prediction System  
An AI-powered tool for predicting multiple diseases.

---

## 🔍 Overview  
In today’s world, early diagnosis of diseases like diabetes, heart disease and Parkinson’s can save lives.  
This project uses AI and machine learning to **predict multiple diseases** from user-input health data — helping individuals and healthcare professionals make data-driven decisions.  
The Multiple Disease Prediction System takes in patient metrics, applies preprocessing and trained ML models, and outputs predictions with intuitive UI.

---

## 💡 Motivation  
- Manually assessing risk factors for multiple diseases is time-consuming and error-prone.  
- An AI-driven approach can help provide quick, consistent, and actionable predictions.  
- As part of my BE in CSE (AIML) and full-stack/AI project experience, I wanted to build something practical and impactful in healthcare.

---

## ✨ Features  
- ✅ Predicts **Diabetes**, **Heart Disease**, and **Parkinson’s Disease** (or as many as your dataset/models support)  
- ✅ Interactive web UI (e.g., with Streamlit) for easy user input  
- ✅ Clean data preprocessing pipelines (handling missing values, scaling, feature extraction)  
- ✅ Trained machine-learning models for each disease — ready to deploy  
- ✅ Modular architecture — add new diseases or swap models easily  
- ✅ Visualizations of input features / prediction results (optional)  

---

## 🧰 Tech Stack  
- **Programming Language:** Python  
- **Web Framework / Interface:** Streamlit or Flask (depending on your implementation)  
- **ML & Data Processing:** Pandas, NumPy, Scikit-Learn  
- **Model Storage:** `.sav` or pickle files for trained models  
- **UI / Visualisation:** Matplotlib / Seaborn or built-in Streamlit charts  
- **Environment / Deployment:** Requirements file, virtual environment, optionally Docker or Streamlit Cloud  

---

## 🧱 Architecture  
User Input → Pre-Processing → Feature Extraction → Model Inference (for each disease) → Prediction & Results

- **Input Module:** Takes user health metrics (age, blood pressure, glucose, vocal features, etc)  
- **Preprocessing Module:** Cleans, transforms and normalises the data  
- **Model Module:** Loads trained ML models for each disease and runs inference  
- **Output Module:** Displays prediction outcome, probability score, and optionally visual insights  

---

## 📥 Usage  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/Multiple-Disease-Prediction-System.git  
   cd Multiple-Disease-Prediction-System
   ```
2. Create a virtual environment:

```bash
python -m venv venv  
source venv/bin/activate    # On macOS/Linux  
venv\Scripts\activate       # On Windows
```
3. Install required dependencies:

```bash

pip install -r requirements.txt
```  
4. Run the application:

```bash

streamlit run app.py        # or the respective script in your repo  

5. Open your browser to http://localhost:8501 (default) and interact with the UI.

📊 Results & Demo
Example: Input metrics for candidate → Model predicts “High risk of Diabetes: 87%”, “Moderate risk of Heart Disease: 68%”
UI displays simplified explanation and highlights key contributing features.

---

