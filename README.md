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
Upload `tracked_output.mp4` to **GitHub Releases** and link it here.

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

## 📁 Project Structure
```bash
crowd-tracking-yolo-sort/
├── crowd_detector.ipynb      # Main Google Colab notebook
├── tracker.py                # SORT tracking implementation
├── requirements.txt          # Python dependencies
├── tracked_output.mp4        # Sample output video
├── README.md                 # Project documentation
└── demo/                     # Demo images/videos
