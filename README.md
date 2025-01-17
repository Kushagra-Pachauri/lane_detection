# lane_detection

# 🚗 Lane Detection & Marking System 🚧  

An advanced computer vision project that detects and marks lanes in road videos. This system leverages **OpenCV**, **MoviePy**, and other powerful tools to provide high accuracy and real-time lane visualization. Whether for autonomous driving research or traffic analysis, this project is designed to deliver reliable and efficient results.  

---

## 🌟 Features  

- **Lane Detection**: Uses edge detection and the Hough transform to identify straight and curved lanes.  
- **Lane Marking**: Overlays detected lanes directly onto video footage for better visualization.  
- **Real-Time Processing**: Processes video files efficiently, making it suitable for live applications.  
- **Camera Calibration**: Ensures accurate lane detection by correcting camera distortions.  
- **Video Preprocessing**: Enhances input videos for optimized performance.  

---

## 📋 Prerequisites  

To set up and run the project, ensure you have the following:  

- **Python** (3.7 or later)  
- Required Python libraries (installed via `requirements.txt`)  
- A video file for processing  

---

## 🛠️ Installation  

Follow these steps to set up and run the project locally:  

### 1. Clone the Repository  
```bash  
git clone https://github.com/Kushagra-Pachauri/lane-detection-marking.git  
cd lane-detection-marking 
``` 

### 2. Install dependencies
You'll need Python and some required libraries:
```bash
pip install -r requirements.txt
```

### 3. Prepare your video footage
- Place your video file in the `videos/` folder or modify the script to specify the path to your video file.

### 4. Run the lane detection and marking
Run the script to detect and mark lanes on your video.
```bash
python lane_detection.py --input_video path_to_video.mp4
```
