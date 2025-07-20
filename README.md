# 💪 Workout Tracker – Real-Time Exercise Monitoring System

The Workout Tracker is a real-time exercise monitoring system that uses computer vision to analyze and improve user workouts. It tracks exercises like planks, push-ups, squats, and bicep curls using a standard webcam, providing real-time feedback, repetition counts, and posture correction through pose estimation.

Designed with accessibility in mind, the project leverages OpenCV, MediaPipe, and Flask to offer a lightweight, responsive web-based interface that enhances the user’s fitness journey without requiring additional hardware.

---

## ⚙️ Features

- 📸 Camera-based pose estimation using MediaPipe
- 🔁 Real-time repetition counting
- 🧍 Posture and form detection
- 📊 Performance analytics
- 💬 Live feedback via web interface
- ⚙️ No wearable devices needed — just a camera!

---

📁 Project Structure
-------------------
- static/                 # Static assets (CSS, JS, media)
- templates/              # HTML templates (Flask)
- app.py                  # Flask backend
- pose_estimation.py      # Pose estimation engine
- utils.py                # Helper functions
- requirements.txt        # Python dependencies
- README.md               # Project documentation

  ---


## 🧠 Tech Stack

- **Python 3.7+** – Programming language  
- **Pandas** – Data loading and preprocessing  
- **NumPy** – Numerical operations  
- **Matplotlib** – Basic data visualization  
- **Seaborn** – Statistical plotting (optional)  
- **Scikit-learn** – Machine learning models and evaluation  
  - RandomForest, SVC, train-test split, metrics  
- **XGBoost** – Gradient boosting classifier  
- **Imbalanced-learn (SMOTE)** – Class imbalance handling  
- **Pickle** – Saving and loading trained models
  
---

## 🚀 How to Run the Project

---

Follow these steps to set up and run the project locally:

***Step 1: Clone the Repository***

git clone https://github.com/your-username/your-repo-name.git

cd your-repo-name

---

***Step 2: Install the Required Dependencies***

pip install -r requirements.txt

---

***Step 3: Run the Main Script***

python cancer_detection.py

---

***Step 4: Output***

The script will:

Preprocess the dataset

Handle class imbalance using SMOTE

Train RandomForest, SVC, and XGBoost models

Display classification reports and confusion matrices

Save models as .pkl files

---

## 📌 Results

## 📈 Accuracy Chart
![Accuracy](images/accuracy_comparison.png)

## 🧪 Confusion Matrix - XGBoost
![XGBoost](images/confusion_matrix_xgboost.png)

## 🌲 Confusion Matrix - Random Forest
![RandomForest](images/confusion_matrix_randomforest.png)

## 💻 Confusion Matrix - SVC
![SVC](images/confusion_matrix_svc.png)

---

##🚀 Quick Tips
-------------
- ✅ Use a virtual environment to avoid conflicts
- 📌 Run the notebook first if you want step-by-step exploration
- 🧠 Modify hyperparameters in `cancer_detection.py` for better accuracy
- 📈 Logs and results are saved in the `outputs/` folder

---

## ✅ 📦 Prerequisites

Before running this project, ensure you have the following installed:
Python 3.7 or higher
Jupyter Notebook or any Python IDE
pip (Python package installer)

---

## ✅ 📌 Conclusion

This project demonstrates how machine learning algorithms can be used to detect cancer using a dataset of diagnostic features. By comparing different models such as Random Forest, SVC, and XGBoost, we were able to evaluate and visualize their performance through accuracy scores and confusion matrices.

---

## ✅ 📌 Key outcomes

Successfully trained and evaluated multiple ML models.
Achieved strong prediction performance (refer to accuracy_comparison.png).
Visualized model results using confusion matrices for deeper insights.
