# 🕹️ Hand Gesture Game Controller by Manoj

Control endless runner games like Subway Surfers or Temple Run using your hand gestures and webcam — no physical controller needed!  
Built with Python, OpenCV, and MediaPipe.

---

## ✨ Features

- 🎮 Play games using hand gestures  
- 🖐️ Real-time gesture detection via webcam  
- 🤖 Built with OpenCV + MediaPipe + PyAutoGUI  
- ⚡ Instant game control with keyboard simulation  

---

## 🧠 Gesture Mappings

| Gesture          | Action         |
|------------------|----------------|
| ☝️ Index Up      | Jump (↑)       |
| ✊ Fist           | Slide (↓)      |
| ✌️ Peace Sign     | Move Right (→) |
| 👌 OK Sign        | Move Left (←)  |
| ✋ Open Hand (Idle) | No Action    |

> 📝 All gestures are designed for **right-hand** use.

---

## 🚀 How It Works

1. Captures video frames via webcam  
2. Detects hand landmarks using MediaPipe Hands  
3. Interprets gestures by analyzing finger positions  
4. Uses PyAutoGUI to send keyboard presses to your active game window  

---

## 🧰 Libraries Required

```bash
mediapipe==0.10.8
opencv-python==4.9.0.80
pyautogui==0.9.54
numpy==1.26.4
