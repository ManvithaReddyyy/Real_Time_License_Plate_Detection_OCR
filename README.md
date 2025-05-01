# Real_Time_License_Plate_Detection_OCR
Real-time vehicle license plate detection and recognition system using Python, OpenCV, and EasyOCR - combines classical computer vision with OCR for text extraction.

This project implements a real-time license plate detection and recognition system using Python, OpenCV, and EasyOCR. It captures video from a webcam, detects license plates using Haar Cascade Classifier, enhances the plate image, and extracts text using OCR.

## Features

- Real-time license plate detection from webcam feed
- Image preprocessing for better OCR accuracy (grayscale, sharpening, CLAHE, resizing)
- Text extraction using EasyOCR with confidence scores
- Automatic saving of detected plate images
- Displays bounding boxes and recognized text in real-time

## Technologies Used

- Python
- OpenCV
- EasyOCR
- NumPy
- Matplotlib

## 🔍 How It Works

1. **Webcam Capture** – Captures live video stream from the camera.
2. **License Plate Detection** – Haar Cascade Classifier locates license plates.
3. **Preprocessing** – Enhances detected plate image for better OCR results.
4. **OCR** – EasyOCR reads and extracts alphanumeric characters from the image.
5. **Display** – Outputs recognized plate number with confidence and shows bounding box on the plate.
