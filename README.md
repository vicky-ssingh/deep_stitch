# Deep Stitch Image Processing Lab

## 📌 Overview
This lab demonstrates an image stitching pipeline using computer vision techniques. The goal is to combine multiple overlapping images into a single panoramic image.

## 🎯 Objectives
- Understand feature detection and matching
- Apply image transformation techniques
- Perform image stitching using Python
- Visualize results effectively

## 🛠️ Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib

## 📂 Project Structure
```
task_2_deep_stitch.ipynb   # Main notebook file
images/                    # Folder containing input images
output/                    # Folder for stitched output
```

## 📸 Required Files
You need the following images:
- image1.jpg
- image2.jpg
(Ensure both images have overlapping regions for stitching)

## ⚙️ Steps Performed
1. Import required libraries
2. Load input images
3. Detect keypoints using feature detectors
4. Match features between images
5. Compute homography matrix
6. Warp and stitch images
7. Display final stitched output

## ▶️ How to Run
1. Install dependencies:
```
pip install opencv-python numpy matplotlib
```

2. Open the notebook:
```
jupyter notebook task_2_deep_stitch.ipynb
```

3. Run all cells step by step

## 📊 Output
- Displays matched keypoints
- Shows final stitched panoramic image

## ⚠️ Notes
- Use high-quality images for better results
- Ensure sufficient overlap between images
- Adjust parameters if stitching fails

## 👨‍💻 Author
Vicky Singh

