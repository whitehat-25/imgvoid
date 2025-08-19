# imgvoid

**imgvoid** is an experimental toolkit for binding **links into images** in safe, creative, and educational ways.  
It explores how images can act as carriers of digital information — without hiding harmful code.  

---

## ✨ Features

- **Clickable Image Links (HTML)**
  - Turn any image into a hyperlink inside a webpage.
  - Outputs lightweight HTML snippets.

- **QR Code Binding**
  - Embed a URL as a QR code overlay on an image.
  - Style options: corner placement, opacity control, or blended watermark.

- **Metadata Binding (EXIF)**
  - Store links inside an image’s EXIF metadata.
  - Supports writing + extracting the hidden link.

- **Educational Steganography (Optional)**
  - Demonstrates hiding text links inside pixel data (least significant bits).
  - Emphasis on *learning about information security concepts*, not malicious use.

---

## 📂 Project Structure

imgvoid/
├── README.md # Project overview
├── requirements.txt # Python dependencies
├── src/
│ ├── html_linker.py # Generate HTML snippets with clickable images
│ ├── qr_binder.py # Overlay QR codes into images
│ ├── exif_binder.py # Hide/retrieve links in EXIF metadata
│ ├── steg_binder.py # (Optional) Simple text steganography for URLs
│ └── utils/
│ └── image_tools.py # Shared helpers (resizing, saving, etc.)
├── examples/
│ ├── input.png
│ ├── output_with_qr.png
│ ├── exif_bound.jpg
│ └── bound.html


---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/imgvoid.git
cd imgvoid
2. Install Dependencies
3. Example Usage
a) HTML Link Binder
