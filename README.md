# NextGen-Traffic-Surveillance-and-Control

## Project Overview

An AI-based traffic surveillance system that uses real-time object detection to monitor and analyze traffic flow. It aims to support smart city infrastructure by detecting vehicles and managing traffic effectively.

## Goal

- Detect vehicles from traffic footage using YOLO
- Simulate traffic behavior
- Analyze and optimize traffic flow

## Model Used

- YOLO (You Only Look Once) for real-time object detection

## Technologies

- Python
- Darkflow (YOLO with TensorFlow)
- NumPy
- Matplotlib

## Project Structure
```
├── cfg/                   # YOLO config files
├── darkflow/              # Darkflow object detection code
├── flow/                  # Data flow and utility scripts
├── images/                # Input images
├── output_images/         # Output with detections
├── test_images/           # Test inputs
├── vehicle_detection.py   # Vehicle detection script
├── simulation.py          # Traffic simulation script
├── requirements.txt       # Python dependencies
```

## How to Run

### 1. Install Dependencies
```
pip install -r requirements.txt
```

### 2. Run Vehicle Detection
```
python vehicle_detection.py
```

### 3. Run Traffic Simulation
```
python simulation.py
```

## Input/Output Example
Input: Traffic image or video  
Output:  
- Detected vehicles highlighted in image  
- Vehicle count and other traffic stats  

## Dataset

Sample images for testing and simulations are in:
- `images/`
- `test_images/`
