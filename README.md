# Sip with Faith ☕ 🙏

A beautiful, inspirational web app that delivers random Bible verses from the top 100 most-searched passages.

## Features

✨ **100 Top-Searched Bible Verses** — Curated collection of the most meaningful passages
📱 **Mobile Responsive** — Works perfectly on phones, tablets, and desktops
🎯 **Smart Randomization** — Never repeats the same verse (except 1% chance)
📖 **Full Verses + References** — Complete text and scripture location
✨ **Beautiful UI** — Modern gradient design with smooth interactions
🔄 **One-Click Refresh** — Get a new verse instantly
📊 **Verse Counter** — Track your position in the rotation

## Quick Start

### Local Development
```bash
cd sip-with-faith
python3 -m http.server 8000
```
Then visit: `http://localhost:8000`

### Deployment

#### Option 1: Vercel (Free & Recommended)
```bash
npm install -g vercel
vercel
```

#### Option 2: GitHub Pages
1. Push to GitHub: `git push origin main`
2. Enable GitHub Pages in repository settings
3. URL: `https://yourusername.github.io/sip-with-faith`

#### Option 3: Railway/Render
Simple web hosting services that support static HTML:
- Railway: https://railway.app
- Render: https://render.com
- Both support free tier for static sites

## QR Code Generation

Use any QR code generator to create a code linking to your deployed URL:
- **Google Charts API**: `https://chart.googleapis.com/chart?chs=300x300&chld=L|1&cht=qr&chl=[YOUR_URL]`
- **QR Code Generator**: https://www.qr-code-generator.com
- **CLI**: `qrencode -o qrcode.png "https://your-url.com"`

**Example:**
```
https://chart.googleapis.com/chart?chs=300x300&chld=L|1&cht=qr&chl=https://sip-with-faith.vercel.app
```

## Customization

### Add More Verses
Edit `index.html` and add to the `topVerses` array:
```javascript
const topVerses = [
    { text: "Your verse text here...", ref: "Book Chapter:Verse" },
    // Add more verses
];
```

### Change Colors
Update the CSS gradient colors in `<style>`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

## License

MIT — Free to use and modify for personal or commercial projects.

---

**Created with ❤️ for daily inspiration**
