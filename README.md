# 🚗 Vehicle Number Plate Detection System using YOLOv10 and OpenCV

An advanced, real-time vehicle number plate detection system built using **YOLOv10**, **OpenCV**, and **Python**. This project leverages deep learning to detect number plates and classify characters (A–Z, 0–9) with high accuracy and speed.

---

## 📌 Features

- ✅ Real-time number plate detection
- 🔤 Trained on 36 alphanumeric characters (A–Z, 0–9)
- ⚡ Fast and accurate using YOLOv10
- 🎥 Supports video streams and webcam input
- 🗂️ YOLO format dataset preparation and training
- 🔍 Character segmentation and recognition using CNN

---

## 🧠 Technologies Used

- 🐍 Python 3.12
- 🔍 YOLOv10 via [Ultralytics](https://github.com/ultralytics/ultralytics)
- 🎥 OpenCV for video and image processing
- 🧠 TensorFlow / Keras for character recognition
- 🧾 EasyOCR (optional) for text extraction
- 📈 Matplotlib, Seaborn for training visualizations

---

## 📁 Directory Structure
Vehicle-Number-Plate-Detection/
├── yolov10s.pt # Pre-trained YOLOv10 model
├── model.h5 # Trained CNN model for character recognition
├── main.ipynb # Jupyter notebook for full pipeline
├── detect_plate.py # Script for YOLO-based plate detection
├── recognize_chars.py # Script for character segmentation & recognition
├── utils/
│ ├── preprocess.py # Preprocessing functions
│ └── draw_boxes.py # Helper to draw boxes and annotations
├── data/
│ ├── train/ # Training images (YOLO format)
│ └── test/ # Test images/videos
├── outputs/
│ ├── cropped_plates/ # Cropped number plate regions
│ └── recognized_text/ # Extracted text results
├── requirements.txt # Dependencies
├── README.md # Project overview

