# ReguMe Legal Website

**Professional legal website for ReguMe iOS app - Required for App Store approval**

Built with [Astro](https://astro.build) for fast performance and SEO optimization.

---

## ✅ What's Included

This website contains **all required pages** for App Store approval:

### Required by Apple
- ✅ **Privacy Policy** (`/privacy-policy`) - REQUIRED by Apple
- ✅ **Terms of Service** (`/terms-of-service`) - REQUIRED by Apple  
- ✅ **Contact Page** (`/contact`) - REQUIRED by Apple
- ✅ **Data Deletion** (`/data-deletion`) - REQUIRED by Apple

### Required for Health Apps
- ✅ **Medical Disclaimer** (`/medical-disclaimer`) - CRITICAL for health apps

### Additional Legal Pages
- ✅ **Cookie Policy** (`/cookie-policy`)
- ✅ **DMCA Policy** (`/dmca-policy`)

### Informational Pages
- ✅ **Homepage** (`/`)
- ✅ **About** (`/about`)
- ✅ **FAQ** (`/faq`)

---

## 🚀 Quick Start

### 1. Development Server

```bash
npm run dev
```

Opens at **http://localhost:4321**

### 2. Build for Production

```bash
npm run build
```

### 3. Preview Production Build

```bash
npm run preview
```

---

## 📁 Project Structure

```
/
├── public/
│   └── favicon.svg
├── src/
│   ├── components/
│   │   └── Layout.astro          # Main layout with header/footer
│   ├── pages/
│   │   ├── index.astro            # Homepage
│   │   ├── privacy-policy.astro   # Privacy Policy (REQUIRED)
│   │   ├── terms-of-service.astro # Terms of Service (REQUIRED)
│   │   ├── medical-disclaimer.astro # Medical Disclaimer (REQUIRED)
│   │   ├── contact.astro          # Contact Page (REQUIRED)
│   │   ├── data-deletion.astro    # Data Deletion (REQUIRED)
│   │   ├── about.astro            # About ReguMe
│   │   ├── faq.astro              # FAQ
│   │   ├── cookie-policy.astro    # Cookie Policy
│   │   └── dmca-policy.astro      # DMCA Policy
│   └── styles/
│       └── global.css             # Brand colors & styles
├── DEPLOYMENT-CHECKLIST.md        # Step-by-step deployment guide
├── CUSTOMIZATION-GUIDE.md         # How to customize content
└── prd.md                         # Original requirements
```

---

## 📋 Next Steps

### Before Deployment:

1. **Read the guides:**
   - 📖 [DEPLOYMENT-CHECKLIST.md](./DEPLOYMENT-CHECKLIST.md) - Complete deployment guide
   - 🎨 [CUSTOMIZATION-GUIDE.md](./CUSTOMIZATION-GUIDE.md) - Customize content

2. **Update email addresses** (see CUSTOMIZATION-GUIDE.md)
   - `support@regume.com`
   - `privacy@regume.com`
   - `legal@regume.com`
   - `dmca@regume.com`

3. **Review legal content**
   - Have a lawyer review (highly recommended)
   - Update "Last Updated" dates
   - Add business address (if required)

4. **Deploy to Vercel/Netlify** (see DEPLOYMENT-CHECKLIST.md)
   - Free hosting with SSL
   - Automatic deployments
   - Custom domain support

5. **Add URLs to App Store Connect**
   - Privacy Policy URL
   - Support URL
   - Terms URL

---

## 🎨 Brand Colors

```css
/* PRIMARY BRAND - Coral Burst */
Primary:       #E86842  /* Coral - Main buttons, CTAs, brand identity */
Primary Dark:  #FF6B4A  /* Hover states, emphasis */
Primary Light: #FFC4A8  /* Light accents, highlights */
Primary Muted: #FFE5D9  /* Subtle backgrounds, disabled states */

/* BACKGROUNDS - Warm & Inviting */
Background:           #FFF4EC  /* Very Light Peach - main screens */
Background Secondary: #FFFFFF  /* Pure White - cards, modals */
Background Tint:      #E7F3F1  /* Chip Sage - subtle UI backgrounds */
Peach Soft:           #F8DCCF  /* Soft Peach - gradients */

/* TEXT - Charcoal & Grays */
Text Primary:   #1E1F22  /* Charcoal - headlines, body text */
Text Secondary: #5A5A5C  /* Medium gray - secondary text */
Text Tertiary:  #9E9EA0  /* Light gray - hints, disabled */

/* BORDERS - Warm Neutrals */
Border:       #E0D8D0  /* Warm neutral - cards, inputs */
Border Light: #F0E8E0  /* Very light warm - dividers */
```

**Full Color Documentation:** See [COLOR-PALETTE.md](./COLOR-PALETTE.md)

**Design Philosophy:** Warm, welcoming coral and peach tones create an inviting, motivating experience that matches the iOS mobile app exactly.

---

## 🧞 Commands

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Installs dependencies                            |
| `npm run dev`             | Starts local dev server at `localhost:4321`      |
| `npm run build`           | Build your production site to `./dist/`          |
| `npm run preview`         | Preview your build locally, before deploying     |
| `npm run astro check`     | Check for TypeScript/Astro errors                |

---

## 🚨 Important Notes

### For App Store Approval:

1. ✅ **All required pages are complete**
2. ✅ **Mobile-responsive design**
3. ✅ **Fast loading with Astro**
4. ⚠️ **Legal review recommended** (especially Medical Disclaimer)
5. ⚠️ **Must be deployed with HTTPS**
6. ⚠️ **Email addresses must work**

### Medical Disclaimer:

This is **CRITICAL** for health apps. The Medical Disclaimer clearly states:
- ReguMe is NOT medical advice
- Users should consult healthcare professionals
- No warranties or guarantees
- Limitation of liability

**Do not modify or weaken the Medical Disclaimer without legal review.**

---

## 📞 Support

- **Deployment issues?** See [DEPLOYMENT-CHECKLIST.md](./DEPLOYMENT-CHECKLIST.md)
- **Content customization?** See [CUSTOMIZATION-GUIDE.md](./CUSTOMIZATION-GUIDE.md)
- **Astro questions?** Visit [Astro Documentation](https://docs.astro.build)

---

## ✨ Features

- ⚡ Lightning-fast with Astro
- 📱 Mobile-responsive design
- 🎨 Professional brand styling
- 🔒 GDPR & CCPA compliant
- ♿ Accessible navigation
- 🔍 SEO-optimized
- 📄 All legal pages complete

---

**Ready for App Store submission!** 🚀

Follow the [DEPLOYMENT-CHECKLIST.md](./DEPLOYMENT-CHECKLIST.md) to deploy and submit to Apple.

