# Optical Character Recognition (OCR) using CNN and Computer Vision

This project implements an end-to-end OCR system capable of detecting and recognizing characters from raw images using image processing and deep learning techniques. It combines classical computer vision for segmentation and a Convolutional Neural Network (CNN) for character classification.

##  Project Overview

The goal of this project is to recognize characters from images by first detecting and segmenting each character and then classifying them using a trained CNN model. This approach simulates a basic OCR pipeline and can be extended to a variety of character-based recognition tasks.

### Pipeline Summary:
1. **Preprocessing:** Convert image to grayscale, apply thresholding, and perform morphological operations.
2. **Segmentation:** Detect contours to locate and extract individual characters.
3. **Classification:** Use a CNN to recognize each segmented character.
4. **Postprocessing:** Sort characters by position and reconstruct the final string.


## 🛠 Technologies Used

- **Python**
- **OpenCV** – Image processing (thresholding, contours, etc.)
- **TensorFlow/Keras** – CNN model for character classification
- **NumPy** – Array manipulation
- **Matplotlib** – Visualization
