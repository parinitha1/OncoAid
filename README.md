🧠 OncoAid – Bone Tumor Treatment Prediction App
OncoAid is a full-stack AI-powered web application designed to predict the optimal treatment for bone tumor patients using Machine Learning (ML), Deep Learning (DL), Quantum Machine Learning (QML), Quantum Neural Networks (QNN), and Large Language Models (LLM). It offers healthcare professionals accurate insights and personalized prevention tips powered by advanced AI technologies.

🚀 Features
✅ User Authentication & Authorization
Secure sign-up and login

Session handling with user credentials stored in SQLite

🧾 Patient Input System
Patient data inputs:

Age

Sex

Grade

Histological Type

MSKCC Type

Site of Primary STS

User-friendly forms with dropdown menus

🧠 ML & DL-Based Prediction
ML: Random Forest

DL: TensorFlow/Keras Neural Network

Real-time predictions with performance feedback

⚛️ Quantum Machine Learning (QML)
Quantum-enhanced data analysis using Qiskit

Improved pattern recognition and prediction accuracy

🧬 Quantum Neural Networks (QNN)
Hybrid classical-quantum models for complex classification tasks

Experimental integration with QML pipelines

💬 Gemini LLM Integration
Gemini LLM powers:

Natural language explanations of model predictions

Patient-specific prevention tips

Enhanced understanding of outcomes using conversational AI

🛠️ Tech Stack
Layer	Technology
Frontend	HTML, Tailwind CSS, JavaScript
Backend	Python, Flask
ML/DL Models	Scikit-learn, TensorFlow
QML/QNN	Qiskit, PennyLane (optional for QNN)
LLM	Gemini LLM
Database	SQLite
Deployment	Localhost / Flask Server

📂 Folder Structure
pgsql
Copy
Edit
OncoAid/
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── about.html
│   ├── contact.html
│   ├── style.css
│   └── script.js
├── backend/
│   ├── app.py
│   ├── auth.py
│   ├── model_utils.py
│   ├── preprocessing.py
│   └── qml_qnn.py
├── models/
│   ├── ml_model.pkl
│   ├── dl_model.h5
│   ├── qml_model.qasm
│   ├── qnn_model.qnn
│   └── gemini_model.llm
├── db/
│   └── users.db
├── static/
│   └── images/, icons/, css/
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── signup.html
│   ├── about.html
│   └── contact.html
├── requirements.txt
└── README.md
💡 How to Run the Project
Clone the repository

bash
Copy
Edit
git clone https://github.com/yourusername/OncoAid.git
cd OncoAid
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask server

bash
Copy
Edit
python backend/app.py
Note: To run QML and QNN modules, ensure you have Qiskit and optional PennyLane installed.

🔮 Future Enhancements
📤 CSV Upload + Batch Prediction
Upload and predict treatments for multiple patients via CSV

📊 Advanced Analytics Dashboard
Charts for input distributions, accuracy, and trends

🧾 Admin Panel
Audit logs, user activity, and model performance tracking

🌐 Multi-language Support
Support for multiple languages across the UI

