# real-time-object-tracking-meanShift-camShift
🚀 Real-Time Object Tracking using Mean Shift & CamShift

This project demonstrates real-time object tracking using Mean Shift and CamShift algorithms in computer vision.

The system tracks a selected object (football) across video frames using color-based histogram back-projection and adaptive tracking techniques.

🔍 Key Features
🎯 Object tracking using Mean Shift algorithm
🔄 Adaptive tracking with CamShift (scale + rotation handling)
🎨 HSV color histogram-based tracking
📹 Real-time video processing using OpenCV
📊 Comparison between Mean Shift and CamShift performance
🧠 How It Works
Select Region of Interest (ROI) in the first frame
Compute HSV color histogram
Apply back-projection to identify matching regions
Use:
Mean Shift → fixed window tracking
CamShift → dynamic window tracking (size & rotation)
📈 Results
Mean Shift successfully tracks the object but struggles with scale changes
CamShift improves tracking by adapting to object size and orientation

➡️ CamShift provides more robust and accurate tracking in dynamic scenarios

🛠️ Tech Stack
Python 🐍
OpenCV (cv2) 👁️
NumPy
📌 Applications
Surveillance systems
Autonomous vehicles
Gesture recognition
Sports analytics

