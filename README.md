# Computer Vision with YOLOv8 and EasyOCR

This repository demonstrates the use of YOLOv8 for object detection and tracking, combined with EasyOCR for text detection in images and videos. The code provides a pipeline for loading images and videos, performing object detection, and extracting text from the images.

## Features

- **YOLOv8 Object Detection**: Utilize the YOLOv8 model for detecting objects in images and videos.
- **EasyOCR Text Detection**: Leverage EasyOCR to detect and extract text from images.
- **Video Processing**: Detect and track objects in video files, and save the processed video with tracked objects.

## Prerequisites

Ensure you have the following installed:

- Python 3.7+
- [Ultralytics](https://github.com/ultralytics/ultralytics)
- OpenCV
- EasyOCR
- Matplotlib

You can install the required libraries using the following command:

```bash
pip install ultralytics opencv-python easyocr matplotlib
```

## Usage

To run the object detection and text extraction pipeline, run the following command:

```bash
python main.py --input <path_to_input_file> --output <path_to_output_file>
```

Replace `<path_to_input_file>` with the path to the input image or video file, and `<path_to_output_file>` with the path to save the processed output file.

