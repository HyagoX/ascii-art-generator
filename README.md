# 🖼️ Image to ASCII Art Converter

A web-based tool that transforms standard images into stylized ASCII art using pixel luminosity mapping. This project explores the intersection of computer vision basics and mathematical data representation.

## 🚀 Overview
The application processes uploaded images by analyzing the brightness (luminosity) of each pixel and mapping it to a specific character set. It's a practical example of how data can be reinterpreted and visualized through different formats.

## 🛠️ Tech Stack
- **Languages:** HTML5, CSS3, JavaScript (ES6+).
- **Core Logic:** Pixel manipulation, Grayscale conversion, and Character mapping.

## 🧪 Mathematical Concept
The core logic relies on a luminosity formula to calculate the "gray" value of a pixel:
`Gray = 0.299*R + 0.587*G + 0.114*B`
This value then determines which ASCII character (from `.` to `@`) best represents that specific area of the image.

## 🎨 Features
- Real-time image processing.
- Responsive UI for desktop and mobile.
- Custom character sets for different artistic effects.

---
*Developed as part of my studies in Applied Mathematics and Web Technologies.*
