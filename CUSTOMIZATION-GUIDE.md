# 🎨 Customization Guide

Quick guide to customize your ReguMe website before deployment.

## 📧 Email Addresses to Update

All legal pages reference these email addresses. If you want to use different emails, find and replace:

### Current Placeholder Emails:

```
support@regume.com     → Your customer support email
privacy@regume.com     → Your privacy/data requests email
legal@regume.com       → Your legal inquiries email
dmca@regume.com        → Your copyright claims email
dpo@regume.com         → Your data protection officer email
hello@regume.com       → Your general contact email
```

### How to Update All at Once:

**Option 1: VS Code / Cursor (Recommended)**
1. Press `Cmd+Shift+F` (Mac) or `Ctrl+Shift+F` (Windows)
2. Search for: `@regume.com`
3. Replace with: `@yourdomain.com`
4. Click "Replace All"

**Option 2: Command Line**
```bash
# Replace all instances (Mac/Linux)
find src/pages -type f -name "*.astro" -exec sed -i '' 's/@regume.com/@yourdomain.com/g' {} +

# Replace all instances (Linux)
find src/pages -type f -name "*.astro" -exec sed -i 's/@regume.com/@yourdomain.com/g' {} +
```

---

## 🏢 Business Information to Add

### 1. Business Address

**Where it's mentioned:**
- Privacy Policy (contact section)
- DMCA Policy (contact section)

**What to add:**
```
ReguMe
[Your Street Address]
[City, State ZIP]
[Country]
```

**Files to update:**
- `src/pages/privacy-policy.astro` (search for "Your Business Address")
- `src/pages/dmca-policy.astro` (search for "Your Business Address")

### 2. Founder/Team Information

**File:** `src/pages/about.astro`

**What to update:**
- Founder name: Search for "[Your Name]"
- Location: Search for "[Your Location]"

### 3. Governing Law

**File:** `src/pages/terms-of-service.astro`

**What to update:**
- Line ~503: "These Terms are governed by the laws of the United States"
- Update to your state/country if different

---

## 🎨 Branding Updates

### Colors

**File:** `src/styles/global.css`

Current brand colors (lines 2-7):
```css
:root {
  --primary: #00A57E;      /* Teal green - main brand color */
  --background: #F4FDFC;   /* Mint white - page background */
  --dark: #062925;         /* Dark teal - headings */
  --accent: #B9F2DA;       /* Light mint - highlights */
}
```

**To change colors:**
1. Open `src/styles/global.css`
2. Update the hex values in the `:root` section
3. Save and refresh

### Logo

**Current:** Text-only "ReguMe" logo

**To add image logo:**

1. Add your logo image to `/public/logo.png` (or .svg)

2. Update `src/components/Layout.astro` (line ~31):
```astro
<a href="/" class="logo">
  <img src="/logo.png" alt="ReguMe" style="height: 32px;" />
  <span>ReguMe</span>
</a>
```

### Favicon

**To update:**
1. Replace `/public/favicon.svg` with your icon
2. Or add `/public/favicon.ico` (classic format)

---

## 📱 App Store Link

### Update Download Link

**Current:** Placeholder `#download` links on homepage

**To update:**

**File:** `src/pages/index.astro`

Find and replace:
```astro
<a href="#download" class="btn">Download App</a>
```

With:
```astro
<a href="https://apps.apple.com/app/YOUR-APP-ID" class="btn" target="_blank">Download on App Store</a>
```

**Also update in:**
- `src/pages/about.astro` (bottom section)

---

## 📅 Update Dates

All legal pages have "Last Updated" dates. Update these before deployment:

**Files to update:**
- `src/pages/privacy-policy.astro` → Line 10
- `src/pages/terms-of-service.astro` → Line 10  
- `src/pages/medical-disclaimer.astro` → Line 10
- `src/pages/cookie-policy.astro` → Line 10
- `src/pages/dmca-policy.astro` → Line 10

**Current date:** November 25, 2024

**Update to:** Your deployment date or official launch date

---

## 🔗 Social Media Links

### Add Social Media Links

**File:** `src/pages/contact.astro`

Current placeholders (around line 35):
```astro
- Twitter: @regume
- Instagram: @regume_app
- TikTok: @regume
```

**Update with your actual handles, or remove if not applicable.**

---

## 🌐 SEO & Meta Information

### Update Site Title & Description

**File:** `src/components/Layout.astro`

Default description (line 7):
```astro
description = "ReguMe - Health Protocol Organizer"
```

**Customize for better SEO:**
```astro
description = "ReguMe: Transform social media wellness content into organized, trackable health protocols. Track supplements, habits, and routines from TikTok, Instagram, and YouTube."
```

### Add Google Analytics (Optional)

**File:** `src/components/Layout.astro`

Add before `</head>`:
```astro
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

Replace `G-XXXXXXXXXX` with your tracking ID.

---

## 📄 Content Customization

### Homepage Hero Section

**File:** `src/pages/index.astro`

**Lines 9-14:** Main headline and tagline
```astro
<h1 style="font-size: 3rem; margin-bottom: 1rem;">ReguMe</h1>
<p style="font-size: 1.25rem; color: var(--text-light); margin-bottom: 2rem;">
  Health Protocol Organizer<br/>
  From Social Media to Actionable Wellness Routines
</p>
```

**Customize** to match your messaging.

### About Page

**File:** `src/pages/about.astro`

**Key sections to personalize:**
- Mission statement (around line 82)
- Values (lines 88-107)
- Team information (lines 115-120)

### FAQ Page

**File:** `src/pages/faq.astro`

**Add/remove questions** based on common user questions:
- Each question is in a `<div class="card">` block
- Copy/paste card structure to add new FAQs
- Delete cards to remove questions

---

## 🧪 Testing Your Changes

After making customizations:

1. **Check locally:**
   ```bash
   npm run dev
   ```
   Visit: http://localhost:4321

2. **Test all pages:**
   - Click through every navigation link
   - Test on mobile view (browser dev tools)
   - Check all email links work

3. **Build for production:**
   ```bash
   npm run build
   ```
   Should complete without errors

---

## 🚀 Priority Customizations (Before Launch)

**Must Do:**
- [ ] Update email addresses
- [ ] Add business address (if required)
- [ ] Update "Last Updated" dates
- [ ] Add App Store download link

**Should Do:**
- [ ] Customize homepage messaging
- [ ] Add founder/team info to About page
- [ ] Update FAQ based on actual questions
- [ ] Add logo image (if you have one)

**Nice to Have:**
- [ ] Add Google Analytics
- [ ] Customize colors (if different from brand)
- [ ] Add social media links
- [ ] Improve SEO descriptions

---

## 💡 Tips

1. **Make changes in small batches** - Test after each change
2. **Keep legal content accurate** - Don't remove important disclaimers
3. **Mobile-first** - Always test on mobile view
4. **SEO matters** - Use descriptive titles and meta descriptions
5. **Legal review** - Have a lawyer review customized legal pages

---

## 🆘 Need Help?

**Common Issues:**

**Pages not updating?**
- Stop dev server (`Ctrl+C`)
- Restart: `npm run dev`
- Hard refresh browser: `Cmd+Shift+R` (Mac) or `Ctrl+Shift+R` (Windows)

**Styles broken?**
- Check `src/styles/global.css` for syntax errors
- Ensure CSS import is in `src/components/Layout.astro`

**Build errors?**
- Run: `npm run build`
- Check error messages
- Verify all `.astro` files have valid syntax

---

**You're all set!** Make your customizations, test thoroughly, and deploy. 🚀

