# Sumit Dhiman - Portfolio Website

[![Live Website](https://img.shields.io/badge/Live-Website-blue?style=for-the-badge)](https://sumitdh.com)
[![Microsoft MVP](https://img.shields.io/badge/Microsoft-MVP-orange?style=for-the-badge)](https://mvp.microsoft.com)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

> A modern, responsive portfolio website showcasing my journey as a Microsoft MVP, IT Systems Administrator, and AI Data Trainer.

## ✨ Features

### 🎨 **Modern Design**
- **Glassmorphism UI**: Beautiful glass-like cards and elements with backdrop blur effects
- **Animated Backgrounds**: Dynamic geometric patterns in hero and footer sections
- **Responsive Layout**: Fully optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Intersection Observer-based scroll animations and hover effects

### 🚀 **Interactive Elements**
- **Dynamic Navigation**: Scrolled state with color changes and smooth transitions
- **Typing Animation**: Animated hero title with wave emoji
- **Counter Animation**: Animated statistics in the About section
- **Parallax Effects**: Subtle parallax scrolling in the hero section
- **Loading Screen**: Professional loading animation on page load

### 📱 **Mobile-First**
- **Hamburger Menu**: Responsive navigation for mobile devices
- **Touch-Friendly**: Optimized for touch interactions
- **Progressive Enhancement**: Works perfectly across all screen sizes

### 🔧 **Performance Optimized**
- **Intersection Observer**: Efficient scroll-based animations
- **CSS Animations**: Hardware-accelerated transitions and effects
- **Image Fallbacks**: Graceful handling of missing images with custom placeholders
- **Smooth Scrolling**: Native CSS smooth scrolling with JavaScript fallbacks

## 🛠️ **Tech Stack**

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic markup and structure |
| **CSS3** | Modern styling with Flexbox, Grid, and animations |
| **JavaScript (ES6+)** | Interactive functionality and animations |
| **Font Awesome** | Professional icons |
| **Google Fonts** | Inter font family for modern typography |

## 📂 **Project Structure**

```
Sumitdh.com/
├── index.html                 # Main HTML file
├── site.webmanifest          # PWA manifest
├── README.md                 # Project documentation
├── assets/
│   ├── styles/
│   │   └── styles.css        # Main stylesheet with animations
│   ├── scripts/
│   │   └── script.js         # JavaScript functionality
│   └── icons/               # Favicons and images
│       ├── favicon.ico
│       ├── favicon16.png
│       ├── favicon32.png
│       ├── favicon180.png
│       ├── sumit.jpg
│       ├── about.png
│       ├── ywg.png
│       ├── icon-browser.png
│       └── icon-archive.png
```

## 🎯 **Key Sections**

### 🏠 **Hero Section**
- Personal introduction with animated background
- Professional title and key achievements
- Call-to-action buttons
- Social media links
- Profile card with availability status

### 👨‍💻 **About Me**
- Professional summary
- Animated statistics (60K+ cases, 3 MVP awards, 30K+ views)
- Key achievements and background

### 📄 **Resume**
- Education and certifications
- Professional highlights grid
- Work experience timeline

### 🛠️ **Skills**
- Categorized skill sets
- Microsoft Technologies
- Technical Support
- AI & Data
- System Administration

### 💼 **Projects**
- Your Windows Guide (Tech Blog)
- Browser Sticky Notes (Chrome Extension)
- Open Internet Archive (Web Extension)

### 🎯 **Experience**
- Interactive timeline with centered markers
- Microsoft MVP & Community Leader
- AI Data Specialist
- Systems Administrator

### 📞 **Contact**
- Contact form with validation
- Social media links
- Professional contact information

## 🚀 **Getting Started**

### Prerequisites
- Modern web browser
- Local web server (optional for development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sumitdhiman/Sumitdh.com.git
   cd Sumitdh.com
   ```

2. **Open in browser**
   ```bash
   # Option 1: Direct file opening
   open index.html
   
   # Option 2: Local server (recommended)
   python -m http.server 8000
   # or
   npx serve .
   ```

3. **View the website**
   Navigate to `http://localhost:8000` if using a local server

## 🎨 **Customization**

### **Colors**
The website uses a modern color palette. Main colors can be customized in `styles.css`:

```css
:root {
  --primary-blue: #2563eb;
  --primary-purple: #7c3aed;
  --accent-gold: #fbbf24;
  --text-dark: #22223b;
  --background-light: #f8fafc;
}
```

### **Animations**
All animations can be controlled via CSS variables and JavaScript settings:

- **Scroll animations**: Modify `observerOptions` in `script.js`
- **Background patterns**: Adjust keyframes in `styles.css`
- **Transition durations**: Update CSS transition properties

### **Content**
Update personal information in:
- `index.html` - All text content and links
- `site.webmanifest` - PWA settings
- `assets/icons/` - Replace with your images

## 🌟 **Key Features Implemented**

### ✅ **Recently Added**
- [x] Glassmorphism bubbles background animation
- [x] Animated geometric patterns in hero and footer
- [x] Centered timeline markers for better visual balance
- [x] Dynamic navbar with scroll-based color changes
- [x] Loading screen with spinner animation
- [x] Scroll-to-top button with hover effects
- [x] Image fallback system with custom placeholders
- [x] Counter animations for statistics
- [x] Parallax effects in hero section

### 🔧 **Performance Features**
- [x] Intersection Observer for efficient animations
- [x] Hardware-accelerated CSS animations
- [x] Optimized image loading
- [x] Smooth scrolling implementation
- [x] Responsive design optimization

## 📱 **Browser Support**

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Full Support |
| Firefox | 88+ | ✅ Full Support |
| Safari | 14+ | ✅ Full Support |
| Edge | 90+ | ✅ Full Support |

## 🤝 **Contributing**

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 **Contact**

**Sumit Dhiman** - Microsoft MVP & IT Systems Administrator

- 🌐 Website: [sumitdh.com](https://sumitdh.com)
- 📧 Email: sumit@yourwindowsguide.com
- 💼 LinkedIn: [@sumitdhmn](https://linkedin.com/in/sumitdhmn)
- 🐙 GitHub: [@Sumitdhiman](https://github.com/Sumitdhiman)
- 🐦 Twitter: [@_sumitdh](https://twitter.com/_sumitdh)
- 📝 Blog: [Your Windows Guide](https://yourwindowsguide.com)

## 🙏 **Acknowledgments**

- Font Awesome for beautiful icons
- Google Fonts for the Inter font family
- Microsoft Community for the amazing support platform
- All the developers who inspired the design and functionality

---

<div align="center">
  <strong>Built with ❤️ and lots of ☕</strong><br>
  © 2025 Sumit Dhiman. All rights reserved.
</div>