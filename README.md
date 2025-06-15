🎨 Real-Time Sketch to Image Generator using AI

If you find this project helpful or inspiring, please consider ⭐ starring the repository and supporting its growth!

 🌟 Why Star This Repository?
- Increases visibility of my work  
- Encourages further development and feature upgrades  
- Supports open-source innovation for creative tech  

🔗 [**GitHub Repository – Click here to Star**](#)
✨ Features

🖐️ Gesture + Mouse Support
Draw with your fingers (MediaPipe) or use the mouse via the canvas interface.

🖌️ Drawing Tools
- Brush  
- Eraser  
- Rectangle (outline and filled)  
- Circle (outline and filled)  
- Line Tool  

🎨 Color Palette
- Choose from **12 vibrant preset colors**

➕➖ Brush Size Adjustment
- Fine control using **+** and **−** buttons

 🖐️ MediaPipe Hand Tracking
- Use **pinch gesture** to draw or place shapes (in gesture mode)

🧹 Canvas Clearing
- Instantly reset your workspace with a "Clear All" option

🧼 Clean UI
- Top panel includes:
  - Tool selection icons  
  - Color buttons  
  - Brush size control  
  - Live canvas preview

⚡ Smooth Drawing Experience
- Implements **point averaging** for stable and smoother line rendering

## 🖼️ Preview
| ![preview1](https://github.com/221FA04508/Real-Time-Sketch-to-Image-Generator-using-AI/blob/8173c58bc45155c40df11b36a95d7a5a8e9ed630/p21.png) |


## 💻 System Requirements

- Python **3.6+**  
- **Webcam** (internal or external) for gesture mode  
- Compatible browser for web UI (if using Streamlit/Gradio)

## 📚 Libraries Used

- [`OpenCV`](https://opencv.org/) (`cv2`) – for real-time video/image processing  
- [`MediaPipe`](https://developers.google.com/mediapipe) – for gesture and hand tracking  
- [`NumPy`](https://numpy.org/) – for matrix operations and canvas processing  
- [`Gradio`](https://gradio.app/) or `Streamlit` – for the interactive UI  
- `diffusers` + `ControlNet` (optional for sketch-to-image functionality)

## 🚀 How to Run

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
python app.py

