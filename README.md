# 🎯 TrackCount360

<p align="center">
  <img src="https://img.shields.io/badge/YOLOv8-Ultralytics-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/OpenCV-RealTimeTracking-green?style=flat-square" />
  <img src="https://img.shields.io/badge/Direction%20Based%20Counting-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/Made%20With-%E2%9D%A4%EF%B8%8F%20Python-red?style=flat-square" />
</p>

## 📽️ Project Overview

**TrackCount360** is an advanced object tracking and counting system built using **Ultralytics YOLOv8** and **OpenCV**. It not only detects and tracks objects in real-time video streams but also smartly **counts objects based on their direction of movement**, such as upward or downward across custom-defined virtual lines.

> This is particularly useful for traffic monitoring, crowd analytics, people counting, or any directional flow analysis task.

---

## 🚀 Features

- ✅ Real-time object detection with **YOLOv8**
- ✅ Object tracking using built-in Ultralytics tracker
- ✅ Two-line system to count objects moving **up** or **down**
- ✅ Displays per-class count and direction
- ✅ Saves the output video with all annotations
- ✅ Clean and modular Jupyter Notebook

---

## 🖼️ Sample Output


<p align="center">
  <img src="assets/output_detected.gif" width="80%" alt="Sample Output">
</p>

---

## 🧠 Tech Stack

| Tool         | Description                         |
|--------------|-------------------------------------|
| Python       | Core programming language           |
| OpenCV       | Frame processing and video handling |
| YOLOv8       | Object detection & tracking         |
| Ultralytics  | Lightweight YOLOv8 API              |
| JupyterLab   | Interactive development environment |

---

## 📁 Folder Structure

```
TrackCount360/
├── notebooks/
│   └── tracking_counting_yolo.ipynb
├── test_videos/
│   └── your_video.mp4
├── output_videos/
│   └── counted_output.mp4
├── requirements.txt
└── README.md
```

---

## 📦 Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/TrackCount360.git
cd TrackCount360
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

> ⚠️ Make sure you are using Python 3.10+ and compatible environment. Colab users do not need manual installation of common libraries.

3. **Upload your video and YOLO model**, then run the notebook on:

- [Google Colab](https://colab.research.google.com/)
- JupyterLab

---

## ⚙️ Usage Guide

1. **Upload video file** (`.mp4`, `.avi`, etc.)
2. **Load YOLOv8 model** (e.g., `yolov8n.pt`, `yolov8s.pt`)
3. **Run all notebook cells**
4. **Get output video** with live bounding boxes, tracking IDs, class names, and directional counters

---

## 📊 Output Explained

- Bounding boxes drawn per object
- Unique ID for each object
- **Up/Down Count** per class based on line crossing
- Output saved as `counted_output.mp4`

---

## 📈 Future Enhancements

- 📍 Live webcam or RTSP/IP streaming
- 🧠 Fine-tuned YOLOv8 model for specific objects
- 📊 Export direction-based analytics to CSV/Excel
- 🔁 Web-based frontend dashboard with Streamlit or Flask

---

## 🙌 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Nikhil** –https://github.com/ScriptSherpa
> Robotics, AI, and Embedded Systems | Intern @ DRDO

---

## ⭐ Star the Repository

If you like this project, don’t forget to ⭐ the repo. It helps others discover it too!

<p align="center">
  <img src="https://img.shields.io/github/stars/yourusername/TrackCount360?style=social" />
</p>

