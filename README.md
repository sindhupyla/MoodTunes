
# 🎵 Emotion-Based Music Recommendation System

A web-based application that detects your **current emotion using OpenCV**, processes your facial expression through a **Machine Learning model**, and recommends songs based on the identified emotions.

---

## 💡 How It Works

1. **Emotion Detection**
   The app uses OpenCV to capture your facial expressions via webcam.

2. **Face Cropping & Prediction**
   It crops your face from each frame and passes it to a trained ML model around 30–40 times within 2–3 seconds.

3. **Emotion Aggregation**
   The list of predicted emotions is sorted by frequency, and duplicates are removed.

4. **Music Recommendation**
   Based on the sorted emotions, songs are recommended that best suit your current emotional state.

---

## 🛠 Installation & Running the App

1. **Clone the Repository or Add Files to PyCharm**
   Create a new project in PyCharm and add the project files.

2. **Install Dependencies**
   Open the terminal and run:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**
   Launch the app using:

   ```bash
   streamlit run app.py
   ```

   Or provide the full path:

   ```bash
   streamlit run path/to/app.py
   ```

---

## 📦 Libraries Used

* `streamlit` – for building the web app
* `opencv` – for image capture and face detection
* `numpy` – numerical computations
* `pandas` – data manipulation
* `tensorflow` – for deep learning model backend
* `keras` – high-level neural network API

---

## ▶️ Demo / Run Guide

You can refer to the following link to see how to run the project in detail:
🔗 [Click here](https://drive.google.com/file/d/1fmd0zIELFi6SswZqqJdz_dg3-JW_Ja1n/view?usp=drivesdk)

---
