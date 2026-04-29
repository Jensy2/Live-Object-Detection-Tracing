# Live-Object-Detection-Tracing
🎥 Live Object Detection App

This is a simple Streamlit app that uses YOLOv8 to detect and track objects in real-time using your webcam.

🚀 Features
Real-time object detection
Object tracking
Adjustable confidence level
Alert for specific objects
Option to save detected frames
📦 Installation

Install the required packages:

pip install streamlit streamlit-webrtc ultralytics opencv-python av torch torchvision numpy
▶️ Run the App
streamlit run app.py

Then open the link in your browser and allow camera access.

⚙️ Settings
Confidence Threshold – controls detection accuracy
Save Frames – saves detected images
Alert Object – shows alert when object is detected
🧠 How It Works
The app uses YOLOv8 to detect objects from the webcam
Detected objects are tracked and counted
Alerts appear if a chosen object is found
📁 Output

Saved images will appear as:

frame_<timestamp>.jpg
📌 Notes
Requires a webcam
Works best on a fast computer
