# pendeteksi_badge_jurusan

A Computer Vision-based system designed to automatically detect and classify school or university department badges (e.g., Computer Science, Accounting, Mechanical Engineering) on student uniforms using deep learning.

## 🚀 Features
* **Real-Time Detection:** Supports live video stream processing via webcam or CCTV.
* **High Accuracy:** Powered by state-of-the-art object detection models fine-tuned on custom datasets.
* **Multi-Class Classification:** Capable of identifying and distinguishing multiple department logos simultaneously.
* **Visual Feedback:** Displays bounding boxes around detected badges with confidence scores.

## 🛠️ Tech Stack
* **Programming Language:** Python
* **Frameworks & Libraries:** OpenCV, Ultralytics YOLOv8 / PyTorch, NumPy
* **Annotation Tools:** Roboflow / LabelImg

## 📦 Installation

Follow these steps to set up the project locally:

1. **Clone the repository:**
   ```bash
   python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
python detect.py --source 0
python detect.py --source path/to/your/image.jpg
   git clone [https://github.com/mikirpakeal/pendeteksi_badge_jurusan.git](https://github.com/mikirpakeal/pendeteksi_badge_jurusan.git)
   cd pendeteksi_badge_jurusan
