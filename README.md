# ✋🔊 Hand Gesture Controlled Volume Controller

A Python project using **OpenCV**, **MediaPipe**, and **pycaw** to control system volume with hand gestures via a webcam. It detects the distance between the thumb and index finger and maps that distance to the system volume range.

## 📸 Demo

Control your system's volume in real-time by simply adjusting the gap between your thumb and index finger!

![Demo GIF or Screenshot Placeholder]
![Screenshot (6)](https://github.com/user-attachments/assets/d9cfc280-a9be-45d9-b068-5f1df6fd82be)


## 🧠 How It Works

- Uses **MediaPipe** to detect hand landmarks.
- Measures the Euclidean distance between the **tip of the thumb and index finger**.
- Maps the measured distance to the **system volume range** using `pycaw`.
- Real-time feedback with:
  - A volume bar
  - Volume percentage display
  - Circles and a connecting line on detected fingertips


## 🛠️ Tech Stack

- **Python**
- **OpenCV** – for real-time video capture and display
- **MediaPipe** – for hand tracking
- **pycaw** – for accessing and controlling Windows system audio
- **NumPy** – for numerical interpolation
- **math.hypot** – for calculating distance
