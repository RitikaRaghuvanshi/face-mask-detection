 Face Mask Detection using OpenCV
 Project Overview
This project is a real-time Face Mask Detection system built using **Python and OpenCV**.  
It detects faces through a webcam and determines whether a person is wearing a mask or not.

If no mask is detected, the system triggers a **beep alert**.

---

  Features
- Real-time face detection
- Mask / No Mask classification (basic logic)
- Visual indicators:
  - 🟢 Green → Mask
  - 🔴 Red → No Mask
- 🔊 Beep alert for safety warning
- Lightweight (no TensorFlow required)

---

Technologies Used
- Python
- OpenCV
- NumPy
- Winsound (for alert)

---

 Project Structure
 face-mask-detection/
│
├── face_mask_opencv.py # Main script
├── README.md # Project documentation
└── requirements.txt # Dependencies (optional)

---

## ⚙️ Installation

### 1. Clone or download project

### 2. Install dependencies
pip install opencv-python numpy
python face_mask_opencv.py

How It Works
Captures video using webcam
Detects faces using Haar Cascade
Extracts lower half of face
Uses grayscale + thresholding
Classifies:
Dark region → Mask
Light region → No Mask

Limitations
Not highly accurate (no AI model used)
Works best with dark masks
Lighting affects performance

Future Improvements
Use Deep Learning (TensorFlow/Keras)
Improve accuracy for all mask types
Add GUI interface
Deploy as web/mobile app

Learning Outcomes
Learned OpenCV basics
Real-time video processing
Debugging camera issues
Optimization techniques
Author
Your Name : Ritika Raghuvanshi



