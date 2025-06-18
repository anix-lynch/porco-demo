# Porco Gallery 🎨

A modern, responsive portfolio gallery showcasing projects in an Airtable-style layout. Built for rapid deployment and demo purposes.

## 🚀 Live Demo

**GitHub Pages:** [https://anix-lynch.github.io/porco-demo/](https://anix-lynch.github.io/porco-demo/)

## ✨ Features

- 📱 **Responsive Design** - Works perfectly on all devices
- 🎨 **Modern UI** - Clean, professional interface with smooth animations  
- 📊 **Project Showcase** - Airtable-style cards displaying tech stacks
- 🐳 **Docker Ready** - Complete containerization setup included
- ⚡ **Lightning Fast** - Optimized for performance

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript
- **Styling:** CSS Grid, Flexbox, CSS Animations
- **Deployment:** Docker, GitHub Pages, Vercel Ready
- **Performance:** Optimized assets, lazy loading

## 🐳 Docker Deployment

### Quick Start
```bash
# Build and run with Docker
./deploy.sh

# Or manually:
docker build -t porco-gallery .
docker run -p 8080:80 porco-gallery
```

Access at: `http://localhost:8080`

## 🌐 Deployment Options

### GitHub Pages (Free)
1. Fork this repository
2. Enable GitHub Pages in Settings
3. Select `main` branch as source
4. Your site will be live!

### Vercel (Free)
```bash
npx vercel --prod
```

### Railway ($5/month cap)
1. Connect GitHub repository
2. Deploy with Docker
3. Unlimited deploys within budget

---

**⭐ Star this repo if it helped you build something awesome!**