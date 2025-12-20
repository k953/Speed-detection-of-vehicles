# 🚗 Vehicle Speed Detection using Computer Vision

This project implements a **vehicle speed detection system** using classical computer vision techniques.  
It processes highway traffic videos, tracks vehicles across frames, and estimates their speed based on distance traveled over time.

---

## 📌 Project Overview

Vehicle speed estimation is an important component of modern **intelligent traffic monitoring systems**.  
This project demonstrates how speed can be calculated from video streams using **object tracking and motion analysis** without relying on additional hardware sensors.

---

## 🧠 Methodology

The system follows a **tracking-by-detection** approach:

1. Video is read frame-by-frame using OpenCV
2. Vehicles are detected in each frame
3. Each vehicle is assigned a unique ID using a custom tracker
4. Vehicle movement is tracked across frames
5. Speed is calculated using distance traveled and time elapsed

---

## 🔁 Processing Pipeline



<img width="653" height="430" alt="image" src="https://github.com/user-attachments/assets/a1a1081d-2742-4fbe-9954-921a7adec495" />



<img width="968" height="256" alt="image" src="https://github.com/user-attachments/assets/e257a46c-96e0-4aeb-bb03-89cefdbfe391" />



---

## ⚙️ Technologies Used

- **Python**
- **OpenCV (cv2)**
- **Computer Vision**
- **Object Tracking**
- **Jupyter Notebook**

---

## 📐 Speed Estimation Logic

Vehicle speed is calculated using the formula:



Speed = Distance / Time


Where:
- Distance is computed from pixel displacement between frames
- Pixel distance is converted to real-world distance using a scale factor
- Time is derived from frame count and video FPS

---

## ▶️ How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/k953/Speed-detection-of-vehicles.git


Open Jupyter Notebook:

jupyter notebook


Run:

speed_estimate.ipynb

📊 Applications

Traffic speed monitoring

Highway surveillance systems

Smart city traffic analytics

Speed violation detection

Intelligent transportation systems (ITS)

🚀 Future Enhancements

Integration with YOLO for robust vehicle detection

Multi-lane speed estimation

Real-time CCTV camera support

License plate recognition (ANPR integration)

Speed violation alerts
