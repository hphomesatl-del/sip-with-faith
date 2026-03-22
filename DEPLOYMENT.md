# Sip with Faith - Deployment Guide ☕ 🙏

Three easy options to deploy your "Sip with Faith" app to the world:

---

## Option 1: Vercel (Recommended - Easiest) ⭐

**Why Vercel:**
- Free hosting for static sites
- Instant deploys from Git
- Custom domain support
- Extremely fast CDN

### Steps:

1. **Install Vercel CLI:**
   ```bash
   npm install -g vercel
   ```

2. **Deploy from the sip-with-faith folder:**
   ```bash
   cd ~/Desktop/sip-with-faith  # or wherever your folder is
   vercel
   ```

3. **Follow prompts:**
   - Confirm project name: `sip-with-faith`
   - Choose Node.js version (default is fine)
   - Say `yes` to "Want to override settings?"

4. **Your site is live!**
   - URL will be something like: `https://sip-with-faith.vercel.app`
   - Every time you push changes to GitHub, it auto-deploys

---

## Option 2: GitHub Pages (Free, Simple)

**Why GitHub Pages:**
- Built into GitHub
- Free forever
- Works great for static sites

### Steps:

1. **Create GitHub repo:**
   - Go to github.com and create a new repo named `sip-with-faith`

2. **Initialize Git in your folder:**
   ```bash
   cd ~/Desktop/sip-with-faith
   git init
   git add .
   git commit -m "Initial commit: Sip with Faith app"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/sip-with-faith.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to repo settings → Pages
   - Source: `main` branch, `/root` folder
   - Save

4. **Your site is live!**
   - URL: `https://YOUR_USERNAME.github.io/sip-with-faith`

---

## Option 3: Railway or Render (Free Tier)

### Railway (5 min setup)

1. **Go to railway.app and sign in**
2. **Create new project → Deploy from GitHub**
3. **Select your sip-with-faith repo**
4. **Railway auto-deploys**
5. **URL**: railway.app gives you a custom domain

### Render (5 min setup)

1. **Go to render.com and sign in**
2. **Create new Static Site**
3. **Connect GitHub repo**
4. **Render auto-deploys**
5. **URL**: render.app gives you a custom domain

---

## Generate QR Code for Your Live Site

Once deployed, generate a beautiful QR code:

1. **Visit your QR generator page:**
   - `https://your-deployed-url/qr-generator.html`

2. **Default URL is pre-filled** with your deployment URL

3. **Click "Generate QR Code"**

4. **Download as PNG** and use it anywhere:
   - Print for your office
   - Share on social media
   - Email to people
   - Add to marketing materials

---

## Custom Domain (Optional)

Want `sipwithfaith.com` instead of the long URL?

### Via Vercel:
1. Buy domain on Namecheap, GoDaddy, or Google Domains
2. In Vercel project settings → Domains
3. Add your domain and follow DNS instructions

### Via GitHub Pages:
1. Buy domain
2. In repo settings → Pages → Custom Domain
3. Add domain and update DNS records

---

## Update Your Site

Make changes to `index.html` and push:

```bash
cd ~/Desktop/sip-with-faith
git add .
git commit -m "Update verses or design"
git push
```

Your changes deploy automatically within seconds! 🚀

---

## Need Help?

- **Vercel Docs**: https://vercel.com/docs
- **GitHub Pages Guide**: https://pages.github.com
- **Railway Docs**: https://docs.railway.app
- **Render Docs**: https://render.com/docs

---

**Your Sip with Faith app is ready to bless people's days! ☕ 🙏**
