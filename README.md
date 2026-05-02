# Arabic Sign Language (ArSL) Detection using YOLOv5, YOLOv8, and YOLOv12 - CSC489

## 📌 Project Overview

This project focuses on detecting Arabic Sign Language (ArSL) alphabet hand gestures using deep learning object detection models. The project compares three YOLO versions: YOLOv5, YOLOv8, and YOLOv12.

The main goal is to evaluate which YOLO model performs best for recognizing Arabic alphabet hand signs in terms of accuracy, speed, model size, and real-time usability.

---

## 👥 Team Members

- Dimah Althunayyan  
- Rehaf Alfaleh  
- Laura Almasoud  

---

## 🎯 Objective

- Build an Arabic Sign Language hand gesture detection system  
- Train and evaluate YOLOv5, YOLOv8, and YOLOv12  
- Compare model performance using mAP, FPS, FLOPs, and model size  
- Identify strengths and limitations of each model  
- Provide a foundation for future ArSL translation systems  

---

## 📊 Dataset

The dataset consists of images representing Arabic Sign Language (ArSL) alphabet hand gestures.

### 🔹 Dataset Details
- Number of Classes: 29 (Arabic alphabet signs)  
- Total Images: Approximately 2,900  
- Images per Class: Between 91 and 111 images  

### 🔹 Data Split
The dataset was divided as follows:
- Training Set: 80%  
- Validation Set: 10%  
- Testing Set: 10%

---

## 🤖 Models Used

- YOLOv5  
- YOLOv8  
- YOLOv12  

---

## ⚙️ Methodology

1. Data collection and preprocessing  
2. Image labeling (bounding boxes)  
3. Data augmentation  
4. Model training  
5. Hyperparameter tuning  
6. Evaluation and comparison  


---

## 📈 Performance Evaluation

### 🔹 Metrics
- mAP50  
- mAP50-95  
- FPS  
- FLOPs  
- Model size  

### 🚀 Model Comparison

| Model | FPS | FLOPs | Model Size |
|---|---:|---:|---:|
| YOLOv5 | 101.2 | 16.0G | 14.6 MB |
| YOLOv8 | 108.67 | 28.5G | 21.49 MB |
| YOLOv12 | 38.3 | 21.3G | 18.95 MB |

---

## 🧠 Key Results

- 🥇 YOLOv8 achieved the best overall performance  
- ⚖️ YOLOv12 showed strong accuracy but slower speed  
- ⚡ YOLOv5 was fastest but less precise  

---

## 🔍 Observations

- Clear gestures (e.g., seen, sheen) → high accuracy  
- Similar gestures (e.g., ba, ta, thaa) → lower accuracy  
- Background and lighting affect detection  

---

## ⚠️ Limitations

- Similar hand shapes are difficult to distinguish  
- Background clutter reduces accuracy  
- Lighting conditions impact results  
- Limited dataset size  
- Real-time performance varies across models  

---

## 💡 Applications

- Assistive tools for Deaf Arabic speakers  
- 📱 Mobile and real-time applications  
- 🎓 Educational tools  
- 🏢 Customer service accessibility  
- 🏛️ Government service support  

---

## 🔗 Dataset & Model Weights (Google Drive)

Due to GitHub file size limitations, the dataset and trained model weights are hosted externally.

📁 Access them here:  
👉 https://drive.google.com/drive/folders/1q6dK3M9PN9zt1b3XQa8NTTsrjpB928rr?usp=sharing

### 📦 Contents of the folder:
- Arabic Sign Language dataset (.zip)
- YOLOv5 trained weights (.pt)
- YOLOv8 trained weights (.pt)
- YOLOv12 trained weights (.pt)

---

### ⚠️ Note
- These files are large and are not included in this repository.
- Make sure to download and extract the dataset before running the notebooks.