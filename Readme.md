# MediaPipe Computer Vision Projects 

This repository contains a collection of real-time computer vision applications using **MediaPipe** and **OpenCV** in Python. These projects demonstrate various capabilities such as hand tracking, face mesh, object detection, 3D bounding boxes, pose estimation, and more.

## 🔍 Overview

Each Python script is a self-contained demo showing how to leverage MediaPipe's powerful models for real-time inference. These can be used for prototyping AR applications, gesture control systems, fitness tracking, and more.

---

## 📁 Project Modules

### ✅ 1. 3D Object Detection
- `3D Object Detection (3D Bounding Boxes) with MediaPipe Objectron.py`  
- `3D Object Detection from Video.py`  
**Features:** Detects and visualizes 3D bounding boxes (e.g., cups) in images and videos.

---

### ✅ 2. Face and Hand Landmark Detection
- `Face and Hand Landmarks Detection using Python – Mediapipe, OpenCV.py`  
**Features:** Uses the holistic model to detect full facial and both hand landmarks simultaneously in real time.

---

### ✅ 3. Hand Tracking
- `Hand landmarks detection using MediaPipe.py`  
- `Instant Motion Tracking with MediaPipe.py`  
**Features:** Tracks hand landmarks and movements using webcam input.

---

### ✅ 4. 3D Face Transformations
- `MediaPipe 3D Face Transform Code 1.py` – Basic face mesh detection  
- `MediaPipe 3D Face Transform Code 2.py` – Scales and transforms 3D face landmarks  
- `MediaPipe 3D Face Transform Code 3.py` – Replaces face region with another face image  
- `MediaPipe 3D Face Transform Code 4.py` – Changes clothing color using pose and color segmentation

---

### ✅ 5. Face Detection
- `Object Detection with Web Cam using MediaPipe.py`  
**Features:** Detects faces using MediaPipe’s lightweight face detection module.

---

# Save the README content to a file named README.md

readme_content = """
# 🎯 Real-Time Face & Pose Detection with MediaPipe

This repository features **three Python projects** that demonstrate real-time and static image-based **face and human pose detection** using **[Google's MediaPipe](https://mediapipe.dev/)** and **OpenCV**. These scripts show how to perform:

- Real-time face detection via webcam
- Full-body pose tracking using BlazePose in real-time
- Static image pose detection with segmentation


### ✅ 5. `Object Detection with Web Cam using MediaPipe.py`

**Purpose**: Real-time **face detection** using your computer's webcam.

**Key Features**:
- Utilizes `mediapipe.solutions.face_detection` for lightweight detection.
- Annotates faces using MediaPipe’s built-in drawing utilities.
- Displays the feed with detected faces in a mirrored (selfie-view) display.
- Exits the program when `Esc` is pressed.

**How It Works**:
1. Captures video using OpenCV.
2. Converts frames from BGR → RGB.
3. Detects faces with MediaPipe.
4. Draws detections and flips the image for display.
5. Runs in a loop until `Esc` is pressed.

---

### ✅ 6. `On-device, Real-time Body Pose Tracking with MediaPipe BlazePose.py`

**Purpose**: Track full-body pose landmarks in **real-time** using BlazePose.

**Key Features**:
- Uses `mediapipe.solutions.pose` for upper/lower body tracking.
- Detects and connects 33 pose landmarks.
- Continuously renders landmarks on live webcam frames.
- Exits the program when the `q` key is pressed.

**How It Works**:
1. Initializes BlazePose with detection and tracking confidence.
2. Captures and flips webcam input.
3. Processes each frame for pose estimation.
4. Draws landmarks using MediaPipe’s connections.
5. Displays results in real-time.

---

### ✅ 7. `Pose landmark detection using MediaPipe.py`

**Purpose**: Detect pose landmarks on a **static image** and visualize the result.

**Key Features**:
- Loads and processes a static image with MediaPipe Pose.
- Enables segmentation and uses high model complexity for detailed results.
- Displays annotated results using `matplotlib`.

**How It Works**:
1. Loads an image from a specified path (you need to update the path).
2. Converts the image to RGB format.
3. Processes the image to detect pose landmarks.
4. Draws landmarks and connections with custom styling.
5. Displays the annotated image using Matplotlib.

---

## 🔧 Installation

Install the required packages:

```bash
pip install opencv-python mediapipe matplotlib numpy


## 🧰 Requirements

Install the required Python packages:

```bash
pip install opencv-python mediapipe numpy matplotlib
