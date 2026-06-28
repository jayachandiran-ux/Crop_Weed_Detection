# 🌱 Crop and Weed Detection using YOLOv8

## 📌 Project Overview

This project implements an AI-powered Crop and Weed Detection system using the YOLOv8 object detection model. The model is trained to automatically identify crops and weeds from agricultural field images, helping farmers improve weed management and precision farming.

---

## 🚀 Features

- Detects crops and weeds from field images
- Uses YOLOv8 Nano for object detection
- Bounding box visualization
- Model training and evaluation
- Image prediction using trained model

---

## 🛠️ Technologies Used

- Python
- YOLOv8 (Ultralytics)
- OpenCV
- NumPy
- Matplotlib
- Google Colab

---

## 📂 Dataset Summary

- Total Images: **1300**
- Total Label Files: **1300**
- Crop Objects: **1212**
- Weed Objects: **860**

---

## 📊 Model Configuration

- Model: YOLOv8 Nano
- Epochs: 20
- Image Size: 512 × 512
- Batch Size: 16

---

## 📈 Results

The model successfully detects crops and weeds using bounding boxes. It was trained using a custom agricultural dataset and evaluated on validation images.

---

## 📷 Sample Prediction

<img src="images/prediction_result.jpg" width="600">

---

## 📉 Training Results

<img src="images/results.png" width="700">

---

## 📊 Confusion Matrix

<img src="images/confusion_matrix.png" width="600">

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
```

```python
from ultralytics import YOLO

model = YOLO("best.pt")

model.predict(
    source="image.jpg",
    save=True
)
```

---

## 📁 Project Structure

```
Crop_Weed_Detection
│
├── Crop_Weed_Detection.ipynb
├── README.md
├── requirements.txt
└── images
    ├── prediction_result.jpg
    ├── results.png
    └── confusion_matrix.png
```

---

## 👨‍💻 Author

**Jayachandiran K**

B.Tech Artificial Intelligence & Data Science

Nehru Institute of Engineering and Technology

---

⭐ If you found this project useful, consider giving it a star.
