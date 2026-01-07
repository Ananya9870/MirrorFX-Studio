# 🎭 MirrorFX-Studio  
**A Real-Time Gesture-Controlled AR Visual Effects Mirror**

MirrorFX-Studio is an interactive computer vision project that transforms a live webcam feed into an artistic **digital mirror**. Using **hand gestures**, users can seamlessly switch between multiple visual rendering styles such as dots, edge outlines, ASCII art, and particle effects — all in real time.

This project blends **Computer Vision, Human–Computer Interaction (HCI), and Creative Coding**, making it ideal for portfolios, hackathons, and AR/AI demonstrations.

---

## ✨ Features

- 🎥 Live Webcam Processing using OpenCV  
- ✋ Hand Gesture Recognition with MediaPipe Hands  
- 🎨 Multiple Visual Effect Modes  
  - Dots (Stipple Art)
  - Lines (Edge Detection)
  - ASCII Art Rendering
  - Particle System Effects
- 🔁 Real-Time Mode Switching using gestures (no keyboard/menu)
- 🪞 Mirror View Split Screen  
  - Left: Original feed  
  - Right: Stylized clone  
- ⚡ Optimized for smooth real-time performance

---

## 🧠 How It Works

1. Webcam feed is captured and mirrored  
2. MediaPipe detects hand landmarks  
3. Finger positions are analyzed to recognize gestures  
4. Each gesture maps to a visual rendering mode  
5. Image processing effects are applied frame-by-frame  
6. Output is displayed as a side-by-side AR mirror  

---

## ✋ Gesture Controls

| Gesture | Mode | Effect |
|------|------|------|
| ✌️ Two Fingers | Dots Mode | Colorful stippled dot rendering |
| ☝️ One Finger | Lines Mode | Neon-style edge outlines |
| 🤙 Thumb + Pinky | ASCII Mode | Image rendered using ASCII characters |
| ✋ Open Palm | Particles Mode | Dynamic particle emission from hand |

---

## 🛠️ Tech Stack

- Python  
- OpenCV – Video capture & image processing  
- MediaPipe – Hand tracking & landmark detection  
- NumPy – Numerical operations  

---

## 📂 Project Structure

MirrorFX-Studio/
│
├── mirrorfx_studio.py # Main application script
├── README.md # Project documentation
└── requirements.txt # Dependencies

---

## ⚙️ Installation & Setup

### Clone the Repository
```bash
git clone https://github.com/your-username/MirrorFX-Studio.git
cd MirrorFX-Studio

🚀 Usage Instructions

Ensure your webcam is connected

Run the script

Show hand gestures in front of the camera

Watch the visual clone react instantly

Press q to exit

🎯 Applications

AR / XR Experiments

Creative Coding & Digital Art

Gesture-Based Interfaces

Human–Computer Interaction Research

AI & Computer Vision Portfolios

Hackathons & Tech Exhibitions


📌 Why MirrorFX-Studio?

MirrorFX-Studio demonstrates how AI-powered vision systems can replace traditional input methods and create natural, intuitive user experiences. It’s not just a filter — it’s an interactive AR mirror driven entirely by human gestures.

👤 Author

Ananya Kriti
Computer Vision | AI | Creative Technology

⭐ If you like this project, consider starring the repository!
