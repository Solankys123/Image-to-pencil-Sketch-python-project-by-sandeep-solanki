# 🖼️ Image to Pencil Sketch Converter 🎨
### A Python mini-project using OpenCV & Tkinter

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-red?logo=opencv)

---

## 📌 Overview
This project is a **simple yet elegant Python application** that transforms any image into a pencil sketch using **OpenCV**. The user selects an image file through a file browser, and the program displays the original image alongside its sketch version in real-time.

🔧 Built during the **LetsGrowMore Internship Program** as a fun and hands-on computer vision task.

---

## 🚀 Features

- 🖼️ Select any image using a file dialog
- 🧠 Convert it to grayscale
- 🎨 Apply sketch effect using **image inversion + Gaussian blur**
- 🖥️ Real-time display of original vs sketch side by side
- 📏 Auto resize to medium resolution for performance
- 🔄 Press `q` to exit the display window

---

## 🛠️ Technologies Used

| Tool/Library | Role |
|--------------|------|
| Python       | Core programming language |
| OpenCV       | Image processing (grayscale, blur, sketch) |
| Tkinter      | GUI file dialog to load images |
| NumPy        | Efficient image array operations |

---

## 💻 How to Run

1. 🔽 Clone this repository or download the `.py` file  
2. 🧰 Install required libraries:
   ```bash
   pip install opencv-python numpy
