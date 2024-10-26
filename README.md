# Video Object Detection with YOLO

This project demonstrates an object detection pipeline using a modified YOLO model to process videos, annotate detected objects, and generate analytical graphs for deeper insights. The repository includes code for detection, annotation, and analysis, providing an end-to-end solution for video-based object recognition.

## 📋 Project Overview

The project takes a video as input, detects various objects using the YOLO (You Only Look Once) model, and outputs:
- A CSV file with detailed detection results.
- An annotated video with bounding boxes around detected objects.
- Analytical graphs for visual insights, including object frequency, detection confidence distribution, and object trends over time.

## ✨ Key Features

- **Real-Time Object Detection**: Efficiently detects multiple objects across video frames.
- **Annotated Output Video**: Shows bounding boxes with labels and confidence scores on detected objects.
- **CSV Export**: Detailed detection data saved in CSV format for each frame.
- **Analytical Graphs**: Visualizes detection insights, including object frequency, confidence distribution, and trends over time.

## 🚀 Model Information

The project utilizes a modified YOLOv8 model pre-trained on COCO datasets, fine-tuned for efficient video processing. YOLO (You Only Look Once) is a fast and accurate object detection model, particularly suited for real-time applications.

## 📂 Repository Structure

- **`VideoObjectDetector` Class**: Handles object detection, video processing, annotation, and analysis.
- **`process_video` Function**: Processes each video frame, applies YOLO for object detection, and stores results.
- **`create_annotated_video` Function**: Generates an annotated video showing detected objects.
- **`analyze_results` Function**: Creates analytical graphs for in-depth insights into the detection process.
- **Output Files**:  
  - `detection_results_[timestamp].csv`: CSV file with frame-by-frame detection data.
  - `annotated_video.mp4`: Annotated video with bounding boxes and labels.

## 🛠 Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/VideoObjectDetection
   cd VideoObjectDetection
