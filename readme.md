# 🖱️ AirCtrl: AI Virtual Mouse with Hand Gesture Recognition

Transform your webcam into a smart AI-powered mouse controller!  
**AirCtrl** lets you **control your computer mouse** using only your **hand gestures**, powered by computer vision and hand tracking.



---

## 🚀 Features

- ✋ **Hand Tracking in Real Time** (via MediaPipe)
- 🖱️ **Move Mouse Cursor** using index finger
- 👆 **Click Action** with gesture combination (index + middle finger)
- ⚙️ **Configurable Frame Size** for better control
- 💡 **No Hardware Required** — just a webcam!

---

## 🧠 Technologies Used

| Tool / Library | Purpose |
|----------------|---------|
| [OpenCV](https://opencv.org/) | Image processing & webcam feed |
| [MediaPipe](https://mediapipe.dev/) | Hand detection & tracking |
| [Autopy](https://github.com/autopilot-rs/autopy) | Mouse control |
| Python | Core programming language |

---

## 📂 Project Structure

```
AirCtrl-AI-Virtual-Mouse/
├── AIvirtualmouse.py        # Main script to control mouse using gestures
├── handtrack.py             # Utility module for hand tracking (wrapper over MediaPipe)
├── README.md                # Project documentation
├── requirements.txt         # Python dependencies
└── .gitignore               # Files to ignore in Git
```

---

## 🧪 Demo & Usage

1. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

2. **Run the project**:
   ```bash
   python AIvirtualmouse.py
   ```

3. **Show your hand in front of your webcam**:
   - Move the **index finger** to move the mouse.
   - **Touch index + middle finger** together to click.
   - Move closer/further to adjust control sensitivity.

---

## 📦 Requirements

- Python 3.7+
- Webcam
- Modules in `requirements.txt`:
  - `opencv-python`
  - `mediapipe`
  - `autopy`
  - `numpy`

Install them via:

```bash
pip install -r requirements.txt
```

---

## 🧠 How It Works (Quick Overview)

1. **Capture video feed** using OpenCV.
2. **Detect hand landmarks** using MediaPipe’s Hand module.
3. **Track index finger** to map position to screen coordinates.
4. **Recognize gesture** (like finger distance) to trigger clicks using Autopy.

---


## 🙋‍♂️ Why This Project?

This is part of my exploration into gesture-controlled interfaces. The project bridges **AI and human-computer interaction** without the need for specialized devices like Leap Motion or Kinect. It’s lightweight, fun, and surprisingly accurate.

---

## 🛠️ To Do / Possible Enhancements

- Add **drag and drop** gesture
- Support **multi-monitor setups**
- Add **volume control** gestures
- Build a **GUI toggle overlay**

---

## 🤝 Contributing

Want to help improve it? Feel free to fork the repo and submit a pull request!  
Bug reports and feature ideas are also welcome in [issues](https://github.com/AbhishekSriv6387/AirCtrl-AI-Virtual-Mouse/issues).

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 📬 Contact

**Abhishek Srivastava**  
📧 abhisheksriv6387@gmail.com  
🔗 [GitHub](https://github.com/AbhishekSriv6387)

---

> ⭐ If you found this project cool or helpful, please give it a star!
