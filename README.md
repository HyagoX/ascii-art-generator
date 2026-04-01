# 🎬 ASCII Video Art Generator (Real-Time)

A high-performance web tool that transforms live video streams and images into ASCII art using HTML5 Canvas and advanced image processing algorithms.

## 🚀 Key Features
- **Real-Time Video Rendering:** Processes video frames on the fly to generate dynamic ASCII animations.
- **Advanced Image Controls:** Interactive sliders for Brightness, Contrast, and Sharpness enhancement.
- **Customizable Detail Levels:** Adjustable resolution scaling (Low, High, Maximum) for different performance needs.
- **Multiple Charsets:** Choose between 5 different artistic styles, from detailed 16-level characters to simple block dots.

## 🛠️ Technical Implementation
- **Luminance Calculation:** Uses the specialized formula `(0.2126 * R + 0.7152 * G + 0.0722 * B)` for accurate grayscale mapping.
- **Canvas Manipulation:** Direct pixel data access via `getImageData` for custom image filtering (Sharpening and Contrast algorithms).
- **Responsive Interface:** Custom CSS with a "Terminal" aesthetic, fully optimized for mobile and desktop displays.

## 🧪 Mathematical Concepts Applied
This project applies digital signal processing concepts, such as convolution kernels for sharpening and linear transformations for contrast adjustment, all implemented in vanilla JavaScript.

---
*Developed as part of my studies in Applied Mathematics and Computational Logic.*
