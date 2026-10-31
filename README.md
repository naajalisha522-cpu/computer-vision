# YOLO Human Pose Estimation

## Project Description
This project uses YOLO26 Pose Estimation to detect human body keypoints from an input video. It identifies important body joints such as shoulders, elbows, wrists, hips, knees, and ankles and connects them to create a human skeleton.

The detected skeleton is displayed over the original video, helping visualize human posture and body movements.

## Technologies Used
- Python
- YOLO26 Pose (Ultralytics)
- OpenCV
- NumPy
- Google Colab

## Features
- Human pose detection from video.
- Detection of body keypoints.
- Skeleton visualization.
- Displays pose estimation on the original video.
- Generates an output video in MP4 format.

## Requirements
Install the required libraries:

pip install ultralytics opencv-python numpy

## How to Run
1. Open the project in Google Colab.
2. Install the required libraries.
3. Upload your input video.
4. Load the YOLO26 Pose model.
5. Run the Python code to process the video.
6. Download the generated output video.

## Input
An MP4 video containing one or more people.

## Output
An MP4 video showing the original video with detected human body keypoints and skeleton connections.

## Applications
- Human activity recognition.
- Sports movement analysis.
- Fitness and posture monitoring.
- Human movement analysis.

## Author
[Your Name]
