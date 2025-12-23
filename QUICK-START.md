# ReguMe Website - Quick Start Guide

**Updated:** December 22, 2025  
**Brand:** Coral & Peach (Matches iOS App) 🔥🍑

---

## 🎨 Brand Colors At-A-Glance

```css
/* Copy-paste these anywhere you need brand colors */
Coral Burst:  #E86842  /* Primary CTA color */
Light Peach:  #FFF4EC  /* Main background */
Pure White:   #FFFFFF  /* Card backgrounds */
Charcoal:     #1E1F22  /* Text color */
```

---

## 🚀 Development Commands

```bash
# Install dependencies
npm install

# Start development server (http://localhost:4321)
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

---

## 📁 Project Structure

```
Regumeweb/
├── src/
│   ├── pages/           # All website pages
│   │   ├── index.astro           # Homepage
│   │   ├── about.astro           # About page
│   │   ├── privacy-policy.astro  # Privacy policy
│   │   ├── terms-of-service.astro
│   │   ├── medical-disclaimer.astro
│   │   ├── contact.astro
│   │   ├── faq.astro
│   │   └── ...more
│   ├── components/
│   │   └── Layout.astro  # Header + Footer
│   └── styles/
│       └── global.css    # All brand colors & styles
├── public/
│   └── favicon.svg
├── COLOR-PALETTE.md       # Complete color documentation
├── BRAND-UPDATE-SUMMARY.md # Brand transformation details
└── README.md              # Full project docs
```

---

## 🎨 Using Brand Colors in Your Code

### In Astro/HTML

```html
<!-- Primary button -->
<a href="#" class="btn">Download App</a>

<!-- Secondary button -->
<a href="#" class="btn btn-secondary">Learn More</a>

<!-- Card -->
<div class="card">
  <h2>Your Heading</h2>
  <p>Your content here</p>
</div>

<!-- Alert boxes -->
<div class="alert alert-warning">Warning message</div>
<div class="alert alert-info">Info message</div>
<div class="alert alert-danger">Error message</div>
```

### In CSS

```css
/* Use color variables */
.my-element {
  background: var(--primary);        /* Coral Burst */
  color: var(--text);                /* Charcoal */
  border: 1px solid var(--border);   /* Warm neutral */
}

/* Use gradients */
.hero {
  background: var(--gradient-hero);  /* Peach to white */
}
```

---

## 🎯 Key Brand Elements

### Logo
- **Header Logo:** Horizontal ReguMe logo
- **Location:** Cloudinary (auto-loads)
- **Height:** 40px (responsive)

### Colors
- **Primary:** Coral Burst (#E86842)
- **Backgrounds:** Light Peach (#FFF4EC) + White (#FFFFFF)
- **Text:** Charcoal (#1E1F22)

### Typography
- **Headings:** Bold, Charcoal
- **Body:** Regular, Charcoal
- **Font:** System fonts (-apple-system)

### Border Radius
- **Buttons:** 16px
- **Cards:** 16px
- **Alerts:** 16px

### Shadows
- **Buttons:** Coral glow
- **Cards:** Soft neutral

---

## 📱 Testing Your Changes

### Local Testing

1. **Start dev server:**
   ```bash
   npm run dev
   ```

2. **Open browser:**
   ```
   http://localhost:4321
   ```

3. **Test all pages:**
   - Homepage (/)
   - About (/about)
   - Privacy Policy (/privacy-policy)
   - Terms (/terms-of-service)
   - Medical Disclaimer (/medical-disclaimer)
   - Contact (/contact)
   - FAQ (/faq)

### Mobile Testing

1. **Get your local IP:**
   ```bash
   ifconfig | grep "inet "
   ```

2. **Access from phone:**
   ```
   http://YOUR_IP:4321
   ```

---

## 🎨 Customizing Colors

### Option 1: Use Existing Variables

Best practice - use existing color variables:

```css
.my-button {
  background: var(--primary);
  color: white;
}
```

### Option 2: Add New Variables

Edit `src/styles/global.css`:

```css
:root {
  /* Add your custom colors here */
  --my-custom-color: #FF0000;
}
```

---

## 🚀 Deploying to Vercel

### First Time Setup

1. **Install Vercel CLI:**
   ```bash
   npm install -g vercel
   ```

2. **Login:**
   ```bash
   vercel login
   ```

3. **Deploy:**
   ```bash
   vercel
   ```

### Subsequent Deploys

```bash
vercel --prod
```

---

## 📚 Documentation Files

### For Design Reference
- **COLOR-PALETTE.md** - Complete color system guide
- **BRAND-UPDATE-SUMMARY.md** - Brand transformation details

### For Development
- **README.md** - Full project documentation
- **CUSTOMIZATION-GUIDE.md** - How to customize content
- **DEPLOYMENT-CHECKLIST.md** - Deployment guide

---

## 🆘 Common Issues

### Build Fails

```bash
# Clean install
rm -rf node_modules package-lock.json
npm install
npm run build
```

### Dev Server Won't Start

```bash
# Kill existing process
lsof -ti:4321 | xargs kill
npm run dev
```

### Colors Not Showing

1. Check browser cache (Cmd+Shift+R to hard refresh)
2. Verify `global.css` is imported in `Layout.astro`
3. Check CSS variables are defined in `:root`

---

## 🎨 Quick Color Reference

### Primary Actions
```css
--primary: #E86842        /* Buttons, CTAs, links */
--primary-dark: #FF6B4A   /* Hover states */
```

### Backgrounds
```css
--background: #FFF4EC           /* Main page background */
--background-secondary: #FFFFFF /* Cards, modals */
```

### Text
```css
--text: #1E1F22           /* Headlines, body text */
--text-secondary: #5A5A5C /* Secondary text */
```

### Borders
```css
--border: #E0D8D0       /* Card borders */
--border-light: #F0E8E0 /* Dividers */
```

---

## 🔗 Useful Links

- **Dev Server:** http://localhost:4321
- **Logo (Header):** https://res.cloudinary.com/dsulhqvza/image/upload/v1763994515/Untitled_design_28_yscikl.png
- **Logo (Icon):** https://res.cloudinary.com/dsulhqvza/image/upload/v1763504676/Untitled_design_27_zb32bz.png

---

## ✅ Pre-Deploy Checklist

- [ ] All pages load without errors
- [ ] Colors look correct (coral, not teal)
- [ ] Logo displays properly
- [ ] Buttons have coral color
- [ ] Cards have white backgrounds on peach
- [ ] Mobile responsive
- [ ] Links work
- [ ] Build succeeds (`npm run build`)

---

## 🎉 You're Ready!

The website is fully branded with ReguMe's warm coral and peach color palette, matching the iOS app perfectly.

**Need help?** Check the documentation files or contact hello@regumeapp.com

---

**Happy Building!** 🚀
