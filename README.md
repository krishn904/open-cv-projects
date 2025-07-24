# 😄 Face, Eyes & Smile Detection using OpenCV 🕵️‍♂️📸

Welcome to my OpenCV project where you can **automatically detect faces, eyes, and smiles** in real-time using your webcam! This is a beginner-friendly project built with the powerful **OpenCV library** and its **Haarcascade classifiers**.

## 🔍 What this project does

This project uses pre-trained Haarcascade models to:
- 👤 Detect **faces**
- 👁️ Detect **eyes**
- 😄 Detect **smiles**

Everything happens in **real-time** using your device’s webcam!

## 📦 Technologies Used

- 🧠 **Python**
- 📸 **OpenCV (cv2)**
- 🧰 **Haarcascade Classifiers** (XML files from OpenCV)

## 🚀 How it works

1. The webcam captures frames.
2. Each frame is scanned using Haarcascade models.
3. Rectangles are drawn around detected:
   - Faces (in blue)
   - Eyes (in green)
   - Smiles (in red)

## 📁 Haarcascade Files Used

- `haarcascade_frontalface_default.xml`
- `haarcascade_eye.xml`
- `haarcascade_smile.xml`

These files are included with OpenCV or can be downloaded from the official [OpenCV GitHub repository](https://github.com/opencv/opencv/tree/master/data/haarcascades).

## 🛠️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name

