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


---

<h2 align="center">Main Features</h2>

<div align="center" style="max-width:1000px;margin:0 auto;">
  <div style="display:flex;flex-wrap:wrap;justify-content:center;gap:18px;padding:12px;">

    <!-- Card 1 -->
    <div style="background:#ffffff;border-radius:12px;padding:18px;width:280px;box-shadow:0 6px 20px rgba(20,30,60,0.08);text-align:left;">
      <div style="display:flex;align-items:center;gap:12px;margin-bottom:10px">
        <svg width="34" height="34" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M3 12h18" stroke="#2B6CB0" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
          <path d="M12 3v18" stroke="#2B6CB0" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        <strong style="font-size:16px;color:#0f1724">Clickable Image Links (HTML)</strong>
      </div>
      <p style="margin:0;color:#334155;font-size:13px;line-height:1.4">
        Generate lightweight HTML snippets that turn any image into a clickable link — ideal for demos, docs, and landing pages.
      </p>
    </div>

    <!-- Card 2 -->
    <div style="background:#ffffff;border-radius:12px;padding:18px;width:280px;box-shadow:0 6px 20px rgba(20,30,60,0.08);text-align:left;">
      <div style="display:flex;align-items:center;gap:12px;margin-bottom:10px">
        <svg width="34" height="34" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect x="3" y="3" width="18" height="18" rx="3" stroke="#16A34A" stroke-width="2"/>
          <path d="M8 8h.01M16 8h.01M8 16h.01M16 16h.01" stroke="#16A34A" stroke-width="2" stroke-linecap="round"/>
        </svg>
        <strong style="font-size:16px;color:#0f1724">QR Code Binding</strong>
      </div>
      <p style="margin:0;color:#334155;font-size:13px;line-height:1.4">
        Overlay scannable QR codes onto images with configurable size, placement, and transparency for user-friendly linking.
      </p>
    </div>

    <!-- Card 3 -->
    <div style="background:#ffffff;border-radius:12px;padding:18px;width:280px;box-shadow:0 6px 20px rgba(20,30,60,0.08);text-align:left;">
      <div style="display:flex;align-items:center;gap:12px;margin-bottom:10px">
        <svg width="34" height="34" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M12 2v20M2 12h20" stroke="#F59E0B" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        <strong style="font-size:16px;color:#0f1724">EXIF Metadata Storage</strong>
      </div>
      <p style="margin:0;color:#334155;font-size:13px;line-height:1.4">
        Write and retrieve URLs stored safely in image EXIF fields. Useful for tagging images with descriptive links or resources.
      </p>
    </div>

    <!-- Card 4 -->
    <div style="background:#ffffff;border-radius:12px;padding:18px;width:280px;box-shadow:0 6px 20px rgba(20,30,60,0.08);text-align:left;">
      <div style="display:flex;align-items:center;gap:12px;margin-bottom:10px">
        <svg width="34" height="34" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <path d="M4 7h16M4 12h16M4 17h16" stroke="#7C3AED" stroke-width="2" stroke-linecap="round"/>
        </svg>
        <strong style="font-size:16px;color:#0f1724">Educational Steganography</strong>
      </div>
      <p style="margin:0;color:#334155;font-size:13px;line-height:1.4">
        A safe demo showing how text (e.g., a URL) can be embedded into pixel data — for learning the basics of data hiding.
      </p>
    </div>

    <!-- Card 5 -->
    <div style="background:#ffffff;border-radius:12px;padding:18px;width:280px;box-shadow:0 6px 20px rgba(20,30,60,0.08);text-align:left;">
      <div style="display:flex;align-items:center;gap:12px;margin-bottom:10px">
        <svg width="34" height="34" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <circle cx="12" cy="12" r="9" stroke="#0EA5E9" stroke-width="2"/>
          <path d="M9 12l2 2 4-4" stroke="#0EA5E9" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/>
        </svg>
        <strong style="font-size:16px;color:#0f1724">Batch Processing</strong>
      </div>
      <p style="margin:0;color:#334155;font-size:13px;line-height:1.4">
        (Planned) Apply bindings or extractions across folders of images — great for bulk documentation or asset pipelines.
      </p>
    </div>

    <!-- Card 6 -->
    <div style="background:#ffffff;border-radius:12px;padding:18px;width:280px;box-shadow:0 6px 20px rgba(20,30,60,0.08);text-align:left;">
      <div style="display:flex;align-items:center;gap:12px;margin-bottom:10px">
        <svg width="34" height="34" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect x="3" y="6" width="18" height="12" rx="2" stroke="#EF4444" stroke-width="2"/>
          <path d="M8 10h8M8 14h4" stroke="#EF4444" stroke-width="2" stroke-linecap="round"/>
        </svg>
        <strong style="font-size:16px;color:#0f1724">Open & Extensible</strong>
      </div>
      <p style="margin:0;color:#334155;font-size:13px;line-height:1.4">
        Clear Python scripts and helpers make extension easy — plug in new binding techniques or UI frontends.
      </p>
    </div>

  </div>
</div>

<hr/>


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
