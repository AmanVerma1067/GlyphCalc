# ✍️ GlyphCalc: Handwritten Expression Calculator

**GlyphCalc** is a Python-based application that uses computer vision and OCR to read and solve handwritten mathematical expressions. Simply upload or scan an image containing handwritten equations, and GlyphCalc will recognize and evaluate them with high accuracy.

---

## 🚀 Features

- 📷 Detect and extract handwritten text using OpenCV and Tesseract OCR  
- 🔍 Image preprocessing for better accuracy  
- 🧠 TensorFlow integration for digit/character classification (if needed)  
- ➕ Supports basic arithmetic: `+`, `-`, `*`, `/`  
- 🖼️ GUI support via Flask (if applicable) or simple CLI  
- 📊 Visual analytics using matplotlib  
- 🗃️ CSV logging with Pandas (optional)

---

## 🛠️ Tech Stack

| Tool/Library   | Purpose                               |
|----------------|----------------------------------------|
| `OpenCV`       | Image preprocessing and contour detection |
| `PyTesseract`  | OCR engine for character recognition    |
| `TensorFlow`   | Optional custom model for character prediction |
| `PIL (Pillow)` | Image format conversion and manipulation |
| `NumPy`        | Numerical operations and matrix handling |
| `Pandas`       | Logging detected expressions/results    |
| `Matplotlib`   | Optional plotting and result visualization |

---
