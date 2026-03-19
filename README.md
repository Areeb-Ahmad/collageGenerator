# 🎨 Mondrian Digital Atelier

A high-performance, interactive art engine inspired by the **De Stijl** movement and the works of **Piet Mondrian**. This project transforms images, text, and raw data into structured, geometric compositions.

---

## 🚀 Core Features

### 1. The Landing Page (`index.html`)
* **Dual-Purpose Design:** A high-impact "Hero" section with a custom-coded **Mondrian Art-Button** that transitions to the full app.
* **Quick Creator:** An integrated, lightweight version of the tool located directly on the home page for instant experimentation.
* **Responsive Layout:** Built with Bootstrap 5 to ensure the gallery looks like a professional exhibition on any device.

### 2. The Advanced Atelier (`mondrian.html`)
* **Nitro Load System:** A specialized fetching engine that processes batch URL imports in small "bursts" (concurrency of 5) to keep the browser responsive.
* **Smart Aspect Ratio Detection:** Automatically analyzes imported images to assign `span-wide` or `span-tall` classes, maintaining the visual balance of the grid.
* **CORS Proxy Integration:** Bypasses browser security restrictions to allow the loading and exporting of images from external domains.
* **Interactive Grid:** Full drag-and-drop reordering powered by `SortableJS` and one-click tile resizing.

---

## 🛠️ Technical Stack

* **Frontend:** HTML5, CSS3 (Custom Grid Logic), JavaScript (ES6+)
* **UI Framework:** [Bootstrap 5](https://getbootstrap.com/)
* **Interactivity:** [SortableJS](https://sortablejs.github.io/Sortable/)
* **Rendering:** [Html2Canvas](https://html2canvas.hertzen.com/)
* **Proxy:** CORS Anywhere (Public Middleman)

---

## 📦 Getting Started

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
    ```
2.  **Open Locally:**
    Open `index.html` in any modern web browser.
3.  **Deploy to GitHub Pages:**
    Push your code to a GitHub repository, go to **Settings > Pages**, and select the `main` branch as your source.

---

## 📖 Usage Guide

1.  **Input:** Paste an image URL or type a word into the "Smart Input" and hit **ADD**.
2.  **Batch Import:** Prepare a `.txt` file with one URL or text string per line. Upload it via the **Import** button to populate the grid instantly.
3.  **Refine:** * **Drag** tiles to find the perfect color balance.
    * **Click** a tile to cycle through sizes: Square → Wide → Tall → Large.
4.  **Export:** Click **Export PNG** to render your composition into a high-quality image file.

---

## 📜 License

This project is licensed under the **MIT License**.

Copyright (c) 2026 [Areeb-Ahmad]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
