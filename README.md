# 🌷 Flower Bloom – AI Hand Gesture Flower Controller

An interactive **real-time flower blooming experience** powered by **MediaPipe Hands**, **HTML5 Canvas**, and **JavaScript**.

Control a procedurally generated tulip using nothing but your hands through your webcam.

---

## ✨ Features

* 🌷 Realistic animated tulip
* ✋ Real-time hand tracking using MediaPipe Hands
* 🤏 Left-hand pinch controls flower bloom
* 🌱 Right-hand pinch controls stem growth
* 🌬 Hand movement creates natural wind effects
* 🍃 Animated leaves and branches
* ✨ Floating pollen particle system
* 💡 Soft lighting and bloom effects
* 📱 Responsive full-screen experience
* ⚡ Runs entirely in the browser (no backend required)

---

## 🎮 Controls

| Gesture                | Action                            |
| ---------------------- | --------------------------------- |
| Left Hand Pinch        | Open / Close the flower bloom     |
| Right Hand Pinch       | Grow / Shrink the flower          |
| Move Hand Left / Right | Create wind that bends the flower |

---

## 🛠 Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* HTML5 Canvas API
* MediaPipe Hands
* Camera Utils
* Drawing Utils

---

## 📁 Project Structure

```text
Flower-Bloom/
│
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/flower-bloom.git
```

### Open the project

Simply open **index.html** in a browser.

For webcam access, it is recommended to serve the project locally using a web server.

Example:

```bash
python -m http.server
```

or

```bash
npx serve
```

Then open:

```
http://localhost:8000
```

---

## 🌐 Live Demo

After deploying with Vercel or GitHub Pages, your project will be available at:

```
https://your-project.vercel.app
```

or

```
https://YOUR_USERNAME.github.io/flower-bloom/
```

---

## 📷 Webcam Permission

This application requires access to your webcam.

When prompted by your browser:

✅ Click **Allow**

The application processes hand tracking entirely in your browser. No video is uploaded or stored.

---

## 🎨 How It Works

1. MediaPipe detects hand landmarks in real time.
2. Pinch distance is converted into bloom and growth values.
3. Organic noise simulates natural wind and movement.
4. Canvas renders:

   * Stem
   * Leaves
   * Branches
   * Animated tulip petals
   * Floating pollen particles
5. Hand movement influences wind, causing the flower to sway naturally.

---

## 📸 Screenshots

Add screenshots here after deployment.

Example:

```
screenshots/
├── home.png
├── bloom.png
└── gestures.png
```

---

## 🔮 Future Improvements

* 🌼 Multiple flower species
* 🌈 Dynamic flower colors
* 🌸 Garden mode
* 🎵 Ambient background music
* 🌦 Weather effects
* 🦋 Butterflies and bees
* 🌙 Day & Night cycle
* 🎥 Gesture recording
* 🥽 WebXR / AR support

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push to your branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

* MediaPipe Hands
* HTML5 Canvas
* Google
* Open Source Community

---

Made with ❤️ using JavaScript and Computer Vision.
