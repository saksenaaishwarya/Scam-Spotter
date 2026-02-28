# 🕵️‍♂️ Spot the Scam – Job Fraud Detection App

A machine learning-powered web app that detects whether a job posting is real or fake. Developed to help job seekers avoid online employment scams using natural language processing and supervised learning.

---

## 🚀 Live Demo

🔗 **Hosted App**: [https://spothescamai.streamlit.app](https://spothescamai.streamlit.app)

---


## 🧠 Project Overview

Online job scams are rising rapidly, luring victims through fake offers and fraudulent listings. This app uses a trained machine learning model to classify job descriptions as **legitimate** or **fraudulent**, helping users make safer career decisions.

---

## ⚙️ Key Features & Technologies Used

- 🔍 Predicts if a job post is fake or real
- 🧠 ML model trained using Logistic Regression
- 📋 Text preprocessing (stopwords, TF-IDF, etc.)
- 🌐 Streamlit-based interactive frontend
- 🧪 Model trained on real job post dataset
- 📈 F1-Score: **0.88**

---

## 🛠️ Technologies

-pandas
-scikit-learn
-streamlit
-matplotlib
-seaborn
-plotly
-joblib
-Pillow
-wordcloud
-numpy
-requests
-shap

---

## 📁 Dataset & Model File

Due to file size, the trained model and original dataset are hosted externally.

📥 **Download Link**: [https://drive.google.com/your-dataset-and-model-link](https://drive.google.com/drive/folders/1BZPYrFZbL7TJfIuDWyMYdyYm5hY4IsGk?usp=drive_link)

After downloading:

- Place `model.pkl` in the `models/` folder
- Place the dataset (optional) in the `data/` folder

---

## 🧪 Setup Instructions (Run Locally)

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/spot-the-scam.git
   cd spot-the-scam
   ```

2. **(Optional) Create a virtual environment**:

   ```bash
   python -m venv venv
   source venv/bin/activate       # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Download model file** from Google Drive and place it in the `models/` folder.

5. **Run the app**:

   ```bash
   streamlit run app/app.py
   ```

---

## 📊 Model Performance

| Metric    | Value |
| --------- | ----- |
| F1 Score  | 0.88  |
| Accuracy  | 89.3% |
| Precision | 0.87  |
| Recall    | 0.89  |

---

## 🙋 Team Members

- **Aishwarya Saksena** — *Lead Developer & Data Scientist*

---

## 🔗 Other Links

- 🔹 Hosted App: [https://spothescamai.streamlit.app](https://spothescamai.streamlit.app)
- 🔹 Demo Video: [https://www.youtube.com/your-video-link](https://www.youtube.com/watch?v=kdChsikXbNA)

---

## 📂 Directory Structure

```plaintext
spot_the_scam_project/
│
├── app/
│   └── app.py
│
├── models/
│   └── model.pkl
│
├── data/
│   └── [not included – download from Drive]
│
└── README.md
```

---

