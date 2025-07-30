# Digital-Whiteboard-Reader

Digital Whiteboard Reader uses OpenCV and OCR to preprocess and extract text respectively.

This project has been made to work only in google colab.

## Project Summary

The **Digital Whiteboard Reader** is a computer vision-based system designed to read, process, and digitize the content written on whiteboards. This system leverages image processing techniques to identify and extract handwritten text or drawings from an image of a whiteboard, with potential applications in education, presentations, and remote collaboration.

By automating the task of reading whiteboard content, the project offers a way to save, archive, or enhance legibility for better digital usage. It can serve as a foundation for more advanced applications like real-time lecture transcription, handwriting recognition, or content streaming.

---

## Objectives

- Capture and preprocess whiteboard images
- Apply computer vision techniques to enhance image clarity
- Extract and isolate handwritten content
- Prepare images for potential downstream tasks like OCR or digitization

---

## Tools & Technologies

- **Programming Language**: Python
- **Libraries Used**:
  - `OpenCV` – for image processing (blurring, thresholding, contour detection)
  - `NumPy` – for array and matrix operations
  - `Matplotlib` – for image visualization
  - `Pillow` (PIL) – for image handling (if used)
- **Development Environment**: Jupyter Notebook

---

## Features

- Automatic whiteboard content enhancement
- Conversion to grayscale and thresholding
- Noise removal and edge detection
- Contour identification for text region isolation
- Easy integration with OCR tools (like Tesseract) for text extraction (optional extension)

---

## Sample Workflow

1. **Input**: An image of a whiteboard with handwritten content.
2. **Preprocessing**:
   - Convert to grayscale
   - Apply Gaussian blur
   - Use adaptive or binary thresholding
3. **Processing**:
   - Detect and highlight content areas
   - Filter out background noise
4. **Output**: A cleaned-up image highlighting the whiteboard content, suitable for OCR or saving.

---

## Possible Extensions

- Integrate OCR (e.g., Tesseract) for handwriting-to-text conversion
- Develop a real-time webcam-based whiteboard reader
- Add handwriting recognition for structured notes

---

## Getting Started

### Prerequisites
Make sure you have the following libraries installed:
```bash
pip install numpy opencv-python matplotlib
