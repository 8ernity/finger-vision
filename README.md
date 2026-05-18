<h1 style="margin:0;">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/270b/512.gif" alt="✋" width="38" style="vertical-align:-4px;">
 FingerVision — Real-Time Hand Tracking
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f680/512.gif" alt="🚀" width="38" style="vertical-align:-4px;">
</h1>


<p align="center">
  <b>A futuristic web-based hand tracking system powered by AI</b><br>
  Detect fingers • Track motion • Draw in air — all from your webcam
</p>

---

## 🎬 Live Demo

👉 https://8ernity.github.io/finger-vision/

---

##  
<h2 style="margin:0;">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f9e0/512.gif" alt="🧠" width="25" style="vertical-align:-4px;">
  What is FingerVision?
</h2>

FingerVision is a **real-time hand tracking web app** that uses computer vision to detect and track your fingers through a webcam.

It allows you to:

* Interact with your screen using gestures
* Track fingertip positions
* Draw in the air like magic ✨

---

<h2 style="margin:0;">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/2728/512.gif" alt="✨" width="25" style="vertical-align:-4px;">
  Features
</h2>


* 🖐 **Real-time Hand Tracking** using MediaPipe
* 🔢 **Finger Counting** (supports both hands)
* 🎯 **Fingertip Coordinate Tracking**
* ✏️ **Air Drawing Mode**
* 🧭 **Left & Right Hand Detection**
* 🎨 **Futuristic UI Design**
* ⚡ **Ultra-smooth real-time performance**

---

<h2 style="margin:0;">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f6e0\_fe0f/512.gif" alt="🛠️" width="28" style="vertical-align:-4px;">
  Tech Stack
</h2>


| Technology      | Purpose             |
| --------------- | ------------------- |
| HTML5           | Structure           |
| CSS3            | UI & Animations     |
| JavaScript      | Logic & Interaction |
| MediaPipe Hands | AI Hand Tracking    |

---

## 🏛️ System Architecture

```mermaid
sequenceDiagram

    participant U as User
    participant C as Camera
    participant JS as JavaScript
    participant AI as MediaPipe
    participant UI as Canvas

    loop Real-Time Processing
        U->>C: Show hand gesture
        C->>JS: Send video frame

        JS->>AI: Process frame
        AI-->>JS: Return landmarks

        JS->>JS: Calculate finger positions
        JS->>UI: Draw on canvas

        UI-->>U: Display output
    end
```

## ⚙️ How It Works


1. Webcam captures live video
2. MediaPipe detects hand landmarks (21 key points)
3. JavaScript processes coordinates
4. UI renders tracking + drawing in real-time

---

<h2 style="margin:0;">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f4e6/512.gif" alt="📦" width="28" style="vertical-align:-4px;">
  Run Locally
</h2>


```bash
git clone https://github.com/8ernity/finger-vision.git
cd finger-vision
```

Then open `index.html` in your browser.

---

<h2 style="margin:0;">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f3af/512.gif" alt="🎯" width="28" style="vertical-align:-4px;">
  Use Cases
</h2>


* Gesture-based UI interaction
* Virtual drawing / teaching tools
* AR/VR experimentation
* Computer vision learning projects

---

## 🔮 Future Enhancements

* 🤖 AI gesture commands (click, scroll, zoom)
* 🎮 Gesture-controlled games
* 🧠 ML-based gesture recognition
* 📱 Mobile optimization

---

## 📜 License

MIT License — free to use and modify.

---

<p align="center">
  Built with ❤️ using Computer Vision
</p>
