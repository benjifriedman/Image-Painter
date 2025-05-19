# Image Painter

A modern, browser-based tool for creative image manipulation.  
**Select, paint, and remix images with custom brushes and export your results!**

---

## Features

- **Upload** JPG or PNG images (PNG supports transparency).
- **Select** any rectangular region from the original image.
- **Paint** the selected region onto a blank canvas of the same size, using:
  - Rectangle, Circle, or Ellipse brush shapes
  - Click or drag to paint multiple times
  - Centered placement at the cursor
- **Customizable UI:**
  - Change the painted canvas background color (supports transparency)
  - Adjust selection rectangle color and stroke width
- **Responsive, dark mode UI** that maximizes canvas size
- **Save** your painted canvas as PNG (with transparency) or JPG (if the input was JPG), with a timestamped filename
- **Clear** the painted canvas at any time

---

## Usage

1. **Open `index.html` in your browser.**
2. Click **“Upload”** and select a JPG or PNG image.
3. **Drag** on the left canvas to select a region (a bold outline will appear).
4. **Choose your brush shape** (Rectangle, Circle, Ellipse) from the dropdown.
5. **Click or drag** on the right canvas to paint the selected region, centered at the cursor.
6. Adjust **background color**, **selection color**, and **stroke width** as desired.
7. Click **“Clear Painted Canvas”** to reset, or **“Save”** to download your creation.

---

## File Types

- **Input:** JPG or PNG
- **Output:**  
  - **PNG** (default, supports transparency)  
  - **JPG** (if the uploaded file was a JPG)

---

## How It Works

- The painted canvas is always the same size as the uploaded image.
- You can select new regions as many times as you want.
- Painting works even if you drag outside and back into the canvas.
- The saved file is named with a timestamp, e.g. `painted-canvas-20240608-153012.png`.

---

## Requirements

- Any modern web browser (Chrome, Firefox, Safari, Edge, etc.)
- No installation or dependencies required

---

## License

MIT License

---

**Enjoy painting!**  
If you have ideas for new features or improvements, feel free to suggest them.
