# 🛰️ Vision-Net — EO/IR Image & Video Classification for Military and Surveillance

> **HAL AEROTHON** — A 36-hour state-level hackathon focused on EO/IR sensor innovations, organized by Hindustan Aeronautics Limited.

🏅 **Top 35 Teams across Karnataka** — From hundreds of teams across the state, Team ByteOverflow was shortlisted among the Top 35!

---

## 📌 Table of Contents
- [About the Hackathon](#about-the-hackathon)
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [How to Run](#how-to-run)
- [Usage](#usage)
- [Team](#team)
- [Links](#-links)
- [Contributing](#contributing)
- [Contact](#contact)

---

## 🏆 About the Hackathon

Back in July, Team **ByteOverflow** had the exciting opportunity to participate in **HAL AEROTHON** — a 36-hour state-level hackathon focused on EO/IR sensor innovations.

### 👨‍💻 Our Project — Camouflage Object Detection for Military Applications

We built an ML model leveraging **EO/IR sensor-enabled cameras** to strengthen defense capabilities. Our solution can help detect objects such as **tanks, ships, and soldiers** — even under camouflage or in night conditions — thereby reducing risks from enemy threats.

### ✨ Key Highlights
- 📡 Built on **EO/IR camera data** for advanced detection
- 🎯 Focused on **camouflage object detection** in challenging environments
- ⚡ Designed for **faster and more reliable identification** in real-time
- 🧠 Powered by **YOLOv8** custom-trained on military object datasets

---

## 📁 Project Overview

This project provides a rapid classification system for **Electro-Optical (EO)** and **Infrared (IR)** imagery, primarily designed for military and surveillance applications. Leveraging a fine-tuned **YOLOv8** object detection model, the system accurately identifies key targets such as:

- 👤 Personnel
- 🚙 Vehicles
- 🛡️ Armored Units
- ✈️ Aircraft
- 🔫 Weapons

The application includes a professional dark-themed web interface built with **Flask**, enabling image and video file uploads with real-time annotated detection results.

---

## 🎯 Objective

The primary goal is to enhance **real-time situational awareness** and support **critical decision-making** in defense and surveillance environments. It focuses on EO/IR image interpretation under challenging conditions such as:

- 🌙 Low-light or night operations
- 🌲 Camouflaged terrains
- 🌫️ Visual obstructions (fog, smoke, haze)

---

## ✨ Features

- 🔍 **Image Classification** — Upload EO/IR images (JPG, JPEG, PNG) and detect military-relevant targets with bounding-box annotations.
- 🎞️ **Video Frame Analysis** — Automatically extract and process frames at 2 FPS (first 30 seconds) and run detection on each frame.
- 🧠 **YOLOv8 Model** — Fine-tuned custom-trained object detection for high accuracy.
- 🌐 **Flask Web UI** — Drag-and-drop dark-themed interface for uploading files and viewing results.
- 📸 **Hackathon Gallery** — Built-in showcase of HAL AEROTHON images and project story.

---

## 🛠️ Tech Stack

| Component | Technology |
|-----------|-----------|
| ML Model | YOLOv8 (Ultralytics) |
| Backend | Flask (Python) |
| Frontend | HTML, CSS (Dark Military Theme) |
| Image Processing | OpenCV, Pillow |
| Deployment | Local development server |

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/AbhiPatil-02/Vision-net-ir-eo.git
cd Vision-net-ir-eo
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Application
```bash
python app2.py
```

The app will start at **http://127.0.0.1:5000**.

---

## 🧪 Usage

1. Open `http://127.0.0.1:5000` in your browser.
2. Click **"Get Started"** or navigate to the **Upload** page.
3. Drag and drop or browse to select an image or video file (`.jpg`, `.jpeg`, `.png`, `.mp4`, `.avi`, `.mov`).
4. A preview of the uploaded file will appear.
5. Click the **"Run Detection"** button.
6. View the output with bounding boxes and labels rendered on the results page.

---

## 👥 Team

**Team ByteOverflow**
- Abhishek Patil
- Sanskar M Mudnur
- Sindhu Hullur
- Prakash Shejale

---

## 🔗 Links

- **GitHub Repository**: [github.com/AbhiPatil-02/Vision-net-ir-eo](https://github.com/AbhiPatil-02/Vision-net-ir-eo)
- **LinkedIn Post**: [HAL AEROTHON Experience](https://www.linkedin.com/posts/abhishek-r-patil_hackathon-machinelearning-artificialintelligence-activity-7372242209074642944-FY49)
- **DEPLOYED PROJECT**: [huggingface-deployment](https://abhipatil02-vision-net-eo-ir.hf.space/)
---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a Pull Request.

---

## 📬 Contact

For questions, issues, or collaborations, feel free to:

- Open an issue on [GitHub](https://github.com/AbhiPatil-02/Vision-net-ir-eo/issues)
- Contact: abhipatilrcb@gmail.com
