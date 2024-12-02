
# Nudity Detection App

The **Nudity Detection App** is a tool designed to analyze images and videos for nudity detection. Built with **Streamlit** and **OpenCV**, it offers two key features:
- **Image Nudity Detection**: Upload an image to detect nudity, visualize the detection, and blur nudity if found.
- **Video Nudity Detection**: Upload a video to scan for nudity frame-by-frame.

## Features
1. Detect nudity in images and videos.
2. Provide visualized results for detection.
3. Automatically blur detected nude areas for privacy.

## Requirements
- Python 3.7+
- ONNX model file (`best.onnx`) placed in the project directory.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/AdiKhanOfficial/nudity-detection-app.git
   cd nudity-detection-app
   ```

2. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

## File Descriptions
- **`app.py`**: Main app file to toggle between image and video detection.
- **`nude_image_app.py`**: Handles image nudity detection logic.
- **`nude_video_app.py`**: Handles video nudity detection logic.
- **`NudeDetector.py`**: Core detection logic using an ONNX model.
- **`best.onnx`**: Pre-trained ONNX model (not included, must be added manually).

## Screenshots
1. **Image Detection Interface**  
   Detect nudity in images with visualized results.

2. **Video Detection Interface**  
   Analyze video frames for nudity detection.

## Contact
For further queries or assistance, contact:

**Adil Khan**  
- [Website](https://adikhanofficial.com)  
- [GitHub](https://github.com/AdiKhanOfficial)  
- [WhatsApp](https://wa.me/+923065305216)
