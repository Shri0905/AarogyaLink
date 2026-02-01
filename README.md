# Aarogya Link - Anemia Screening Tool

![Version](https://img.shields.io/badge/version-2.0.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![PWA](https://img.shields.io/badge/PWA-enabled-purple)

A progressive web application for anemia risk screening designed for women aged 15-49 in India.

## ✨ Features

- 🌍 **Multi-language Support**: English, Hindi, and Marathi
- 📱 **PWA Enabled**: Install as a mobile app, works offline
- 🌙 **Dark Mode**: Reduces eye strain
- ✅ **Smart Validation**: Prevents incomplete submissions
- 🛡️ **Error Boundaries**: Graceful error handling
- ⚡ **Loading States**: Professional user feedback
- 📊 **Analytics**: Google Analytics integration
- 🔒 **Privacy-First**: All data stays on user's device

## 🚀 Live Demo

[View Live Site](https://your-site-name.netlify.app)

## 📁 Project Structure

```
aarogya-link/
├── index.html              # Main application file
├── manifest.json           # PWA manifest
├── sw.js                   # Service worker
├── icon-192.png           # App icon (192x192)
├── icon-512.png           # App icon (512x512)
└── README.md              # This file
```

## 🛠️ Installation

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- HTTPS hosting (for PWA features)

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/aarogya-link.git
cd aarogya-link
```

2. Serve locally (Python):
```bash
python -m http.server 8000
```

3. Open browser:
```
http://localhost:8000
```

### Deploy to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy)

Or manually:
1. Push code to GitHub
2. Connect repository to Netlify
3. Deploy automatically

## 📱 PWA Installation

### Android (Chrome):
1. Visit the site
2. Tap "Add to Home Screen" banner
3. App installs on home screen

### iOS (Safari):
1. Visit the site
2. Tap Share button
3. Tap "Add to Home Screen"

## 🎨 Customization

### Change Theme Colors
Edit CSS variables in `index.html`:
```css
:root {
  --header-gradient-1: #455a64;
  --header-gradient-2: #607d8b;
}
```

### Update Analytics
Replace Google Analytics ID in `index.html`:
```javascript
gtag('config', 'YOUR-GA-ID');
```

## 🤝 Contributing

Developed by **The Rotaract Club of D.Y. Patil School of Biotechnology and Bioinformatics**, Navi Mumbai.

### Contributors
- Zone 1, RID 3142
- Community Health Initiative

## 📄 License

MIT License - feel free to use this for community health initiatives.

## 🔗 Resources

- [Anemia Mukt Bharat](https://anemiamuktbharat.info/)
- [NFHS-5 Report](http://rchiips.org/nfhs/)
- [WHO Anemia Guidelines](https://www.who.int/health-topics/anaemia)

## 📞 Support

For questions or support:
- National Health Helpline: 104
- Women Helpline: 1091
- Emergency: 108

## 🙏 Acknowledgments

- World Health Organization (WHO)
- Ministry of Health & Family Welfare, India
- Anemia Mukt Bharat Program
- All community health workers

---

**Made with ❤️ for women's health in India**
