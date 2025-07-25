# DriveAwareAI 🚘💤 - Real-Time Drowsiness Detection System

**DriveAwareAI** is a real-time drowsiness detection system built using computer vision techniques. It monitors a driver’s alertness using facial landmarks and eye movement, and raises an alarm when signs of drowsiness are detected — helping prevent road accidents.

---

## 🧠 Motivation 

According to the **National Highway Traffic Safety Administration**, every year around **100,000** crashes involve drowsy driving — leading to over **1,500 fatalities** and **70,000+ injuries**. Preventive technologies like **DriveAwareAI** can help save lives.

---

## ⚙️ Built With

- [OpenCV](https://opencv.org/) – Real-time video/image processing
- [dlib](http://dlib.net/) – Face & facial landmark detection
- [imutils](https://github.com/jrosebr1/imutils) – Helper functions for OpenCV
- [scikit-learn](https://scikit-learn.org/) – Machine learning support
- [NumPy](https://numpy.org/) – Numerical computation

---

## 🚀 Getting Started

1. Install **Python 3.x**
2. Install [CMake](https://cmake.org/download/) (required for dlib)


## 🧠 Algorithm
Capture video frames

Detect face using dlib

Identify eye landmarks

Compute Eye Aspect Ratio (EAR)

If EAR is below threshold for several frames → trigger buzzer alarm

🧪 Real-World Testing
✅ Detects drowsiness in normal lighting

✅ Works with face positioned left, center, or right

✅ Detects eyes even with glasses

❌ Head tilted >30° reduces detection accuracy

📱 Future Scope
Convert to a mobile app for Android/iOS

Integration with car dashboard systems

Night vision camera support

AI model retraining for improved accuracy

📌 Other Project Name Ideas
In case you want to fork and brand this differently:

Name	Concept
DriveAwareAI	Active alertness detection while driving
AlertVision	Vision + attention monitoring
SomnoSafe	Sleep-aware driver safety
REMDetector	Drowsiness via eye movement detection
WakeGuard	Wakefulness protector
FocusTrack	Tracking driver focus in real-time

📚 References
Facial Features Monitoring – IEEE

Drowsiness Detection using Eye Blink – IEEE

Real Python - Face Detection

PyImageSearch - Facial Landmarks

👤 Author
Vamshi
📍 GitHub: vamshikiranreddy
 for safer roads by Vamshi
