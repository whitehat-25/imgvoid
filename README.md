# imgvoid

**imgvoid**  is an experimental toolkit that demonstrates how images can safely act as carriers of digital information. Designed for educational and creative purposes, it provides multiple methods to bind URLs into images without hiding harmful code. With support for clickable HTML wrappers, QR code overlays, and EXIF metadata storage, imgvoid shows practical techniques for linking visuals to external resources. It also includes a simple steganography demo to illustrate how data can be embedded in pixel structures. This project is ideal for students, educators, and researchers exploring digital watermarking, steganography basics, and creative uses of image-based information sharing.

<p align="center">
  <img src="examples/output_with_qr.png" alt="imgvoid Logo" width="300"/>
  <br/><br/>
  <small>🔗 Bind links into images in safe, creative, and educational ways</small>
  <br/><br/>
  <a href="https://github.com/yourusername/imgvoid" target="_blank" title="Star imgvoid on GitHub">
    ⭐ Star this project
  </a>
  &nbsp; | &nbsp;
  <a href="https://discord.gg/btZpkp45gQ" target="_blank" title="Join our community!">
    <img src="https://dcbadge.limes.pink/api/server/btZpkp45gQ" alt="Join our Discord"/>
  </a>
</p>

<hr/>


--


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
