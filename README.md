

#SENTIMENTAL ANALYSIS BASED MUSIC RECOMMENDATION SYSTEM

Developed a real-time Emotion-Based Music Recommender using Streamlit, MediaPipe, and Keras. The system detects user emotions via webcam using facial and hand landmarks and recommends songs dynamically based on detected mood, language, and artist preference.

---

## ?? Features

* ?? 1. Real-time Emotion Detection
* ?? 2. Emotion-Based Song Recommendation
* ?? 3. Live Video Processing
* ?? 4. Deep Learning Powered
* ?? 5. Session State Management
* ??6.Confidence-based prediction output

---

## ?? Technologies Used

* **Python 3.11.5**
* **Streamlit** – Web framework
* **streamlit-webrtc** – Real-time Streaming
* **OpenCV** – Computer Vision
* **MediaPipe** – Landmark Detection
* **python**- Backend Logic

---

## ?? Project Structure

```
emotion-music-recommender/
?
??? app.py                      # Main Streamlit application
??? model.h5                    # Trained deep learning model
??? labels.npy                  # Emotion label classes
??? emotion.npy                 # Stores last detected emotion
?
??? requirements.txt            # Project dependencies
??? README.md                   # Project documentation
?
??? assets/
?   ??? demo_screenshot.png
?
??? utils/
?   ??? emotion_processor.py    # Emotion detection class (optional modularization)
?   ??? helpers.py              # Utility functions
?
??? notebooks/
    ??? model_training.ipynb    # Model training notebook```

---

## ?? How It Works

1. User input(language,singer)
2. webcam activation
3. landmark extraction
4. Feature Engineering(Landmark coordinates converted into relative positions)
5. Emotion Prediction
6. Song Recommendation(via youtube)

---
## Architechture of the image


## ?? How to Run the Project

### 1?? Install Dependencies

```bash
pip install -r requirements.txt
```

### 2?? Run the Application

```bash
python app.py
```

### 3?? Open in Browser

```
http://127.0.0.1:5000
```

---
## ?? Emotion Classification Model
* Format: model.h5
* Framework: Keras
* Type: Deep Neural Network (likely Dense ANN)
* Input:
o Face landmarks (x, y offsets)
o Left hand landmarks
o Right hand landmarks
* Output:
o Emotion class (e.g., Happy, Sad, Angry, Neutral)

---

## ?? Viva Explanation (Short)

This project is an Emotion-Based Music Recommender built using Streamlit. It captures live webcam video using streamlit-webrtc and detects facial and hand landmarks using MediaPipe. These landmarks are converted into numerical features and passed into a trained deep learning model built with Keras. The model predicts the user's emotion such as happy, sad, or angry. Based on the detected emotion, along with user-input language and singer, the system automatically recommends songs by opening relevant search results on YouTube. The goal is to provide personalized music recommendations based on real-time emotional state.”

---

## ? Advantages

* Real-Time Emotion Detection
* Personalized Music Recommendation
* Automatic Mood Recognition
* Lightweight & Fast Model
* Simple Web Interface

---

## ?? Disclaimer

This project is developed for educational purposes only. Emotion detection accuracy may vary based on lighting, camera quality, and model performance. Music recommendations are generated through YouTube search results and are not directly affiliated with or endorsed by YouTube




