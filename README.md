# imgvoid

**imgvoid** is an experimental toolkit that demonstrates how images can safely act as carriers of digital information.  
Designed for **educational and creative purposes**, it provides multiple methods to bind URLs into images without hiding harmful code.  

With support for **clickable HTML wrappers**, **QR code overlays**, and **EXIF metadata storage**, imgvoid shows practical techniques for linking visuals to external resources.  
It also includes a **simple steganography demo** to illustrate how data can be embedded in pixel structures.  

This project is ideal for **students, educators, and researchers** exploring digital watermarking, steganography basics, and creative uses of image-based information sharing.  

---

<p align="center">
  <img src="https://github.com/whitehat-25/imgvoid/blob/main/imgvoid-wide.png" alt="imgvoid Logo" width="320"/>
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

---

## ✨ Main Features  

<p align="center">
  <table>
    <tr>
      <td><b>🔗 HTML Link Binder</b></td>
      <td>Wrap images in safe clickable HTML snippets that open URLs directly.</td>
    </tr>
    <tr>
      <td><b>📷 QR Code Binder</b></td>
      <td>Overlay QR codes inside images so links can be scanned easily.</td>
    </tr>
    <tr>
      <td><b>🖼 EXIF Metadata Binder</b></td>
      <td>Store and retrieve links safely inside image metadata fields.</td>
    </tr>
    <tr>
      <td><b>🎨 Steganography Demo</b></td>
      <td>A simple proof-of-concept showing how text can hide inside pixel data (educational only).</td>
    </tr>
    <tr>
      <td><b>⚡ Easy-to-Use CLI</b></td>
      <td>Run scripts quickly with Python to generate bound images in seconds.</td>
    </tr>
    <tr>
      <td><b>📚 Educational Toolkit</b></td>
      <td>Perfect for workshops, research, or teaching digital watermarking concepts.</td>
    </tr>
  </table>
</p>

---
📖 Detailed Feature Descriptions
🖼️ Clickable HTML Wrappers

This method creates a small HTML file that wraps an image inside an <a> tag.
When clicked, the image redirects the user to the desired URL.
✅ Perfect for web demos, teaching beginners about hyperlinks, or making visual buttons.
💡 Example use: Creating an educational page where each image leads to a cybersecurity resource.

📱 QR Code Overlays

QR codes are visible, accessible, and secure — everyone knows what they are.
This feature generates a QR code for a given link and overlays it on top of your chosen image.
✅ Great for posters, digital flyers, or research demos.
💡 Example use: Embedding a QR code to your GitHub repo inside your project logo.

📷 EXIF Metadata Binder

Most image formats (like JPEG) support metadata tags.
imgvoid can safely store links inside the EXIF fields (e.g., ImageDescription).
The image looks normal, but tools (or Python scripts) can read back the embedded link.
✅ Useful for teaching metadata awareness in digital forensics or photography courses.
💡 Example use: Adding attribution links inside images for academic research.

🎨 Steganography Demo

Steganography hides data inside images at the pixel level.
Our implementation is simple and educational, meant to demonstrate the concept without strong obfuscation.
✅ Excellent for students exploring cybersecurity basics.
⚠️ Not meant for real-world secure communication.
💡 Example use: Show how even a simple image can “carry” a hidden short link.

🛠️ Utilities

A set of small helper functions to:

Resize images without distortion

Save and export in multiple formats

Handle conversions automatically

✅ This makes the workflow smooth, so you can focus on experiments instead of boilerplate code.

## 📂 Project Structure

imgvoid/
├── README.md # Project overview
├── requirements.txt # Python dependencies
├── src/
│ ├── html_linker.py # Generate HTML snippets with clickable images
│ ├── qr_binder.py # Overlay QR codes into images
│ ├── exif_binder.py # Hide/retrieve links in EXIF metadata
│ ├── steg_binder.py # (Optional) Simple text steganography demo
│ └── utils/
│ └── image_tools.py # Shared helpers (resizing, saving, etc.)
├── examples/
│ ├── input.png
│ ├── output_with_qr.png
│ ├── exif_bound.jpg
│ └── bound.html
