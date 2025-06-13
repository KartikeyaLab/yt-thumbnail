# YouTube Thumbnail Downloader

A sleek, privacy-focused web application for downloading YouTube video thumbnails in the highest available resolution. Built with vanilla HTML, CSS (Tailwind), and JavaScript.

🔗 **Live Demo**: [https://kartikeyalab.github.io/yt-thumbnail/](https://kartikeyalab.github.io/yt-thumbnail/)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?logo=tailwind-css&logoColor=white)

## ✨ Features

- **🚀 Instant Downloads** - Get YouTube thumbnails in seconds
- **🎯 High Resolution** - Automatically fetches the highest available quality (up to 1280×720)
- **🔒 Privacy-First** - Everything runs client-side, no data stored
- **📱 Responsive Design** - Works on desktop and mobile
- **⚡ Zero Dependencies** - Pure vanilla JavaScript
- **🚫 Ad-Free** - Clean, distraction-free interface

## 🎯 Supported Formats

- Full YouTube URLs: `https://www.youtube.com/watch?v=dQw4w9WgXcQ`
- Shortened URLs: `https://youtu.be/dQw4w9WgXcQ`
- Direct Video IDs: `dQw4w9WgXcQ`

## 🚀 Quick Start

### Use Online
Visit [https://kartikeyalab.github.io/yt-thumbnail/](https://kartikeyalab.github.io/yt-thumbnail/) and start downloading thumbnails immediately.

### Run Locally
```bash
git clone https://github.com/KartikeyaLab/yt-thumbnail.git
cd yt-thumbnail
# Open index.html in your browser or use a local server
python -m http.server 8000
```

## 💻 How It Works

1. **Enter** a YouTube URL or video ID
2. **Preview** the highest quality thumbnail available
3. **Download** with a single click

The app tries multiple resolutions in order:
- `maxresdefault.jpg` (1280×720)
- `sddefault.jpg` (640×480)  
- `hqdefault.jpg` (480×360)
- `mqdefault.jpg` (320×180)
- `default.jpg` (120×90)

## 🏗️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS (CDN)
- **Typography**: Inter font
- **Deployment**: GitHub Pages

## 🔧 Customization

The app uses CSS custom properties for easy theming:

```css
/* Dark theme with glassmorphism effects */
background: radial-gradient(circle at top left, #111 0%, #000 100%);
backdrop-filter: blur(12px);
```

## 🤝 Contributing

Contributions welcome! Please:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

### Development Guidelines
- Keep it dependency-free
- Maintain privacy-first approach
- Test across browsers
- Follow existing code style

## 🐛 Troubleshooting

**"Invalid YouTube URL or ID"**
- Check the URL format
- Try using just the video ID
- Ensure the video exists and is public

**"Could not load any thumbnail"**
- Video might be private or deleted
- Try a different video to test

## 📄 License

MIT License - see [LICENSE](LICENSE) for details.

## 👨‍💻 Author

**Kartikeya**
- GitHub: [@KartikeyaLab](https://github.com/KartikeyaLab)
- Email: kartikeya30062009@gmail.com

---

<div align="center">
  <p>⭐ Star this repo if you find it useful!</p>
  <p><a href="https://kartikeyalab.github.io/yt-thumbnail/">Try it now</a></p>
</div>
