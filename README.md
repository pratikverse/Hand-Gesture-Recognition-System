# 🖐️ Hand Gesture Recognition

Real-time hand and finger gesture recognition using **MediaPipe** and **TensorFlow Lite**.

---

## ✨ Overview
A real-time computer vision system that detects hand landmarks from live video input and classifies both **static hand gestures** and **dynamic finger movements** with high efficiency.

---

## 🚀 Features
- Real-time hand gesture recognition via webcam  
- Static hand pose classification using keypoints  
- Dynamic finger gesture recognition using motion history  
- On-screen visualization of landmarks, gestures, and FPS  
- Multiple interaction modes for recognition and data logging  

---

## ⚙️ How It Works
- **Hand Landmark Detection**  
  MediaPipe Hands extracts 2D hand keypoints from each video frame.

- **Keypoint Classification**  
  `keypoint_classifier.tflite` classifies static hand gestures from landmark coordinates.

- **Finger Gesture Classification**  
  `point_history_classifier.tflite` analyzes trajectory history to recognize motion-based gestures.

- **Real-Time Processing**  
  Continuous frame processing with FPS calculation for performance monitoring.

---

## 🧠 Application Modes
- **Recognition Mode** – Detects and displays gestures  
- **Keypoint Logging Mode** – Logs hand landmark data  
- **Point History Logging Mode** – Logs movement trajectories  

---

## ⌨️ Controls
| Key | Action |
|---|---|
| `n` | Recognition mode |
| `k` | Keypoint logging mode |
| `h` | Point history logging mode |
| `0–9` | Select gesture label |
| `ESC` | Exit application |

---

## 📊 Data Source
- Hand keypoints and motion history captured using **MediaPipe**

---

## 🛠️ Tech Stack
- Python  
- MediaPipe  
- TensorFlow Lite  
- OpenCV  

---

## 🎯 Use Cases
- Human–Computer Interaction  
- Gesture-based control systems  
- Real-time computer vision applications  

---

