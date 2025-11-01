
----
# 🖐️ Hand HUD — Palm-Anchored Kinematic Dashboard  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-Enabled-green)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hand%20Tracking-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey.svg)
![Contributions Welcome](https://img.shields.io/badge/Contributions-Welcome-brightgreen.svg)

---

## 🎯 Overview  
**Hand HUD** is a real-time, palm-anchored **kinematic dashboard** built using **OpenCV** and **MediaPipe**.  
It detects your hand from a webcam feed and overlays a **mechanical-style HUD (Heads-Up Display)** centered on the palm.  

### ✨ Features
- 🌀 Palm-centered **radial UI**
- 🦴 **Finger bone visualization**
- 🧭 **Rotation & kinematic readouts**
- 🧊 **3D cube** and **grid overlay**
- ⚙️ Real-time MediaPipe tracking

Ideal for gesture-based interaction research, AR prototyping, or visualization demos.

---

## 📁 Project Structure  
```plaintext
hand-hud/
├── main.py              # Application entrypoint & webcam loop
├── hand_overlay.py      # HUD drawing & kinematic computations
├── utils.py             # Helper functions (geometry, smoothing)
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
````

---

## ⚙️ Installation & Usage

### 1️⃣ Create a virtual environment (recommended)

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

### 2️⃣ Install dependencies

```powershell
pip install -r requirements.txt
```

### 3️⃣ Run the application

```powershell
python main.py
```

🖥️ A webcam window will open — move your hand into the frame to see the live HUD.

---

## 🔧 Configuration

* 👋 **Single-hand mode** is enabled by default.
  → To enable **multi-hand mode**, toggle the flag in `main.py`.
* 🧮 Adjust **smoothing**, **HUD layout**, and **drawing constants** in `hand_overlay.py`.
* 📸 Optionally enable **recording/output images** (feature-ready).

---

## 🪪 License

This project is released under the **MIT License** — see [LICENSE](LICENSE).
You’re free to reuse, modify, and redistribute this code with proper credit.
If you prefer an attribution-required license (e.g., **CC BY 4.0**), contact the maintainer.

---

## 🤝 Contributing

Contributions are welcome!
To contribute:

1. Open an **issue** to discuss your idea or report a bug.
2. Create a **branch** for your change.
3. Submit a **pull request** with a clear description.

By contributing, you agree your code will be shared under this project’s license (MIT by default).

---

## 📬 Contact

* 🧑‍💻 **Author:** [KShashikala10](https://github.com/KShashikala10)
* 🌐 **Repository:** [GitHub – hand-overlay](https://github.com/KShashikala10/hand-overlay)

⭐ *If you find this project useful, consider giving it a star on GitHub!*

---

