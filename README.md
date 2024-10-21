# Football Analysis Project

## Introduction
The goal of this project is to detect and track players, referees, and footballs in a video using YOLO, a highly efficient AI object detection model. The model is trained to enhance its performance. Players are assigned to teams based on the colors of their t-shirts by applying K-means for pixel segmentation and clustering. This information is used to calculate each team's ball possession percentage during a match. Optical flow is utilized to measure camera movement between frames, ensuring accurate player movement tracking. Perspective transformation is implemented to account for the scene's depth and perspective, allowing player movement to be measured in meters rather than pixels. Additionally, the project calculates the speed of players and the distance they cover. This approach covers multiple key concepts in machine learning and addresses practical, real-world challenges, making it applicable for both beginners and experienced engineers.

![Screenshot](output_videos/screenshot.png)

## Modules Used
The following modules are used in this project:
- YOLO: AI object detection model
- Kmeans: Pixel segmentation and clustering to detect t-shirt color
- Optical Flow: Measure camera movement
- Perspective Transformation: Represent scene depth and perspective
- Speed and distance calculation per player

## Trained Models
- [Trained Yolo v5](https://drive.google.com/file/d/1DC2kCygbBWUKheQ_9cFziCsYVSRw6axK/view?usp=sharing)

## Sample video
-  [Sample input video](https://drive.google.com/file/d/1t6agoqggZKx6thamUuPAIdN_1zR9v9S_/view?usp=sharing)

## Requirements
To run this project, you need to have the following requirements installed:
- Python 3.x
- ultralytics
- supervision
- OpenCV
- NumPy
- Matplotlib
- Pandas
