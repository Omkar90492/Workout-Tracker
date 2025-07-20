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

- Python 3.9+
- OpenCV – Video capture and frame handling
= MediaPipe – Pose detection and analysis
- Flask – Web framework for UI and backend
- HTML/CSS/JavaScript – Frontend display
  
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

***Step 3: Run the Flask app***

python app.py


---

## 📌 Results

## 📈 User Interface of the Exercise Tracking System
![User Interface](images/user_interface.jpg)

## 🧪 Confusion Matrix - XGBoost
![XGBoost](images/confusion_matrix_xgboost.png)

## 🌲 Confusion Matrix - Random Forest
![RandomForest](images/confusion_matrix_randomforest.png)

## 💻 Confusion Matrix - SVC
![SVC](images/confusion_matrix_svc.png)

---

##🚀 Quick Tips
-------------
- Use in a well-lit room for best pose detection 📸
- Keep your full body visible in the camera frame 👤
- Works best on desktop or laptop with a stable webcam 💻
- Make sure Python version is 3.9 or above 🐍

---

## ✅ 📦 Prerequisites
-------------
- Python installed (>= 3.9)
- A webcam device
- Internet browser (for Flask UI)
- Pip installed
- Recommended: Virtual environment (venv)
  
---

## ✅ 📌 Conclusion

This project demonstrates how real-time camera-based fitness tracking can assist users in achieving their workout goals. With a simple webcam and a browser, users receive immediate feedback on their form and performance.
The project can evolve into a full-fledged fitness assistant with:

- 📈 AI-based personalized coaching
- ☁️ Cloud data storage
- ⌚ Wearable integration
- 📱 Cross-platform (iOS/Android) support


---

## ✅ 📌 Key outcomes

- Built a real-time AI-based workout assistant
- Learned to integrate computer vision with web interfaces
- Improved understanding of pose estimation (MediaPipe)
- Created a scalable fitness tracker framework
