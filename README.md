Here's the updated README to reflect the use of Gemini LLM for providing prevention tips:

---

🧠 **OncoAid – Bone Tumor Treatment Prediction App**

OncoAid is a full-stack AI-powered web application that predicts the optimal treatment for bone tumor patients using Machine Learning (ML), Deep Learning (DL), and Large Language Models (LLM). Built for accessibility, accuracy, and ease-of-use, OncoAid provides healthcare practitioners and researchers with intelligent insights based on patient inputs.

🚀 **Features**
✅ **Current Functionality**
🔐 **User Authentication & Authorization**

* Sign-up and login with session handling
* Credentials stored securely with SQLite backend

🧾 **Patient Input System**

* Input patient features like:

  * Age
  * MSKCC Type
  * Site of Primary STS
* Clean and intuitive web form with dropdowns

🧠 **ML & DL Treatment Prediction**

* **Machine Learning**: Random Forest
* **Deep Learning**: Neural Network with TensorFlow/Keras
* Real-time prediction display with model accuracy and performance indicators

  ⚛️ Quantum Machine Learning (QML) & Quantum Neural Networks (QNN)

QML: Implement quantum-enhanced algorithms using Qiskit for improved pattern detection.

QNN: Combine classical neural networks with quantum circuits for advanced predictions.

Real-time predictions powered by QML and QNN models.

💬 **Gemini LLM Integration**

* Integration with **Gemini LLM** for intelligent prediction explanations, medical insights, and prevention tips.
* Provides personalized **prevention tips** based on the patient's data and prediction results.
* Natural language processing to deliver easily understandable, patient-specific advice.

📁 **Backend Processing (Python)**

* Data preprocessing, prediction handling, and database logging
* Trained models saved as .pkl, .h5, and LLM files
* Integration with Gemini LLM for prediction explanations and prevention tips

💻 **Frontend Interface**

* Built with HTML, Tailwind CSS, and JavaScript
* Interactive and responsive UI for both desktop and mobile

🛠️ **Tech Stack**

| Layer           | Technology                     |
| --------------- | ------------------------------ |
| Frontend        | HTML, Tailwind CSS, JavaScript |
| Backend         | Python, Flask                  |
| ML/DL Models    | Scikit-learn, TensorFlow       |
| LLM Integration | Gemini LLM                     |
| Database        | SQLite                         |
| Deployment      | Localhost / Flask server       |

📁 **Folder Structure**

```
OncoAid/
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── about.html
│   ├── contact.html
│   ├── style.css (Tailwind CDN or config)
│   └── script.js
├── backend/
│   ├── app.py
│   ├── model_utils.py
│   ├── auth.py
│   └── preprocessing.py
├── models/
│   ├── ml_model.pkl
│   ├── dl_model.h5
│   └── gemini_model.llm (example for LLM integration)
├── db/
│   └── users.db
├── static/
│   └── images, icons, or CSS
├── templates/
│   ├── login.html
│   ├── signup.html
│   ├── index.html
│   ├── about.html
│   └── contact.html
├── requirements.txt
└── README.md


💡 **How to Run the Project**

1. Clone the repository

   ```bash
   git clone https://github.com/yourusername/OncoAid.git
   cd OncoAid
   ```
2. Install the required dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Start the application

   ```bash
   python backend/app.py
   ```

🔮 **Future Enhancements**

* **CSV Upload + Batch Prediction**: Support for CSV file upload to predict treatment in bulk.
* **Advanced Analytics Dashboard**: Visual insights on user inputs, model metrics, and prediction trends.
* **Admin Panel**: User analytics, audit logs, and model tracking.
* **Multi-language Support**: Enable UI localization for broader accessibility.

---


