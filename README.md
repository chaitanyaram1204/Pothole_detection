# Pothole Detection System

## Overview
This project aims to detect water-filled potholes using computer vision techniques and the YOLO (You Only Look Once) model. The system processes both video streams from a camera and individual images, providing real-time detection of potholes.

## Dependencies
- OpenCV
- geocoder

## Files Included
1. **camera_video.py**: Python script for real-time pothole detection using a camera feed.
2. **image.py**: Python script for pothole detection in individual images.
3. **obj.names**: File containing class names, including "pothole".
4. **process.py**: Additional script for processing the detected potholes.
5. **result.avi**: Video file with the detected potholes highlighted.
6. **test2.mp4**: Sample video file for testing the system.
7. **trained.ipynb**: Jupyter Notebook containing the training process for the YOLO model.
8. **yolov4_tiny.cfg**: Configuration file for the YOLOv4 Tiny model.
9. **yolov4_tiny.weights**: Pre-trained weights for the YOLOv4 Tiny model.
10. **yolov4tinytrain.ipynb**: Jupyter Notebook documenting the training process for YOLOv4 Tiny.

## Usage
### Real-time Detection (camera_video.py)
1. Ensure the required dependencies are installed.
2. Run `camera_video.py` to initiate real-time pothole detection from a camera feed.
3. Press 'q' to exit the application.

### Image Detection (image.py)
1. Ensure the required dependencies are installed.
2. Update the image file path in `image.py`.
3. Run `image.py` to detect potholes in the specified image.

## Important Notes
- The system utilizes the YOLOv8 Tiny model, and its weights and configuration files are provided.
- Results, including detected pothole images and their coordinates, are stored in the 'pothole_coordinates' directory.

Feel free to explore and adapt the code based on your specific requirements!

