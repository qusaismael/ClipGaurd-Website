# ClipGuard Website

🛡️ **Official website for ClipGuard - Privacy-focused clipboard protection for Linux**

## 📁 Structure

```
website/
├── index.html          # Main landing page
├── privacy.html        # Privacy policy page
├── css/
│   └── styles.css      # All styles and animations
├── js/
│   └── main.js         # Interactive functionality
├── images/             # Image assets (add screenshots, logos here)
├── assets/             # Additional assets
├── robots.txt          # Search engine directives
├── sitemap.xml         # SEO sitemap
├── .htaccess           # Apache server configuration
├── DEPLOYMENT.md       # Deployment instructions
└── README.md           # This file
```

## 🚀 Quick Start

### Local Development

1. **Clone the repository:**
   ```bash
   cd ClipGuard/website
   ```

2. **Start a local server:**
   
   **Option A - Python:**
   ```bash
   python3 -m http.server 8000
   ```
   
   **Option B - Node.js (npx):**
   ```bash
   npx serve .
   ```
   
   **Option C - PHP:**
   ```bash
   php -S localhost:8000
   ```

3. **Open browser:**
   ```
   http://localhost:8000
   ```

### Deploy to Production

See [DEPLOYMENT.md](DEPLOYMENT.md) for comprehensive deployment instructions covering:
- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Traditional hosting (Apache/Nginx)

## ✨ Features

### Design
- 🎨 Modern, gradient hero section
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth animations and transitions
- 🌙 Clean, professional UI
- 🖥️ Animated terminal demo

### Functionality
- 📋 One-click code copying
- 🔗 Smooth scrolling navigation
- 📱 Mobile hamburger menu
- 🎯 Intersection observer animations
- 🎮 Easter egg (try the Konami code!)

### SEO
- ✅ Semantic HTML5
- ✅ Meta tags (OpenGraph, Twitter Cards)
- ✅ Sitemap.xml
- ✅ robots.txt
- ✅ Fast page load
- ✅ Accessible (ARIA labels)

### Security
- 🔒 Security headers configured
- 🔒 HTTPS enforcement (in .htaccess)
- 🔒 XSS protection
- 🔒 Clickjacking prevention
- 🔒 Content Security Policy

## 🛠️ Customization

### Update GitHub Links
Replace `qusaismael` with your actual GitHub username in:
- `index.html` (multiple locations)
- `privacy.html`

### Add Screenshots
1. Create screenshots of ClipGuard in action
2. Save to `images/` folder
3. Reference in HTML:
   ```html
   <img src="images/screenshot1.png" alt="ClipGuard in action">
   ```

### Change Colors
Edit CSS variables in `css/styles.css`:
```css
:root {
    --primary-color: #3498db;    /* Main brand color */
    --secondary-color: #2ecc71;  /* Success/highlights */
    --dark: #2c3e50;             /* Text color */
    /* ... more variables ... */
}
```

## 📊 Browser Support

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+
- ✅ Opera 76+

## 🤝 Contributing

Improvements welcome! To contribute:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📝 License

This website is part of the ClipGuard project and shares the same MIT License.

## 🙏 Credits

Built with:
- HTML5, CSS3, JavaScript (ES6+)
- Google Fonts (system fonts for performance)
- No frameworks (pure vanilla JS)
- SVG graphics

## 📞 Support

- 🐛 [Report Issues](https://github.com/qusaismael/ClipGuard/issues)
- 💬 [Discussions](https://github.com/qusaismael/ClipGuard/discussions)
- 📖 [Documentation](https://github.com/qusaismael/ClipGuard#readme)

---

Made with ❤️ for privacy-conscious Linux users

