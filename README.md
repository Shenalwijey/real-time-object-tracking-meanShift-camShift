# real-time-object-tracking-meanShift-camShift
# 🚀 Real-Time Object Tracking using Mean Shift & CamShift


---

## 📌 Overview

This project demonstrates **real-time object tracking** using **Mean Shift** and **CamShift** algorithms implemented with **OpenCV in Python**.

The system tracks a selected object (football) across video frames using **color-based histogram back-projection** and adaptive tracking techniques.

---

## 🎯 Features

- 🔵 Object tracking using **Mean Shift algorithm**
- 🟢 Adaptive tracking using **CamShift (scale & rotation handling)**
- 🎨 HSV color histogram-based tracking
- 📹 Real-time video processing with OpenCV
- 📊 Performance comparison between Mean Shift & CamShift

---

## 🧠 How It Works

1. Select the **Region of Interest (ROI)** in the first frame  
2. Compute the **HSV color histogram** of the object  
3. Apply **back-projection** to identify matching pixels  
4. Use:
   - 📌 Mean Shift → Fixed tracking window  
   - 📌 CamShift → Dynamic tracking window (resizes & rotates)  
5. Track object frame-by-frame  

---

## 📈 Results & Insights

- ✅ Mean Shift successfully tracks the object  
- ⚠️ Struggles with scale and rotation changes  
- ✅ CamShift adapts to object size and orientation  
- 🚀 Provides more **accurate and robust tracking**

---

## 🛠️ Tech Stack

- **Python**
- **OpenCV (cv2)**
- **NumPy**

---


## 🚀 Applications

- 🛡️ Surveillance systems  
- 🚗 Autonomous vehicles  
- ✋ Gesture recognition  
- ⚽ Sports analytics  

---

## 📚 Key Concepts

- Mean Shift (Mode-seeking algorithm)
- CamShift (Adaptive Mean Shift)
- Histogram Back Projection
- Object Tracking in Computer Vision

---

## 🙌 Acknowledgements

- OpenCV Documentation  
- Research by Comaniciu & Meer (Mean Shift Algorithm)

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

---


