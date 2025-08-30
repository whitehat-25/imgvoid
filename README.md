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

📝 Metadata Injection (Extended)  
Instead of relying only on EXIF, you can also inject links into **IPTC** or **XMP metadata fields**, which are more flexible.  
Tools like `exiftool` allow safe embedding and retrieval.  

**Example with exiftool:**  
```bash
# Embed a link
exiftool -Comment="https://example.com/hidden" sample.jpg  

# Extract it back
exiftool sample.jpg | grep Comment

✅ Great for demonstrations of how invisible text can live in images.
⚠️ Note: Some platforms strip metadata when compressing/re-uploading (e.g., social media).

🎨 Steganography Demo
Steganography hides data inside images at the pixel level.
Our implementation is simple and educational, meant to demonstrate the concept without strong obfuscation.
✅ Excellent for students exploring cybersecurity basics.
⚠️ Not meant for real-world secure communication.
💡 Example use: Show how even a simple image can “carry” a hidden short link.

📦 EOF Appending Method
Another approach is to append data after the end-of-file marker in an image.
Image viewers ignore everything after the EOF, so the picture looks normal while still containing extra data.

Example (Linux command):

# Append link after PNG file
echo "https://example.com/hidden" >> sample.png

To extract later:

strings sample.png | tail

✅ Works with PNG/JPEG and keeps the image visually unchanged.
⚠️ Easy to spot with hex editors, and some file validators may reject such images.
💡 Example use: Teaching file structure basics in cybersecurity workshops.

🛠️ Utilities
A set of small helper functions to:

    Resize images without distortion

    Save and export in multiple formats

    Handle conversions automatically

✅ This makes the workflow smooth, so you can focus on experiments instead of boilerplate code.


---

This way, your repo will now clearly show **5 unique binding methods**:
- HTML Wrappers  
- QR Overlays  
- Metadata Injection (EXIF/IPTC/XMP)  
- Steganography (LSB demo)  
- EOF Appending  
