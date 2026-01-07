# 🎨🖼️ HEXIT

### *Instant Color Extraction from Any Image URL*

<p align="center">
  <strong>Drop a URL. Get the colors.</strong><br/>
  A fast, modern, web-based API that extracts dominant colors from any public image.
</p>

---

<div align="center">

![API](https://img.shields.io/badge/API-Live-blue?style=for-the-badge)
![Vercel](https://img.shields.io/badge/Vercel-Deploy-black?logo=vercel)
![JSON](https://img.shields.io/badge/Response-JSON-green)
![License](https://img.shields.io/badge/License-MIT-green.svg)

</div>

---

## ✨ What is HEXIT?

**HEXIT** is a lightweight image color extraction API.  
Send an image URL — receive clean **HEX color codes** ready for UI, theming, and design systems.

No uploads.  
No SDKs.  
No nonsense.

---

## 🚀 API Usage

### Endpoint
```http
GET https://hexit-ky.vercel.app/v2?url=IMAGE_URL
Example Request
http
Copy code
GET https://hexit-ky.vercel.app/v2?url=https://images.unsplash.com/photo-1558591710-4b4a1ae0f04d
Example Response
json
Copy code
{
  "imageUrl": "https://images.unsplash.com/photo-1558591710-4b4a1ae0f04d",
  "colors": [
    "#384350",
    "#788390"
  ]
}
🎯 Use Cases
🎨 Dynamic UI theming

🖼️ Image-based background generation

🧩 Design systems & color palettes

⚡ Frontend color analysis

🧠 Creative tooling & automation
