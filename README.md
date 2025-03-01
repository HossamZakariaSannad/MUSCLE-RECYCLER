# 🏋️‍♂️ MUSCLE-RECYCLER

**Muscle Recycler** is an AI-powered system designed to assist users during workout exercises by providing real-time feedback and guidance using computer vision techniques. The system leverages the **OpenPose** model for pose estimation and tracks exercise repetitions, joint angles, and posture accuracy.

> 🚨 **Status:** Inactive (Not Deployed)

---

## 📌 Project Overview

Muscle Recycler is built to revolutionize home workouts by combining **AI** and **computer vision** to monitor exercises, count repetitions, and provide corrective feedback. This system offers guidance using an **Avatar** that visually demonstrates proper form, helping users improve their posture and avoid injuries.

---

## ⚙️ System Phases

### 1️⃣ Exercise Recognition
- Detects the type of exercise the user is performing (e.g., squats, push-ups, etc.).
- Utilizes computer vision techniques and pre-defined movement patterns.

### 2️⃣ Pose Estimation (OpenPose Model)
- Extracts human body keypoints from the video stream using **OpenPose**.
- Tracks joints (shoulders, elbows, knees, etc.) frame-by-frame.

### 3️⃣ Angles Measurement
- Calculates joint angles in real time.
- Tracks movement accuracy based on predefined ideal angles for each exercise.

### 4️⃣ Data Preprocessing
- Filters noise in detected keypoints.
- Normalizes and smooths joint movements to improve accuracy.

### 5️⃣ Counting Repetition
- Detects and counts completed repetitions for each exercise.
- Identifies valid and invalid repetitions based on posture and range of motion.

### 6️⃣ Feedback
- Provides live feedback such as "Keep your back straight" or "Lower your hips."
- Feedback is based on real-time analysis of posture and angles.

### 7️⃣ Guidance Avatar
- Visual avatar demonstrating correct posture and movement.
- Compares user's form to ideal form for better understanding.

---

## 🛠️ Technologies Used

| Technology   | Purpose                          |
|--------------|----------------------------------|
| Python       | Core language                    |
| OpenPose     | Pose estimation model            |
| OpenCV       | Video processing & computer vision |
| NumPy        | Data processing                   |
| Math         | Angle calculations                |

---

## 🚀 Current Status

✅ System is theoretically designed and partially implemented.  
❌ The project is **not deployed** and currently inactive.  
💡 Future plans include turning it into a real-time web or mobile application.

---

## 📂 Folder Structure (Expected)

```
MUSCLE-RECYCLER/
├── README.md
├── data/
├── models/
├── src/
│   ├── exercise_recognition.py
│   ├── pose_estimation.py
│   ├── angle_measurement.py
│   ├── preprocessing.py
│   ├── repetition_counter.py
│   ├── feedback.py
│   ├── avatar_guidance.py
├── requirements.txt
└── demo_video/
```

---

## 📣 Future Plans

- ✅ Improve exercise detection accuracy.
- ✅ Add more exercises to the system.
- ✅ Deploy as a web application (possibly using Flask or FastAPI).
- ✅ Integrate real-time guidance with a 3D Avatar.

---

## 📧 Contact

For inquiries or contributions, feel free to open an issue or fork the project.
