# CV-Project

# Keypoint Detection and Matching in Images (SIFT, RANSAC, Harris)

## 📌 Overview
This project demonstrates three classic computer vision techniques using OpenCV in Python:
- SIFT for feature detection and matching
- RANSAC for removing outliers and fitting homography
- Harris Corner Detection for identifying corner features

## 🖼 Input Image
The same landscape image was used for all operations.

## 📁 Folder Structure
- `images/` - Input image
- `results/` - Output images
- Python files for each algorithm

## 🔍 Techniques

### 1. SIFT Keypoint Matching
Detects and matches keypoints between two identical images.
![SIFT Result](results/sift_result.jpg)

### 2. RANSAC Homography Filtering
Filters out incorrect matches using RANSAC and displays inliers.
![RANSAC Result](results/ransac_result.jpg)

### 3. Harris Corner Detection
Identifies corners in the grayscale image.
![Harris Corners](results/harris_corners.jpg)

## 💻 Dependencies
- Python 3
- OpenCV (`pip install opencv-python`)
- NumPy

## 👨‍💻 Author
[Your Name]


