# Traffic Management System Using YOLO (v8–v11)

This project implements a **Traffic Management System** using YOLO object detection models (v8–v11)
It is designed to **monitor traffic flow**, count vehicles, detect congestion, and identify potential traffic jams in real-time. 
The system works on **Google Colab** and can analyze video footage for autonomous traffic monitoring applications.

---

## 🔹 Key Features
- **Vehicle Counting**: Detects cars, trucks, motorcycles, and other vehicles in real-time 
- **Traffic Flow Analysis**: Measures traffic smoothness or congestion.  
- **Traffic Jam Detection**: Flags areas where vehicles remain stationary for a prolonged time (e.g., 10 vehicles in one zone)
- **Real-Time Monitoring**: Works on video streams with annotated frames.  
- **YOLO Models**: Tested with YOLOv8 to YOLOv11 for accuracy and performance.

---

### Traffic Flow Monitoring
![Traffic Screenshot 1](val_results/Screenshot%202025-08-15%20002708.jpg)  
*Traffic Detection Sample 1*

![Traffic Screenshot 2](val_results/Screenshot%202025-08-15%20002725.jpg)  
*Traffic Detection Sample 2*

## 🚗 Vehicle Detection.

Here are some sample detected frames from the model:

![Detection 1](val_results/1_mp4-0_jpg.rf.71f17d5bdbcac3f9939ae34558b63288.jpg)  
![Detection 2](val_results/2_mp4-22_jpg.rf.7e53e9a475efa9889dc0a74380255e9b.jpg)  
![Detection 3](val_results/3_mp4-2_jpg.rf.fb3ec30812baf2bbaca8718878601bde.jpg)  
![Detection 4](val_results/4_mp4-8_jpg.rf.1d199d41f6c3738763c192883ad1a5b4.jpg)  
![Detection 5](val_results/5_mp4-26_jpg.rf.61d8ef7774c6c33aa7015c91dc91aa34.jpg)

---

## 📊 Results / Evaluation

Here are the evaluation results and metrics from the Traffic Management System:

### Confusion Matrices
![Confusion Matrix](val_results/confusion_matrix%20(1).png)  
![Normalized Confusion Matrix](val_results/confusion_matrix_normalized.png)  

### Performance Graph
![Results Graph](val_results/results.png)

---

## 🛠 Tech Stack
- **Python**  
- **YOLOv8 – YOLOv11** (Ultralytics)  
- **OpenCV**  
- **Google Colab / Kaggle**  
- **PyTorch**

---

## 🚀 How It Works.
1. **Video Input:** Feed traffic footage into the model.  
2. **Object Detection:** YOLO detects vehicles and pedestrians.  
3. **Vehicle Counting:** Count moving and stationary vehicles in each zone.  
4. **Traffic Flow Analysis:** Determine smoothness or congestion.  
5. **Traffic Jam Detection:** Flag areas where multiple vehicles stay for a prolonged time.

---

## 📄 Applications
- Smart city traffic monitoring  
- Autonomous vehicle research  
- Traffic safety analysis
