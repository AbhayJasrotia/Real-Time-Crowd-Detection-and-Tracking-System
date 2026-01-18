# 🚶‍♂️ Real-Time Crowd Detection & Tracking System  
### YOLOv8 + SORT | Computer Vision Major Project

## 📌 Overview
This project implements a **real-time Crowd Detection and Tracking System** using **YOLOv8** for person detection and **SORT (Simple Online Realtime Tracking)** for multi-object tracking.

The system detects individuals in crowded scenes, assigns **unique IDs**, tracks their movement across frames, and displays **real-time crowd count** per frame.

🎓 **Developed as a Major Project for B.Tech Computer Science Engineering (CDAC DASSD)**  
📍 Domain: Computer Vision, Deep Learning, Real-Time Systems

---

## 🎬 Demo

🎥 **Watch Demo Video**  
https://youtu.be/AoZ7w4NXbjc?si=bBhFuGt3-G-AUl-y

### 📊 Sample Results
- ✅ Frames Processed: **92**
- ✅ Average People per Frame: **16.4**
- ✅ Total Unique IDs Tracked: **39**
- ✅ Processing Speed: **30+ FPS (GPU)** | **8–10 FPS (CPU)**
- ✅ Detection Confidence: **~87%**

---

## 🧠 Key Features
- ✅ Real-time person detection using **YOLOv8**
- ✅ Multi-object tracking using **SORT (Kalman Filter + Hungarian Algorithm)**
- ✅ Persistent **unique ID assignment**
- ✅ Dynamic **people count overlay**
- ✅ Bounding box visualization with confidence scores
- ✅ Video input/output using **OpenCV**
- ✅ GPU acceleration (also works on CPU)
- ✅ Modular and easy-to-extend codebase

---

**##🚀 How It Works**
Input Video
    ↓
YOLOv8 Detection (Person Class)
    ↓
Bounding Boxes + Confidence
    ↓
SORT Tracking (Kalman + IoU Matching)
    ↓
Tracked Objects with Unique IDs
    ↓
Annotated Output Video

### 🎯 Tracking Performance

| Metric           | Value               | Notes                  |
|------------------|---------------------|------------------------|
| Estimated MOTA   | 65–70%              | SORT baseline          |
| IDF1 Score       | 60–65%              | No appearance features |
| ID Switches      | ~2 per person       | Expected               |
| Optimal Density  | 10–100 people/frame | Best performance range |

## 👨‍💻 Author

**Your Name**  
B.Tech Computer Science Engineering | CDAC DASSD  
📧 abhayjasrotia@gmail.com  

🔗 LinkedIn: https://www.linkedin.com/in/abhay-jasrotia-907487236/ 
