# DocScanner
A Computer Vision project that automatically detects a document in an image, applies perspective transformation, and generates a clean scanned version similar to a mobile scanner app.

## 🚀 Features

- Detects document boundaries automatically
- Finds the largest rectangular contour
- Applies Perspective Transform
- Converts image into a top-down scanned view
- Supports images captured from different angles
- Built using OpenCV and NumPy

## 🛠️ Tech Stack

- Python
- OpenCV
- NumPy
- Matplotlib

## 📌 Workflow

1. Load image
2. Resize image for processing
3. Convert to grayscale
4. Apply Gaussian Blur
5. Perform Edge Detection using Canny
6. Detect contours
7. Identify document boundary
8. Apply Four Point Perspective Transform
9. Generate scanned output

## 📸 Sample Results

<img width="1926" height="495" alt="docScannerOutput" src="https://github.com/user-attachments/assets/e099d439-2747-4be3-be52-87aa11061538" />

## 📈 Future Improvements
- Real-time webcam scanning
- Adaptive thresholding
- OCR integration using Tesseract
