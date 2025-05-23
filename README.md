````markdown
# Disease Prediction from Symptoms 🧠💊

This project predicts diseases based on user-reported symptoms using machine learning. It includes both a Python backend for training and prediction, and a simple frontend interface for user interaction.

---

## 🚀 Features
- Predicts probable diseases based on selected symptoms  
- Trained using historical medical data  
- Simple GUI frontend for ease of use  
- Modular, extensible Python code  

---

## 🛠️ Requirements

- **Python 3.10** or **Python 3.12**  
- Git  
- A Windows, macOS or Linux machine  

---

## 📦 Setup Instructions

1. **Clone the repository**  
   ```bash
   git clone https://github.com/sheshadri-s/Disease-Prediction-from-Symptoms.git
   cd Disease-Prediction-from-Symptoms
````

2. **Create & activate a virtual environment**

   * **For Python 3.10**

     ```powershell
     C:\Users\AppData\Local\Programs\Python\Python310\python.exe -m venv venv310
     .\venv310\Scripts\Activate.ps1
     ```
   * **For Python 3.12**

     ```powershell
     C:\Users\AppData\Local\Programs\Python\Python312\python.exe -m venv venv312
     .\venv312\Scripts\Activate.ps1
     ```

3. **Install dependencies**

   ```powershell
   pip install --upgrade pip
   pip install -r requirements.txt
   ```

---

## 🧠 Running the Backend

1. Navigate to the backend folder:

   ```powershell
   cd .\Disease-Prediction-from-Symptoms-master\
   ```
2. Run the prediction script:

   ```powershell
   python main.py
   ```

---

## 💻 Running the Frontend

1. Open a new terminal (with the same venv active) and navigate to the frontend folder:

   ```powershell
   cd ..\Diseaseprediction-frontEnd\
   ```
2. Launch the GUI:

   ```powershell
   python disease_prediction.py
   ```

---

## 📄 Project Structure

```
.
├── Disease-Prediction-from-Symptoms-master/   # Backend code and model training
│   ├── config.yaml
│   ├── main.py
│   ├── data/
│   └── models/
├── Diseaseprediction-frontEnd/                 # Frontend GUI code
│   └── disease_prediction.py
├── requirements.txt
└── README.md
```
