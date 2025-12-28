![Banner](https://i.pinimg.com/originals/3f/35/90/3f3590a3809163db554425361295f121.jpg)

# 🌀 Doctor Strange Filter with Python

A **real-time hand tracking & magic circle filter** inspired by Marvel's Doctor Strange.  
This project leverages **Mediapipe** and **OpenCV** to replicate the mystical circles on your palms, reacting to hand gestures in real time.

---

## ✨ Features

- Detects **hand gestures** using your device's camera.
- Calculates **palm openness and center** to apply the magic circles.
- Overlay **rotating inner & outer circles** dynamically.
- Demonstrates **transparent image overlay** and **rotation effects**.
- Configurable via `config.json` for custom settings.

---

## 🗂 Folder Structure

```
.
├── Models                    
│   ├── Inner Circles         # Inner magic circle images
│   └── Outer Circles         # Outer magic circle images
├── functions.py              # Helper functions for hand processing & overlays
├── main.py                   # Main script to run the filter
├── LICENSE
├── requirements.txt          # Project dependencies
└── README.md
```

---

## ⚡ Setup & Installation

1. **Clone the repository**

```bash
git clone https://github.com/imanshu-01/Doctor-Strange-Filter
cd Doctor-Strange-Filter
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the filter**

```bash
python main.py
```

> Make sure your overlay images are in the correct folders under `Models`.

---

## 🎥 Screenshots & Demo

<p align="center">
  <img src="https://user-images.githubusercontent.com/44752389/221366707-a1b93627-f246-428a-8397-864493b49d43.jpg" width="250" />
  <img src="https://user-images.githubusercontent.com/44752389/221366732-49876999-5b7c-4af1-9264-9656ae03f62c.jpg" width="250" /> 
  <img src="https://user-images.githubusercontent.com/44752389/221366735-d25b821a-c143-4cf5-bf80-eb7da7644f1c.jpg" width="250" />
</p>

<p align="center">
  <a href="<![https://github.com/imanshu-01/Doctor-Strange-Filter-with-Python/blob/main/Assets/IMG_5652.MOV]()">🎬 Watch Demo Video</a>
</p>

---

## 🛠 Technologies Used

- **Python 3.x**
- **OpenCV** – Real-time image processing
- **Mediapipe** – Hand detection & gesture tracking
- **JSON** – Configuration management

---

## 📐 How It Works

1. **Hand Detection:** The camera captures hand landmarks using Mediapipe.
2. **Gesture Analysis:** Measures distances between finger tips and palm to check openness.
3. **Overlay Application:** Applies rotating inner & outer circles at the palm center.
4. **Dynamic Animation:** Rotates images based on degree increments and updates in real-time.

> This project demonstrates advanced concepts like **perspective correction**, **rotation matrices**, and **transparent overlays**.

---

## ⚙️ Configuration

Edit `config.json` to customize:

- Camera resolution and device ID.
- Line settings (color, thickness).
- Overlay images and shield size multiplier.
- Rotation speed and quit key.

---

## 📝 License

This project is licensed under the **MIT License** – see the LICENSE file for details.

---

## 👤 Author

**Himanshu Narayan Patle**  

[![Instagram](https://img.shields.io/badge/Instagram-000000?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/h_imanshu_01/?next=%2F)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/himanshu-patle-2b563730b/)
[![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/imanshu-01)
