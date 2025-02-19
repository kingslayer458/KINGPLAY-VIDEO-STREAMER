
# 🎬 KingPlay Video Streamer

A modern video streaming platform prototype with cinematic visuals and smooth animations. Built for movie enthusiasts!

## ✨ Features

- 🎥 Auto-playing hero section with cinematic trailer
- 🌓 Smart dark/light mode toggle
- 📱 Fully responsive design
- 🎬 Movie poster hover animations
- 🔍 Interactive search functionality
- 📺 Dynamic feature tabs
- 🖼️ HD quality indicators
- 🎞️ Smooth page transitions

## 🚀 Quick Start

1. Clone the repository:
```bash
git clone https://github.com/yourusername/kingplay-streamer.git
cd kingplay-streamer
```

2. Open in browser:
```bash
open index.html  # Or double-click the file
```
# For Electron desktop app
```
npm install
npm start
```

### Prerequisites
- AWS Account (for production deployment)
- Node.js 16+ (for Electron build)
  
## 🎮 Usage

1. **Toggle Theme**  
   Click the sun/moon icon in top-right to switch between dark/light modes

2. **Browse Movies**  
   Hover over movie posters for zoom effect  
   Click posters to watch movies

3. **Explore Features**  
   Click through different content tabs (Movies, TV Shows, Originals)

4. **Responsive Design**  
   Resize browser or view on mobile devices for adaptive layout

## 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Electron.js](https://img.shields.io/badge/Electron-191970?style=for-the-badge&logo=Electron&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)


- **Font Awesome Icons**  
- **Google Fonts**  
- **Cloud-hosted Videos**  

## 🎨 UI/UX Highlights

### 🌓 Dark Mode Magic
```css
body.dark-mode {
  background: #0a0a0a;
  color: #fff;
  transition: all 0.5s ease;
}
```
Smooth color transitions with CSS animations

### 🎥 Cinematic Hero Section
Auto-playing fullscreen background video with overlay text

### 🎬 Movie Grid Animation
```css
.movies-img:hover {
  transform: scale(1.05);
  box-shadow: 0 10px 20px rgba(0,0,0,0.3);
}
```
Hover effects with scale transformation and shadow

### 📱 Mobile-First Design
```css
@media (max-width: 768px) {
  .menu {
    display: none;
  }
  .menu-btn {
    display: block;
  }
}
```
Responsive hamburger menu for mobile devices

## 📸 Screenshots

| Light Mode | Dark Mode |
|------------|-----------|
| ![Light Mode](LIGHT.png) | ![Dark Mode](DARK.png) |

| dashboard | streaming |
|------------|-----------|
| ![dashboard](d.png) | ![streaming](s.png) |

## 🌟 Contributing

Found a bug? Have a feature idea? Contributions welcome!
1. Fork the project
2. Create your branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

Distributed under MIT License. See `LICENSE` for more information.

## ⚠️ Disclaimer

This project is for educational purposes only. Movie assets are used as placeholders. Please replace with licensed content for production use.

---

Made with ❤️ by [C MANOJ KUMAR] | [Live Demo](#) | [Report Bug](#)


