# 👤 Face Detection using OpenCV (Haar Cascade)

A real-time face detection system using OpenCV and Haar Cascade classifiers. This project captures video from your webcam, detects human faces, and draws bounding boxes around them. You can capture up to 30 face images per session, ideal for dataset creation or training models.

---

## 🚀 Features

- 🎥 Real-time video capture via webcam  
- 🤖 Face detection using Haar Cascade Classifier  
- 🧠 Grayscale conversion for efficient processing  
- 🟩 Green bounding boxes around faces  
- 📝 On-screen messages: “Person detected” / “No person detected”  
- 💾 Captures up to 30 frames for dataset generation  

---

## 🛠️ Technologies Used

- **Python 3**
- **OpenCV (cv2)**
- **Haar Cascade XML**
- **OS Module** (for working with directories)

---

## 📂 Project Structure

face-detection/
├── haar_face_detector.py # Main Python script
├── haarcascade_frontalface_default.xml # Haar cascade classifier
└── README.md # This file



---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Arooma4/Face-Detection-.git
cd face-detection
2. Install Dependencies

pip install opencv-python
3. Download Haar Cascade File
If not already present, download haarcascade_frontalface_default.xml from OpenCV’s GitHub:
🔗 https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml

Place it in the same directory as your Python script.

▶️ Run the Script

python haar_face_detector.py
