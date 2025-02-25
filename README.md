# Assignment01_DigitalImageProcessingLAB_CSE438
Digital Image Processing LAB taken by Audity Ghosh maam, 8A, CSE 50 Batch

# 🖼️ Digital Image Processing Lab Report  

## 📌 Introduction  
This report provides an overview of the Digital Image Processing Lab, detailing the objectives, methodologies, and results of the exercises conducted. The focus is on implementing fundamental image processing techniques using **Python** and **OpenCV**.  

## 👩‍🏫 Faculty  
**Audity Ghosh**  
Lecturer, Department of Computer Science & Engineering  
University of Information Technology and Sciences (UITS)  

## 👨‍🎓 Submitted by  
**Maheru Tabassum Ohana**  
- **ID:** 2125051015  
- **Section:** 8A  
- **Batch:** 50  

## 📚 Course Details  
- **Course Code:** CSE 438  
- **Course Title:** Digital Image Processing Lab  
- **Section:** 8A (50th Batch)  
- **Date:** 5 February, 2025  

---

## 📝 Assignment 1: Image Region Extraction and HSV Conversion  

### 🎯 Objectives  
- Understanding basic image manipulation techniques in Python.  
- Extracting a specific region from an image.  
- Converting an image to HSV color space and analyzing its components.  

### 🔧 Lab Tasks  

#### ✅ Task 1: Extracting a 100×100 Region from the Center of an Image  
- Load an image from a given URL.  
- Determine the center coordinates of the image.  
- Extract a **100×100** pixel region from the center.  
- Display both the original and cropped image for comparison.  

#### ✅ Task 2: Converting an Image to HSV and Visualizing Components  
- Convert the input image from **RGB to HSV** color space.  
- Extract and visualize the **Hue, Saturation, and Value** components individually in grayscale.  
- Analyze how HSV representation differs from RGB.  

### 🛠️ Methodology  

#### 🚀 Tools and Libraries Used  
- **Python 3.x**  
- **OpenCV (cv2)**  
- **NumPy**  
- **Matplotlib**  

#### 🔄 Implementation  
- **Image Loading:** The image is loaded from a URL using OpenCV.  
- **Region Extraction:** Image slicing is used to extract a **100×100 pixel** region from the center.  
- **HSV Conversion:** The `cv2.cvtColor()` function is used to transform the RGB image into HSV format.  
- **Visualization:** The extracted components are displayed using **Matplotlib**.  

### 📊 Results  
- The extracted image region and HSV components were successfully visualized, demonstrating:  
  ✅ The ability to manipulate image regions programmatically.  
  ✅ How **HSV color space** represents image information differently than **RGB**.  

