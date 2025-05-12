

# 🚗 Automatic License Plate Detection and Recognition

This project detects and recognizes license plates from **images** and **videos** using a combination of **YOLO-based contour detection** and **EasyOCR** for optical character recognition. It is optimized for **real-time** or **batch processing**, and can be run seamlessly in environments such as **Google Colab** or locally.

---

## 📸 Project Features

* 📷 **Image and video input support** for flexible media processing.
* 🎯 **License plate localization** using **contour detection** (YOLO-free).
* 🔤 **Text recognition** from license plates using **EasyOCR**.
* ⏱️ **Real-time video processing** with **frame skipping** for improved performance.
* 🧾 **Outputs annotated media** with detected license numbers overlaid.

---

## 🛠️ Tech Stack

* **Python 3.x**
* **OpenCV** for image/video processing
* **EasyOCR** for optical character recognition (OCR)
* **NumPy** for numerical operations
* **imutils** for image manipulation
* **Google Colab** (optional, for cloud execution)

---

## 🧑‍💻 How to Run

### ✅ Google Colab (Recommended)

1. Open the notebook in **Google Colab**.
2. Upload your **image or video** when prompted.
3. The processed output (annotated image/video) will be displayed and made available for download.

---

### 🖥️ Local Setup

1. Ensure **Python 3.x** is installed.

2. Install dependencies:

   ```bash
   pip install opencv-python easyocr imutils numpy
   ```

3. Run the script:

   ```bash
   python main.py
   ```

---

## 🧾 Requirements

To install all required packages, use:

```bash
pip install opencv-python easyocr imutils numpy
```

⚡ **Optional** (for **GPU acceleration** with EasyOCR):

```bash
pip install torch torchvision torchaudio
```

---

## 🖼️ Sample Output

* Detected license plates will be highlighted with **bounding boxes**.
* The recognized plate numbers will be **overlaid** on the images or video frames.

---

