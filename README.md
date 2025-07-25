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

## System Design

<img width="619" height="525" alt="image" src="https://github.com/user-attachments/assets/0d430665-1bf9-4c0c-a756-1564ab6edb2c" />



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

### 🚗 Reference Inspiration: Bosch Driver Drowsiness Detection System

![Bosch Interior Monitoring](images/bosch_interior.png)

Bosch deploys camera and steering-performance cues to accurately detect driver fatigue. It monitors facial expressions, gaze, steering angle variance, trip duration, and turn signal use to generate timely alerts.:contentReference[oaicite:9]{index=9}


## result Refrence images from the web
Testing and Results in Real-World Scenario:
The tests were conducted in various conditions including:

Different lighting conditions.
Drivers posture and position of the automobile drivers face.
Drivers with spectacles.
Test case 1: When there is ambient light
<img width="795" height="637" alt="image" src="https://github.com/user-attachments/assets/2a124f51-93ff-4234-a098-e6e60d4f5598" />


Result: As shown above, when there is ambient amount of light, the automobile driver's face and eyes are successfully detected.

Test case 2: Position of the automobile drivers face

Centre Positioned
<img width="799" height="640" alt="image" src="https://github.com/user-attachments/assets/dcc22558-62f5-47bd-baa3-68a7bae69ef6" />



Result: As shown in above, When the automobile driver's face is positioned at the Centre, the face, eyes, eye blinks, and drowsiness was successfully detected.

Right Positioned
<img width="791" height="632" alt="image" src="https://github.com/user-attachments/assets/d7c799aa-8fe1-4574-85ee-b51fde836783" />



Result: As shown in above, When the automobile driver's face is positioned at the Right, the face, eyes, eye blinks, and drowsiness was successfully detected.

Left Positioned
<img width="785" height="641" alt="image" src="https://github.com/user-attachments/assets/35628486-1f9a-49c5-aeef-038d7e8d34d2" />



Result: As shown in screen snapshot in above, when the automobile driver's face is positioned at the Left, the face, eyes, eye blinks, and drowsiness was successfully detected.

Test case 3: When the automobile driver is wearing spectacles
<img width="796" height="635" alt="image" src="https://github.com/user-attachments/assets/dd79afb3-e6e2-44cc-8162-42462851a843" />




Result: As shown in screen snapshot in above, When the automobile driver is wearing spectacles, the face, eyes, eye blinks, and drowsiness was successfully detected.

Test case 4: When the automobile driver’s head s tilted
<img width="791" height="629" alt="image" src="https://github.com/user-attachments/assets/e49fa004-c2c7-42d5-a89b-0f17539c94d2" />



Result: As shown in screen snapshot in above, when the automobile driver's face is tilted for more than 30 degrees from vertical plane, it was observed that the detection of face and eyes failed.

The system was extensively tested even in real world scenarios, this was achieved by placing the camera on the visor of the car, focusing on the automobile driver. It was found that the system gave positive output unless there was any direct light falling on the camera.

Future Scope
Smart phone application: It can be implemented as a smart phone application, which can be installed on smart phones. And the automobile driver can start the application after placing it at a position where the camera is focused on the driver.


## 📚 References
Facial Features Monitoring – IEEE

Drowsiness Detection using Eye Blink – IEEE

Real Python - Face Detection

PyImageSearch - Facial Landmarks

## 👤 Author
Vamshi
📍 GitHub: vamshikiranreddy
 for safer roads by Vamshi
