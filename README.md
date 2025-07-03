# 🛰️ AI-Based Surveillance System for Farm Intrusion Detection

A real-time computer vision solution designed to enhance farm security by detecting unauthorized intrusions — including humans and animals — in agricultural areas. Built using **YOLOv5**, **OpenCV**, and **Google Colab**, this system offers a lightweight yet powerful framework for rural and smart farming surveillance needs.

---

## 📌 Project Overview

With the rise in agricultural theft and wildlife intrusions, traditional farm surveillance systems are no longer efficient. This AI-driven solution leverages deep learning for **automated visual monitoring**. It detects and classifies objects (such as humans or animals) through **real-time video feeds** or uploaded images.

🔒 **Goal:** Improve security and awareness in farm environments using intelligent vision systems.

🧠 **Core Approach:** Detect intruders using YOLOv5 object detection on camera feeds or uploaded images.

---

## 🛠️ Tech Stack

| Component         | Tool/Library                     |
|------------------|----------------------------------|
| Language          | Python 3                         |
| Object Detection  | YOLOv5 (You Only Look Once)      |
| Deep Learning     | PyTorch                          |
| Platform          | Google Colab                     |
| Image Processing  | OpenCV                           |
| Visualization     | Matplotlib, cv2                  |
| Deployment Ready? | Yes (Notebook + Webcam Support)  |

---

## 📂 Project Structure

AI-Surveillance-System/
├── yolov5/ # YOLOv5 pre-trained models and weights
├── sample_images/ # Test images for running inference
├── camera_stream.py # Real-time webcam detection
├── image_detection.py # Detection on uploaded/static images
├── requirements.txt # Python dependencies
├── surveillance_notebook.ipynb # Main Google Colab implementation
├── utils/ # Helper scripts (e.g., draw boxes, labels)
└── README.md # This file

yaml
Copy
Edit

---

## 💻 How to Run

### 🔁 Option 1: Google Colab (Recommended)

Use the project directly in the cloud — no installation needed.

1. Click the link: [Open in Google Colab](https://colab.research.google.com/drive/YOUR_NOTEBOOK_LINK_HERE)
2. Follow the step-by-step instructions in the notebook.
3. Use webcam or upload an image for detection.

---

### ⚙️ Option 2: Run Locally

1. **Clone the repo**
   ```bash
   git clone https://github.com/Adarshthakur-850/AI-Surveillance-System.git
   cd AI-Surveillance-System
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run webcam-based detection

bash
Copy
Edit
python camera_stream.py
Detect from a static image

bash
Copy
Edit
python image_detection.py --img sample_images/farm1.jpg
📸 Sample Outputs
Input Image	YOLOv5 Detection

🧠 Model Info
Model Used: YOLOv5s (smallest & fastest variant)

Dataset: Pre-trained on COCO dataset

Customization: Easily extendable to custom datasets like crop fields, farm-specific animals, or vehicles

📈 Potential Use-Cases
🐾 Wildlife intrusion alert in farms

🚜 Smart agriculture security systems

🏡 Rural household perimeter surveillance

🌾 Crop monitoring for human presence

🧠 Edge-AI integration with IoT cameras

🛠️ Future Improvements
✅ Email/SMS-based alerting system

✅ Integration with Raspberry Pi + camera

✅ Custom training on rural intruder dataset

✅ Cloud deployment for mobile monitoring

✅ Integration with Twilio, Firebase, or AWS IoT Core

🙋‍♂️ Author
Adarsh Thakur
🔗 LinkedIn
📧 thakuradarsh8368@gmail.com
💻 GitHub

📜 License
This project is licensed under the MIT License.

⭐ Contribute or Support
If this project helped you, please ⭐ star the repository.
Feel free to open issues or PRs to improve the model, documentation, or add features!

yaml
Copy
Edit

---

✅ Just copy and paste this into your `README.md` file on GitHub.  
Let me know if you also want the **Colab notebook**, `requirements.txt`, or `camera_stream.py` templates.
