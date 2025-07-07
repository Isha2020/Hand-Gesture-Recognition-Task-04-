 # Task-04-
# Hand Gesture Recognition using Deep Learning

This project aims to build a deep learning model to **recognize hand gestures** from image data. It can be used for **gesture-based control systems** and **human-computer interaction**.

---

## 🧠 Task Objective

**Task-04 (prodigy infotech Internship)**  
**Goal:** Develop a hand gesture recognition model that accurately identifies different hand gestures using image or video data.

---

## 📂 Files in this Repository

- `hand_gasture.ipynb` → Jupyter Notebook with data preprocessing, model training, and evaluation.
- `gesture_model.pkl` → Trained deep learning model file (saved using pickle/joblib).
- `label_map.pkl` → Dictionary mapping labels to gesture names (used during prediction).


---

## 📊 Dataset

Dataset used: [LEAP Gesture Dataset](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)

- 10 classes of gestures
- ~20,000+ grayscale images
- Collected from 10 users using Leap Motion sensor

---

## 🔧 Libraries Used

- `TensorFlow` / `Keras`
- `NumPy`
- `Matplotlib`
- `OpenCV`
- `joblib` or `pickle` for model saving

---

## 🎯 Model Performance

- ✅ **Final Accuracy:** 99.18%
- 🧮 **Final Loss:** 0.0152

---

## 🖥️ Future Scope (Optional)

- Integrate with **webcam** to recognize real-time gestures
- Use for sign language recognition or home automation

---

## 💡 How to Use

1. Clone/download the repo.
2. Run `hand_gasture.ipynb` in Jupyter/Colab.
3. Load the model using `gesture_model.pkl`.
4. Use OpenCV to capture real-time webcam input and predict gestures.

---

## 🔗 Author

- 👩‍💻 **Isha Sarkar**  
Machine Learning Intern @ prodigy infotech
[LinkedIn](https://www.linkedin.com) | [GitHub](https://github.com/Isha2020)

---

