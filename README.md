## Real-Time Object Detection using OpenCV DNN

A real-time object detection system that identifies and labels common objects from a live webcam feed using OpenCV’s Deep Neural Network (DNN) module and a pre-trained MobileNet-SSD model.

---

### About the Project

This project demonstrates real-time object detection using deep learning with OpenCV.  
It uses a **pre-trained MobileNet-SSD (Single Shot Detector)** model to detect and classify multiple objects such as persons, cars, dogs, bottles, and more from a live video stream.

The system processes each frame, performs inference using a deep neural network, and draws bounding boxes with class labels and confidence scores in real time.

---

### Features

- Real-time object detection using webcam  
- Deep learning–based detection with OpenCV DNN  
- Pre-trained MobileNet-SSD model  
- Multiple object classification  
- Bounding boxes with confidence percentage  
- Lightweight and fast inference  

---

### Technologies Used

- Python  
- OpenCV (DNN module)  
- NumPy  
- Imutils  
- Caffe pre-trained model  

---

### How to Run

1. Ensure the following model files are present in the project directory:
   - `MobileNetSSD_deploy.prototxt`
   - `MobileNetSSD_deploy.caffemodel`

2. Run the object detection script:
   ```bash
   python main.py
   
3. Press ESC to stop the camera feed and exit.

---

### Project Folder Structure

realtime-object-detection-opencv-dnn/
│
├── main.py                             # Real-time object detection script
├── MobileNetSSD_deploy.prototxt        # Model configuration file
├── MobileNetSSD_deploy.caffemodel      # Pre-trained weights
├── README.md                           # Project documentation
└── requirements.txt                    # Required libraries

---

### Working Principle

- Load the pre-trained MobileNet-SSD model  
- Capture live video frames using a webcam  
- Resize frames and create input blob  
- Pass blob through the DNN for inference  
- Extract detected objects with confidence scores  
- Draw bounding boxes and labels on detected objects  
- Display results in real time  

---

### Applications

- Real-time surveillance systems  
- Smart camera applications  
- Traffic monitoring  
- Human detection systems  
- Learning deep learning with OpenCV DNN  

---

### Output

- Live webcam feed with detected objects  
- Bounding boxes with object labels  
- Confidence percentage for each detection  

---

### Limitations

- Uses a pre-trained generic dataset  
- Limited to predefined object classes  
- Performance depends on system hardware  

---

### License

This project is intended for educational purposes.
