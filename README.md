# Image Enhancement Assignment

This repository contains my assignment for **Image Processing (PCD)** on **Image Enhancement**.  
The project demonstrates various enhancement techniques such as blurring, brightness/contrast adjustment, and edge-preserving filters using **Python + OpenCV**.

## Features Implemented

### Blur Techniques
1. **Box Blur (Mean Filter)** – Simple averaging of neighbors.  
2. **Gaussian Blur** – Weighted averaging with Gaussian kernel.  
3. **Median Blur** – Replaces pixel with neighborhood median, good for salt-and-pepper noise.  
4. **Bilateral Filter** – Smooths flat areas but keeps edges sharp.  
5. **Motion Blur** – Simulates directional movement blur.  

### Intensity Transformations
- **Brighten** – Increases pixel intensity to lighten the image.  
- **Darken** – Scales down intensities to make the image darker.  
- **Lower Contrast** – Compresses the intensity range to reduce contrast.  

## References
[1] Image Blurring Example with OpenCV in Python - https://youtu.be/0Y9G-mYzffk?si=DivkdBzhjeHOFT6q
[2] https://www.geeksforgeeks.org/python/python-intensity-transformation-operations-on-images/
[3] https://www.kaggle.com/code/bhavinmoriya/histograms-intensity-transformations-opencv#Toy-Example
