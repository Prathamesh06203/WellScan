
# 🧠 WellScan - AI-Powered Medical Diagnostic Platform

**WellScan** is an intelligent AI-based medical diagnostic web application that provides instant disease detection using advanced machine learning and deep learning models. It is designed to assist users with early detection of critical diseases from medical imagery and health data, all from the comfort of their home.

## 🚀 Features

- 🔬 Disease Detection: Supports 7 types of diseases:
  - Brain Tumor (MRI)
  - Pneumonia (Chest X-ray)
  - Covid-19 (Chest X-ray)
  - Heart Disease (Health parameters)
  - Diabetes (Retinopathy Images)
  - Breast Cancer (Mammogram Images)
  - Alzheimer's (MRI)

- 🤖 Models Used:
  - CNN, VGG-16 (Image-based diseases)
  - Random Forest, XGBoost (Tabular data)
  - Logistic Regression, SVM, KNN (Comparative studies)

- 📊 Real-time Prediction Interface
- 📷 Upload Medical Images or Enter Health Parameters
- 🧠 Backend with trained ML/DL models
- 🌐 User-friendly Frontend Interface
- 🛡️ Secure and private prediction system

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap
- **Backend:** Python, Flask
- **ML/DL:** TensorFlow, Keras, Scikit-learn, OpenCV
- **Deployment:** Streamlit / Flask Server (Customizable)
- **Data Sources:** Kaggle, Open-source medical datasets

---

## 📁 Project Structure

```
WellScan/
│
├── static/                  # CSS, JS, assets
├── templates/               # HTML templates
├── models/                  # Pre-trained model files
├── images/                  # Sample input images
├── app.py                   # Flask app main file
├── utils.py                 # Helper functions
└── README.md
```

---

## 🧪 How to Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/WellScan.git
   cd WellScan
   ```

2. **Create a Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate   # For Linux/Mac
   venv\Scripts\activate      # For Windows
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**
   ```bash
   python app.py
   ```

5. **Open in Browser**
   ```
   http://localhost:5000
   ```

---

## 📷 Sample Output

![WellScan Screenshot](images/screenshot.png)

---

## 📚 Datasets Used

- [Brain MRI Dataset – Kaggle](https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection)
- [Pneumonia Dataset – Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)
- [Retinal Images for Diabetic Retinopathy – Kaggle](https://www.kaggle.com/competitions/diabetic-retinopathy-detection)
- And others from open-source repositories

---

## 🙌 Contributions

Feel free to open issues or submit pull requests to improve this platform. All contributions are welcome!

---

## 📃 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Developed by

**Prathamesh Kshirsagar**  
[LinkedIn](https://www.linkedin.com/in/prathameshkshirsagar/) | [Portfolio](https://your-portfolio-link.com) | [GitHub](https://github.com/your-username)

```

---

Let me know if you want to include a **video demo**, **live link**, or add **badges** (build, version, license) on top of the file. I can generate those too.
