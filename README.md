# 🔥 Fire Detection using YOLOv8 (Webcam)

A real-time fire detection system built using **YOLOv8**, **OpenCV**, and **Streamlit**.
This application uses your system’s webcam to detect fire and display results instantly.

---

## 🚀 Features

* 🔥 Real-time fire detection using webcam
* 🤖 Powered by YOLOv8 (Ultralytics)
* 🎥 Live video processing with OpenCV
* 🌐 Simple and interactive UI using Streamlit
* ⚡ Fast and lightweight implementation

---

## 🧠 How It Works

1. The webcam captures live video frames
2. Each frame is passed to the YOLOv8 model (`best.pt`)
3. The model detects fire (if present)
4. The result is displayed with bounding boxes and status

---

## 📁 Project Structure

```
fire-detection-webcam/
│
├── app.py              # Streamlit UI (webcam + display)
├── main.py             # Fire detection logic (YOLO model)
├── best.pt             # Trained YOLOv8 model
├── requirements.txt    # Dependencies
└── README.md           # Project documentation
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/navedrys/fire-detection-app.git
cd fire-detection-app
```

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```
streamlit run app.py
```

👉 Open your browser and start detection using the checkbox.

---

## ⚠️ Important Notes

* 📌 This app uses your **local webcam**, so it works only on your machine
* ❌ Webcam is **not supported on Streamlit Cloud deployment**
* ✔️ Make sure `best.pt` is present in the root directory

---

## 🛠️ Tech Stack

* **YOLOv8** – Object Detection Model
* **OpenCV** – Image & Video Processing
* **Streamlit** – Web Application Framework
* **Python** – Core Programming Language

---

## 🎯 Future Improvements

* 📊 Display confidence score
* 🔔 Add alert system (sound/email)
* 🌫️ Detect smoke along with fire
* ☁️ Deploy using image/video upload support

---

## 💼 Use Cases

* Industrial safety monitoring
* CCTV surveillance systems
* Fire hazard detection
* Smart security applications

---

## 👨‍💻 Author

**Naved Shaikh**
📧 [navedrys@gmail.com](mailto:navedrys@gmail.com)
📱 7414991107
🔗 LinkedIn: https://www.linkedin.com/in/your-linkedin-id

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it!
