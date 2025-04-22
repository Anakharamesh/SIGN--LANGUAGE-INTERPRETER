# 🤟 AI-Powered Sign Language Interpreter

This is a browser-based **real-time sign language interpreter** that uses **TensorFlow.js** and the **HandPose model** to detect hand gestures and interpret American Sign Language (ASL) signs via your webcam.

---

## 📸 Live Demo

> **Coming Soon** — Deploy this with GitHub Pages or Netlify to see it in action!

---

## 🚀 Features

- ✅ Real-time hand tracking using TensorFlow.js
- ✅ Recognizes common ASL signs:
  - Hello
  - Thank You
  - I Love You
  - Yes
  - No
  - Please
- ✅ Interactive UI with sign description and history
- ✅ No backend required – runs fully in browser
- ✅ Gesture detection based on landmark geometry (not image classification)

---

## 🧠 How It Works

1. Loads the **HandPose model** from TensorFlow.js
2. Captures live video from webcam
3. Detects 21 3D landmarks on the hand
4. Matches finger states against predefined ASL patterns
5. Displays sign name, description, and logs the history

---

## 🧰 Tech Stack

- **HTML5**
- **CSS3**
- **JavaScript**
- [TensorFlow.js](https://www.tensorflow.org/js)
- [@tensorflow-models/handpose](https://github.com/tensorflow/tfjs-models/tree/master/handpose)

---

## 📂 File Structure

# SIGN--LANGUAGE-INTERPRETER
This project is a real-time Sign Language Interpreter built using TensorFlow.js and the HandPose model. It leverages the webcam to recognize American Sign Language (ASL) gestures and displays their corresponding meanings and descriptions on-screen.

---

## 🛠️ Setup & Usage

1. Download or clone the repository
2. Open `AI PROJECT FINAL.HTML` in any modern browser (Chrome recommended)
3. Click **Start Camera**
4. Show a supported ASL gesture
5. Watch it get interpreted live! ✨

---

## ⚠️ Limitations

- Relies on a **pretrained model (HandPose)** — not suitable where custom model restrictions apply.
- Works best with a **well-lit environment** and centered hand in camera view.

---

## 📜 License

This project is for educational/demo purposes only. MIT License can be added if needed.

---

## 🙌 Author

Made with ❤️ by **Anakha**  
_“Bridging gaps between communication through AI”_


