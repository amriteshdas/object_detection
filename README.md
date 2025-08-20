# 🖼️ Object Detection App using Python & OpenCV

This project is a simple **Object Detection App** built with Python, OpenCV, and YOLOv3-tiny.  
It can detect multiple objects in real-time using your webcam or video files.  

---

## 🚀 Features
- Real-time object detection using YOLOv3-tiny  
- Works with webcam and video files  
- Lightweight & fast (uses YOLOv3-tiny for speed)  
- Easy to install and run  

---

## 🛠️ Installation & Setup

### 1. Clone this repository  
```bash
git clone https://github.com/your-username/object-detection-app.git
cd object-detection-app
```

### 2. Install Python (Mac/Linux/Windows)  
Make sure you have **Python 3.8+** installed.  

Check version:
```bash
python3 --version
```

### 3. Install pip (Mac)  
Check if pip is installed:
```bash
pip3 --version
```

If not, install pip:  
```bash
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py
```

Upgrade pip:
```bash
pip3 install --upgrade pip
```

### 4. Install dependencies  
```bash
pip3 install opencv-python numpy
```

---

## 📂 Download YOLO Files  

Download YOLOv3-tiny config and weights:  

- [yolov3-tiny.cfg](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3-tiny.cfg?raw=true)  
- [yolov3-tiny.weights](https://pjreddie.com/media/files/yolov3-tiny.weights)  
- [coco.names](https://github.com/pjreddie/darknet/blob/master/data/coco.names?raw=true)  

Put these files inside your project folder.

---

## ▶️ Run the App  

### Run with webcam:
```bash
python3 object_detection.py
```

### Run with video file:
```bash
python3 object_detection.py --video sample.mp4
```

---

## 📸 Screenshot (Example)

![Detection Screenshot](https://raw.githubusercontent.com/pjreddie/darknet/master/data/dog.jpg)

---

## 🤝 Contributing  
Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

---

## 📜 License  
This project is licensed under the MIT License.  

---

💡 Built with ❤️ using Python & OpenCV
