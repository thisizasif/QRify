# QRify | Online QR Code Scanner

![QRify Banner](https://github.com/thisizasif/QRify/blob/main/QRify.png?raw=true)

[![Live Demo](https://img.shields.io/badge/🌐_Live_Demo-0099ff?style=for-the-badge)](https://thisizasif.github.io/qrify)
[![MIT License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/thisizasif/qrify?style=for-the-badge)](https://github.com/thisizasif/qrify/stargazers)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge)](https://makeapullrequest.com)

## 📱 About

QRify is a lightweight, privacy-focused QR code scanner that works directly in your browser. No apps to download, no data uploaded to servers. Scan QR codes using your camera or upload images.

## ✨ Features

- **Real-time camera scanning** - Point and scan instantly
- **Image upload** - Scan QR codes from photos
- **Smart content detection** - Automatically identifies URLs, emails, contacts
- **Multi-camera support** - Switch between front and back cameras
- **Scan history** - Keep track of previously scanned codes
- **Quick actions** - Copy, save, or search decoded content
- **100% private** - All processing happens locally in your browser

## 🚀 Quick Start

1. **Visit** [qrify.thisizasif.com](https://thisizasif.github.io/qrify)
2. **Allow camera access** when prompted
3. **Point camera** at QR code
4. **View results** instantly

## 📸 How to Use

### Camera Scanning
```javascript
// Allow camera access
await navigator.mediaDevices.getUserMedia({
    video: { facingMode: "environment" }
});
```

### Upload Image
1. Click "Upload QR Image"
2. Select image file
3. View decoded content

## 🛠 Tech Stack

- **HTML5** - Structure and semantics
- **CSS3** - Responsive design
- **JavaScript** - Camera API and processing
- **jsQR Library** - QR code detection
- **Font Awesome** - Icons
- **Google Fonts** - Typography

## 📁 Project Structure

```
qrify/
├── index.html
├── style.css
├── script.js
├── README.md
├── LICENSE
└── .gitignore
```

## 🚀 Deployment

```bash
# Clone repository
git clone https://github.com/thisizasif/qrify.git

# Open in browser
open index.html
```

**Host on:**
- GitHub Pages
- Netlify
- Vercel
- Any static hosting

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch:
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add amazing feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/amazing-feature
   ```
5. Open a Pull Request

## 📄 License

MIT License © 2023 thisizasif

See [LICENSE](LICENSE) for details.

## 👨‍💻 Author

**thisizasif**

- 🌐 Portfolio: [thisizasif.com](https://thisizasif.github.io)
- 🐙 GitHub: [@thisizasif](https://github.com/thisizasif)
- 🐦 Twitter: [@thisizasif](https://twitter.com/thisizasif)

## 🔗 Related Projects

- **[Txtify](https://github.com/thisizasif/txtify)** - Text to TXT file converter
- **QRify** - QR code scanner (this project)

## 📱 Browser Support

| Browser | Status |
|---------|--------|
| Chrome  | ✅ Full support |
| Firefox | ✅ Full support |
| Safari  | ⚠️ Limited (iOS restrictions) |
| Edge    | ✅ Full support |

## 🛡 Privacy

- All processing happens locally in your browser
- No data sent to any server
- Camera access only when needed
- No tracking or analytics

---

<div align="center">

**Made with ❤️ by [thisizasif](https://thisizasif.com)**

⭐ **If QRify helps you, please give it a star!**

</div>
