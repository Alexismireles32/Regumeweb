# ReguMe Legal & Policy Website - Complete PRD

## 🎯 Project Overview

**Purpose:** Create a professional website to host all legal documents, policies, and terms required for ReguMe's iOS App Store approval and legal compliance.

**Critical Mission:** This website is **REQUIRED** for App Store approval. Without it, the app will be rejected.

**Timeline:** 3-5 days to complete
**Priority:** 🔴 CRITICAL - Blocking App Store submission

---

## 📋 Executive Summary

### **What This Website Must Include:**

1. ✅ **Privacy Policy** (REQUIRED by Apple)
2. ✅ **Terms of Service** (REQUIRED by Apple)
3. ✅ **Medical Disclaimer** (REQUIRED for health apps)
4. ✅ **Cookie Policy** (Best practice)
5. ✅ **DMCA Policy** (Copyright protection)
6. ✅ **Contact Information** (REQUIRED by Apple)
7. ✅ **About ReguMe** (Trust building)
8. ✅ **Data Deletion Request Form** (REQUIRED by Apple)
9. ✅ **Support/FAQ** (Best practice)

### **Technical Requirements:**

- ✅ Must be publicly accessible (https://regume.com or similar)
- ✅ Must be mobile-friendly
- ✅ Must load fast (<3 seconds)
- ✅ Must be simple to navigate
- ✅ Must have valid SSL certificate
- ✅ Must be indexed by search engines

---

## 🏗️ Website Structure

### **Recommended Tech Stack:**

**Option 1: Next.js + Vercel (RECOMMENDED)**
- ✅ Fast deployment
- ✅ Free hosting
- ✅ Automatic SSL
- ✅ SEO-friendly
- ✅ Professional

**Option 2: Simple HTML + Netlify**
- ✅ Even simpler
- ✅ Free hosting
- ✅ Quick to build

**Option 3: WordPress**
- ⚠️ More overhead
- ⚠️ Slower
- ✅ Easy to update

**RECOMMENDATION:** Use Next.js + Vercel for professional, fast deployment.

---

## 📄 Page-by-Page Requirements

### **1. Homepage (index.html or /)**

**Purpose:** Welcome page with quick navigation to all legal documents

**Required Content:**
```
┌─────────────────────────────────────┐
│  ReguMe Logo                        │
│                                     │
│  Health Protocol Organizer          │
│  From Social Media to Actionable    │
│  Wellness Routines                  │
│                                     │
│  Quick Links:                       │
│  - Privacy Policy                   │
│  - Terms of Service                 │
│  - Medical Disclaimer               │
│  - Contact Us                       │
│  - Download App (App Store link)    │
│                                     │
│  © 2024 ReguMe. All rights reserved.│
└─────────────────────────────────────┘
```

**Technical Specs:**
- Clean, minimal design
- Brand colors: #00A57E (primary), #F4FDFC (background)
- Mobile-responsive
- Fast loading (<1 second)

---

### **2. Privacy Policy (/privacy-policy)**

**Purpose:** REQUIRED by Apple - Disclose all data collection and usage

**Critical Sections (In Order):**

#### **2.1 Introduction**
```markdown
Last Updated: [DATE]

ReguMe ("we," "our," or "us") respects your privacy. This Privacy Policy 
explains how we collect, use, disclose, and safeguard your information when 
you use our mobile application ReguMe (the "App").

By using the App, you agree to the collection and use of information in 
accordance with this policy.
```

#### **2.2 Information We Collect**

**MUST LIST EVERYTHING:**

```markdown
### Personal Information
- Email address (for account creation)
- Name (optional, for personalization)
- Age range (optional, for anonymized health insights)
- Gender (optional, for anonymized health insights)
- Geographic region (optional, general location only)

### Health Information
- Saved wellness protocols
- Supplement/habit tracking data
- Progress check-in responses
- Daily action completion status
- Outcome tracking data (anonymized and aggregated)

### Usage Information
- Video URLs you import
- Search queries in Discovery Engine
- App usage analytics
- Crash reports
- Device information (model, OS version)

### Third-Party Data
- Social media video metadata (from TikTok, Instagram, YouTube)
- Creator profile information (usernames, follower counts)
- Product recommendations (from Amazon Product Advertising API)
```

#### **2.3 How We Use Your Information**

```markdown
We use your information to:
- Provide and maintain the App
- Extract health protocols from social media videos
- Personalize your wellness recommendations
- Generate anonymized health insights ("democracy in health")
- Improve App functionality
- Send notifications about your daily routines
- Provide customer support
- Comply with legal obligations
```

#### **2.4 Third-Party Services**

**MUST DISCLOSE ALL:**

```markdown
### Service Providers We Use:

**Supabase (Database & Authentication)**
- Purpose: User authentication, data storage
- Data shared: Email, user profile, app data
- Privacy Policy: https://supabase.com/privacy

**OpenAI (GPT-4o)**
- Purpose: AI-powered protocol extraction, content analysis
- Data shared: Video transcripts, captions
- Privacy Policy: https://openai.com/policies/privacy-policy

**Apify (Web Scraping)**
- Purpose: Extract video metadata from social media
- Data shared: Video URLs
- Privacy Policy: https://apify.com/privacy-policy

**Amazon Product Advertising API**
- Purpose: Product recommendations for supplements
- Data shared: Supplement names
- Privacy Policy: https://www.amazon.com/gp/help/customer/display.html?nodeId=468496

**Cloudflare R2 / Supabase Storage**
- Purpose: Image hosting
- Data shared: Profile images, video thumbnails
- Privacy Policy: https://www.cloudflare.com/privacypolicy/

**Sentry (Error Tracking)**
- Purpose: Monitor app errors and performance
- Data shared: Crash logs, device information
- Privacy Policy: https://sentry.io/privacy/
```

#### **2.5 Data Security**

```markdown
We implement appropriate technical and organizational security measures:
- Encryption in transit (SSL/TLS)
- Encryption at rest (database encryption)
- Secure authentication (Supabase Auth)
- Regular security updates
- Access controls and logging

However, no method of transmission over the Internet is 100% secure. 
While we strive to protect your data, we cannot guarantee absolute security.
```

#### **2.6 Data Retention**

```markdown
We retain your information:
- Account data: Until you delete your account
- Health tracking data: Until you delete your account
- Anonymized analytics: Indefinitely (cannot be linked to you)
- Cached data: 24-48 hours (automatic cleanup)

You can request deletion of your data at any time.
```

#### **2.7 Your Rights**

```markdown
You have the right to:
- Access your personal data
- Correct inaccurate data
- Delete your data (account deletion)
- Opt-out of outcome tracking
- Opt-out of analytics
- Export your data

To exercise these rights, contact us at privacy@regume.com
```

#### **2.8 Children's Privacy**

```markdown
ReguMe is intended for users 17 years of age and older. We do not 
knowingly collect information from children under 17. If you believe 
we have collected information from a child, please contact us immediately.
```

#### **2.9 California Privacy Rights (CCPA)**

```markdown
If you are a California resident, you have additional rights:
- Right to know what data we collect
- Right to deletion
- Right to opt-out of data sales (we do not sell data)
- Right to non-discrimination

Contact us at privacy@regume.com to exercise these rights.
```

#### **2.10 International Users (GDPR)**

```markdown
If you are in the European Economic Area (EEA), you have additional rights:
- Right to access
- Right to rectification
- Right to erasure
- Right to restrict processing
- Right to data portability
- Right to object

Our legal basis for processing: Consent, contract performance, legitimate interests.

Contact our Data Protection Officer at dpo@regume.com
```

#### **2.11 Changes to Privacy Policy**

```markdown
We may update this Privacy Policy from time to time. We will notify you 
of changes by:
- Posting the new policy on this page
- Updating the "Last Updated" date
- Sending an in-app notification (for material changes)

Continued use after changes constitutes acceptance.
```

#### **2.12 Contact Us**

```markdown
For privacy questions or concerns:

Email: privacy@regume.com
Address: [Your Business Address]
Phone: [Your Phone Number] (optional)

Response time: Within 30 days
```

---

### **3. Terms of Service (/terms-of-service)**

**Purpose:** Legal agreement between ReguMe and users

**Critical Sections:**

#### **3.1 Acceptance of Terms**

```markdown
Last Updated: [DATE]

By accessing or using ReguMe ("the App"), you agree to be bound by 
these Terms of Service ("Terms"). If you do not agree, do not use the App.

These Terms constitute a legally binding agreement between you and ReguMe.
```

#### **3.2 Description of Service**

```markdown
ReguMe is a mobile application that:
- Extracts health and wellness protocols from social media videos
- Organizes supplements, habits, and routines
- Provides daily action tracking
- Offers product recommendations
- Generates anonymized health insights

ReguMe is NOT:
- A medical service or healthcare provider
- A substitute for professional medical advice
- A diagnostic or treatment tool
- Endorsed by any medical organization
```

#### **3.3 Medical Disclaimer (CRITICAL)**

```markdown
⚠️ IMPORTANT MEDICAL DISCLAIMER

ReguMe provides informational content extracted from third-party social 
media sources. This information is NOT:
- Medical advice, diagnosis, or treatment
- Verified by medical professionals
- A substitute for consulting qualified healthcare providers
- Approved by the FDA or any regulatory agency

ALWAYS consult with licensed healthcare professionals before:
- Starting any supplement regimen
- Following health protocols
- Making changes to your wellness routine
- Treating any medical condition

ReguMe is not responsible for any health outcomes, adverse effects, or 
consequences resulting from following protocols in the App.

Use of the App is at your own risk.
```

#### **3.4 User Responsibilities**

```markdown
You agree to:
- Be at least 17 years of age
- Provide accurate account information
- Keep your account secure
- Use the App for lawful purposes only
- Not attempt to reverse engineer the App
- Not scrape or automated-access the App
- Not upload malicious content
- Not violate intellectual property rights

You are solely responsible for:
- Your health decisions
- Following protocols from the App
- Verifying information with medical professionals
- Any consequences of using the App
```

#### **3.5 Intellectual Property**

```markdown
### ReguMe's IP
The App, including design, code, logos, and functionality, is owned by 
ReguMe and protected by copyright, trademark, and other laws.

### Third-Party Content
Social media video content, creator names, and profile images are the 
property of their respective owners. ReguMe does not claim ownership.

### User Content
You retain ownership of your personal data and tracking information. 
By using the App, you grant ReguMe a license to:
- Store and process your data
- Generate anonymized insights
- Display your data within the App

### Attribution
ReguMe provides attribution to original content creators through:
- Creator names and usernames
- Links to original videos
- Follower counts and platform information
```

#### **3.6 Third-Party Services**

```markdown
The App integrates with third-party services:
- Social media platforms (TikTok, Instagram, YouTube)
- Amazon Product Advertising API
- Cloud service providers

We are not responsible for:
- Third-party service availability
- Changes to third-party APIs
- Third-party privacy practices
- External website content
```

#### **3.7 Prohibited Uses**

```markdown
You may NOT:
- Use the App for illegal activities
- Harass or harm others
- Upload spam or malicious content
- Circumvent security features
- Access others' accounts
- Scrape or copy App content
- Reverse engineer the App
- Resell or redistribute the App
- Make false medical claims
- Promote dangerous health practices
```

#### **3.8 Content Reporting**

```markdown
If you believe content in the App:
- Violates copyright
- Contains harmful health advice
- Is inappropriate or offensive
- Violates these Terms

Report it to: support@regume.com

We will review and may remove content at our discretion.
```

#### **3.9 Disclaimers and Limitation of Liability**

```markdown
THE APP IS PROVIDED "AS IS" WITHOUT WARRANTIES OF ANY KIND.

WE DISCLAIM ALL WARRANTIES:
- Accuracy of extracted protocols
- Fitness for a particular purpose
- Non-infringement
- Uninterrupted service

LIMITATION OF LIABILITY:
To the maximum extent permitted by law, ReguMe shall not be liable for:
- Health outcomes or adverse effects
- Lost data or information
- Indirect, incidental, or consequential damages
- Damages exceeding the amount paid for the App (if any)

Some jurisdictions do not allow limitation of liability, so this may 
not apply to you.
```

#### **3.10 Indemnification**

```markdown
You agree to indemnify and hold harmless ReguMe from any claims, damages, 
or expenses arising from:
- Your use of the App
- Your violation of these Terms
- Your violation of any laws
- Your health decisions based on App content
```

#### **3.11 Account Termination**

```markdown
We may suspend or terminate your account if:
- You violate these Terms
- You engage in prohibited activities
- Required by law
- At our discretion for any reason

You may delete your account at any time through the App settings.

Upon termination:
- Your access will cease
- Your data will be deleted (within 30 days)
- These Terms will survive where applicable
```

#### **3.12 Dispute Resolution**

```markdown
### Governing Law
These Terms are governed by the laws of [Your State/Country].

### Arbitration (Optional - Consult Lawyer)
Any disputes will be resolved through binding arbitration, except:
- Small claims court disputes
- Intellectual property claims

### Class Action Waiver
You agree to resolve disputes individually, not as part of a class action.
```

#### **3.13 Changes to Terms**

```markdown
We may modify these Terms at any time by:
- Posting updated Terms
- Updating the "Last Updated" date
- Notifying you in-app (for material changes)

Continued use after changes constitutes acceptance.
```

#### **3.14 Contact Information**

```markdown
For questions about these Terms:

Email: legal@regume.com
Address: [Your Business Address]

Customer Support: support@regume.com
```

---

### **4. Medical Disclaimer Page (/medical-disclaimer)**

**Purpose:** Standalone, prominent disclaimer for health content

```markdown
# Medical Disclaimer

Last Updated: [DATE]

## ⚠️ IMPORTANT - PLEASE READ CAREFULLY

ReguMe is an informational tool that extracts wellness protocols from 
social media content. **ReguMe is not a medical service and does not 
provide medical advice, diagnosis, or treatment.**

## What ReguMe IS

✅ An organizational tool for wellness information
✅ A way to track health routines and habits
✅ A platform to discover health content from social media
✅ An informational resource

## What ReguMe IS NOT

❌ A medical diagnosis tool
❌ A treatment recommendation service
❌ A replacement for healthcare professionals
❌ Verified or approved medical advice
❌ Endorsed by any medical organization
❌ Regulated by the FDA or similar agencies

## Critical Warnings

### Consult Healthcare Professionals

**ALWAYS consult qualified healthcare providers before:**
- Starting any supplement or vitamin regimen
- Following health protocols
- Changing your diet or exercise routine
- Treating any medical condition
- Discontinuing any prescribed treatment

### Content Source

All protocols in ReguMe are extracted from:
- Social media videos (TikTok, Instagram, YouTube)
- Content creators who may not be medical professionals
- Unverified sources

**We do not verify:**
- Medical accuracy of protocols
- Safety of recommendations
- Efficacy of treatments
- Qualifications of content creators

### Health Risks

Following unverified health advice can be dangerous:
- Supplements may interact with medications
- Treatments may worsen conditions
- Delays in proper medical care can be harmful
- Individual health needs vary

### No Professional Relationship

Using ReguMe does NOT create:
- A doctor-patient relationship
- A healthcare provider relationship
- Any fiduciary duty
- Any liability on our part

## Your Responsibility

You are solely responsible for:
- Verifying information with medical professionals
- Your health decisions
- Any outcomes from following protocols
- Ensuring supplements/treatments are safe for you

## Emergency Situations

**If you are experiencing a medical emergency:**
- Call 911 (or your local emergency number)
- Go to the nearest emergency room
- DO NOT rely on ReguMe or social media advice

## Supplement Disclaimers

Supplements mentioned in ReguMe:
- Are not evaluated by the FDA
- Are not intended to diagnose, treat, cure, or prevent disease
- May have side effects or interactions
- May not be suitable for everyone

**Always consult a healthcare provider before taking supplements.**

## Product Recommendations

Product links and recommendations:
- Are provided for convenience only
- Are not endorsements
- May earn us affiliate commissions
- Should be verified with your healthcare provider

## Accuracy of Information

We do not guarantee:
- Accuracy of extracted protocols
- Completeness of information
- Up-to-date medical knowledge
- Error-free content

Information may be outdated, incomplete, or incorrect.

## Limitation of Liability

**TO THE MAXIMUM EXTENT PERMITTED BY LAW:**

ReguMe is not liable for:
- Health outcomes or adverse effects
- Medical complications
- Misuse of information
- Reliance on App content
- Any damages arising from use

## Changes to Disclaimer

We may update this disclaimer at any time. Check regularly for updates.

## Questions or Concerns

If you have medical questions or concerns:

**DO NOT contact ReguMe for medical advice.**

Instead:
- Contact your healthcare provider
- Visit urgent care or emergency room
- Call a medical hotline

For non-medical App questions: support@regume.com

---

**By using ReguMe, you acknowledge that you have read, understood, and 
agree to this Medical Disclaimer.**

**USE AT YOUR OWN RISK.**
```

---

### **5. Cookie Policy (/cookie-policy)**

**Purpose:** Disclose use of cookies and tracking (if applicable)

```markdown
# Cookie Policy

Last Updated: [DATE]

## What Are Cookies?

Cookies are small text files stored on your device when you visit our website.

## How We Use Cookies

### Website Cookies (regume.com)
- Essential cookies: Site functionality
- Analytics cookies: Usage statistics (Google Analytics, if used)
- No advertising cookies

### Mobile App
The ReguMe mobile app does NOT use browser cookies. Instead, we use:
- Local storage: Cached data, user preferences
- Analytics SDKs: App usage tracking (if implemented)

## Your Choices

You can:
- Disable cookies in your browser settings
- Opt-out of analytics in the App settings
- Use the website without cookies (limited functionality)

## Third-Party Cookies

Our website may load third-party services that use cookies:
- Google Analytics (analytics)
- Hosting provider (functionality)

Refer to their privacy policies for details.

## Contact Us

Questions about cookies: privacy@regume.com
```

---

### **6. DMCA Copyright Policy (/dmca-policy)**

**Purpose:** Protect against copyright claims (important for user-generated content)

```markdown
# DMCA Copyright Policy

Last Updated: [DATE]

## Overview

ReguMe respects intellectual property rights and complies with the 
Digital Millennium Copyright Act (DMCA).

## How ReguMe Uses Content

ReguMe:
- Does NOT host social media videos
- Does NOT copy video files
- Links to original content on social media platforms
- Displays publicly available metadata (thumbnails, descriptions)
- Extracts text-based protocols from video transcripts
- Attributes all content to original creators

## If You Believe Your Rights Were Infringed

If you believe content in ReguMe infringes your copyright:

### 1. Send a DMCA Notice

Email: dmca@regume.com

Include:
- Your name and contact information
- Description of copyrighted work
- Location of infringing content in our App
- Statement of good faith belief
- Statement of accuracy under penalty of perjury
- Your physical or electronic signature

### 2. We Will Respond

Within 5-10 business days:
- Review your claim
- Remove content if valid
- Notify the user who uploaded it (if applicable)

## Counter-Notice

If your content was removed and you believe it was a mistake:

Email: dmca@regume.com

Include:
- Your contact information
- Identification of removed content
- Statement of good faith belief
- Consent to jurisdiction
- Your signature

## Repeat Infringers

We may terminate accounts of repeat infringers.

## Fair Use

ReguMe may rely on fair use for:
- Transformative use of content (extracting protocols)
- Attribution and linking
- Educational purposes

## Contact

DMCA Agent: dmca@regume.com
Address: [Your Business Address]
```

---

### **7. Data Deletion Request (/data-deletion)**

**Purpose:** REQUIRED by Apple - Allow users to request data deletion

**Must Include:**

```markdown
# Data Deletion Request

## Delete Your ReguMe Account & Data

You have the right to delete your account and all associated data.

### How to Delete Your Data

**Option 1: In-App (Recommended)**
1. Open ReguMe app
2. Go to Settings
3. Tap "Account"
4. Tap "Delete Account"
5. Confirm deletion

All your data will be permanently deleted within 30 days.

**Option 2: Email Request**
If you cannot access the app, email us:

Email: privacy@regume.com
Subject: Data Deletion Request

Include:
- Your registered email address
- Your account username (if known)
- Confirmation that you want all data deleted

We will respond within 30 days.

### What Gets Deleted

When you delete your account:
- ✅ Personal information (email, name, demographics)
- ✅ Saved protocols and routines
- ✅ Tracking data and check-ins
- ✅ Preferences and settings
- ✅ Account access

### What Remains (Anonymized)

Some data cannot be deleted because it's anonymized:
- Aggregated analytics (no personal identifiers)
- Anonymized outcome insights
- System logs (retain for 90 days for security)

### Deletion Timeline

- Request received: Immediate confirmation
- Data deletion: Within 30 days
- Confirmation email: After deletion completes

### Cannot Be Undone

**Data deletion is permanent and cannot be reversed.**

If you create a new account later, it will be treated as a new user.

### Questions?

Email: privacy@regume.com
Response time: Within 30 days
```

---

### **8. Contact Us (/contact)**

**Purpose:** REQUIRED by Apple - Provide support contact

```markdown
# Contact Us

## Get in Touch with ReguMe

### Customer Support

**Email:** support@regume.com
**Response Time:** Within 48 hours (business days)

For:
- App issues or bugs
- Feature questions
- Account help
- General inquiries

### Privacy Requests

**Email:** privacy@regume.com
**Response Time:** Within 30 days

For:
- Data deletion requests
- Privacy concerns
- GDPR/CCPA requests
- Data export requests

### Legal Inquiries

**Email:** legal@regume.com
**Response Time:** Within 5-10 business days

For:
- Copyright claims (DMCA)
- Terms of Service questions
- Legal notices

### Business Address

ReguMe
[Your Street Address]
[City, State ZIP]
[Country]

### Social Media

- Twitter: @regume
- Instagram: @regume_app
- TikTok: @regume

---

**We're here to help!**

Most questions are answered in our FAQ section.
For urgent issues, email support@regume.com
```

---

### **9. About ReguMe (/about)**

**Purpose:** Build trust and explain the app

```markdown
# About ReguMe

## Health Protocol Organizer for the Social Media Age

ReguMe transforms social media wellness content into actionable, 
organized health protocols.

### The Problem

Health advice is scattered across TikTok, Instagram, and YouTube. 
Keeping track of supplements, habits, and routines is overwhelming.

### The Solution

ReguMe extracts protocols from videos and organizes them into:
- Daily action checklists
- Supplement schedules
- Habit reminders
- Progress tracking

### How It Works

1. **Import** - Paste a video URL from TikTok, Instagram, or YouTube
2. **Extract** - AI analyzes the video and extracts the protocol
3. **Organize** - Protocols are saved to your personal library
4. **Track** - Daily reminders keep you consistent

### Mission

Democratize health knowledge by making wellness protocols accessible, 
organized, and actionable for everyone.

### Values

- **Attribution** - Always credit original creators
- **Safety** - Strong medical disclaimers and user protection
- **Privacy** - Your health data stays secure
- **Community** - Share insights to help others

### Technology

Built with:
- React Native (mobile app)
- Supabase (backend)
- OpenAI GPT-4o (AI extraction)
- Modern health tech stack

### Team

Founded by [Your Name]
Based in [Your Location]

### Contact

Questions? Email: hello@regume.com

---

**Join thousands organizing their wellness journey with ReguMe.**

[Download on the App Store]
```

---

### **10. FAQ / Support (/faq)**

**Purpose:** Reduce support burden and build trust

```markdown
# Frequently Asked Questions

## General Questions

### What is ReguMe?
ReguMe is a mobile app that extracts health protocols from social media 
videos and helps you organize and track them.

### Is ReguMe free?
[Explain your pricing model]

### What platforms are supported?
TikTok, Instagram, and YouTube.

### Is my data private?
Yes. Read our [Privacy Policy](/privacy-policy) for details.

## Medical & Safety

### Is ReguMe medical advice?
**NO.** ReguMe provides informational content only. Always consult 
healthcare professionals. See our [Medical Disclaimer](/medical-disclaimer).

### Are protocols verified by doctors?
No. Protocols are extracted from social media and not verified. 
Verify with your healthcare provider before following.

### Can I use ReguMe to treat medical conditions?
No. ReguMe is not a medical tool. Consult healthcare professionals 
for medical treatment.

## App Features

### How do I import a protocol?
[Step by step instructions]

### How do I track my progress?
[Instructions]

### Can I create custom protocols?
[Yes/No + details]

### How do I delete my account?
[Link to data deletion page]

## Technical

### What devices are supported?
iOS 14.0 or later.

### Why isn't my video importing?
[Troubleshooting steps]

### How do I report a bug?
Email: support@regume.com

## Privacy & Legal

### What data do you collect?
See our [Privacy Policy](/privacy-policy).

### How do I delete my data?
See [Data Deletion](/data-deletion).

### Do you sell my data?
No. We never sell user data.

## Content & Copyright

### Who owns the protocols?
Original creators own their content. ReguMe provides attribution 
and links to sources.

### How do I report copyright infringement?
See our [DMCA Policy](/dmca-policy).

### Can I share protocols?
Yes, but attribution to original creators is maintained.

---

**Still have questions?**

Email: support@regume.com
```

---

## 🎨 Website Design Requirements

### **Visual Design:**

**Brand Colors:**
- Primary: #00A57E (teal green)
- Background: #F4FDFC (mint white)
- Dark: #062925 (dark teal)
- Accent: #B9F2DA (light mint)

**Typography:**
- Headings: SF Pro Display (or similar)
- Body: SF Pro Text (or similar)
- Size: 16px base font size
- Line height: 1.6 for readability

**Layout:**
```
┌────────────────────────────────────┐
│  Header (Logo + Navigation)        │
├────────────────────────────────────┤
│  Content (Max width: 800px)        │
│  Centered, with padding            │
│                                    │
│  [Clean, readable text]            │
│                                    │
├────────────────────────────────────┤
│  Footer (Links + Copyright)        │
└────────────────────────────────────┘
```

### **Navigation:**

**Header Menu:**
- Home
- Privacy Policy
- Terms of Service
- Medical Disclaimer
- Contact
- Download App

**Footer Links:**
- All legal pages
- Social media links
- Copyright notice

### **Mobile-First:**
- Responsive design
- Touch-friendly links (44px minimum)
- Readable font sizes (16px+)
- Fast loading (<3 seconds)

---

## 🚀 Deployment Checklist

### **Pre-Launch:**

- [ ] All pages written and proofread
- [ ] Legal review (lawyer review recommended)
- [ ] Domain purchased (regume.com or similar)
- [ ] SSL certificate active (HTTPS)
- [ ] Mobile responsive tested
- [ ] Page load speed <3 seconds
- [ ] Contact emails set up (privacy@, support@, legal@, dmca@)
- [ ] Privacy policy generator used (or lawyer-written)
- [ ] Terms reviewed by lawyer (highly recommended)

### **Launch:**

- [ ] Deploy to Vercel/Netlify
- [ ] Test all pages load correctly
- [ ] Test all links work
- [ ] Test mobile layout
- [ ] Submit sitemap to Google
- [ ] Add to App Store Connect (URLs required)

### **Post-Launch:**

- [ ] Monitor email inboxes (support@, privacy@, etc)
- [ ] Set up auto-responders for common questions
- [ ] Create FAQ based on user questions
- [ ] Update as laws change

---

## 📱 App Store Connect Configuration

### **Where to Add URLs:**

**In App Store Connect:**

1. **App Privacy Section:**
   - Privacy Policy URL: `https://regume.com/privacy-policy`

2. **App Information:**
   - Terms of Service: `https://regume.com/terms-of-service`
   - Support URL: `https://regume.com/contact`

3. **Version Information:**
   - What's New: Mention any policy updates

### **In-App Links:**

Add to your app:
- Settings → Privacy Policy (opens web view)
- Settings → Terms of Service (opens web view)
- Settings → Medical Disclaimer (opens web view)
- Settings → Contact Support (opens email or web view)
- Onboarding → "By signing up, you agree to our [Terms] and [Privacy Policy]"

---

## ⚖️ Legal Compliance Summary

### **What This Website Achieves:**

✅ **Apple Requirements:**
- Privacy policy (REQUIRED)
- Terms of service (REQUIRED)
- Support contact (REQUIRED)
- Data deletion method (REQUIRED)

✅ **Health App Requirements:**
- Medical disclaimers (CRITICAL)
- No medical claims
- User warnings
- Safety information

✅ **Privacy Laws:**
- GDPR compliance (EU users)
- CCPA compliance (California users)
- Data transparency
- User rights respected

✅ **Copyright Protection:**
- DMCA policy
- Counter-notice process
- Repeat infringer policy

✅ **Risk Mitigation:**
- Limitation of liability
- Disclaimers throughout
- User responsibilities clear
- No warranties

---

## 💰 Estimated Costs

### **One-Time:**
- Domain name: $10-15/year
- Legal review (optional): $500-2000
- Design (if hiring): $0 (use template) - $500

### **Ongoing:**
- Hosting: $0 (Vercel/Netlify free tier)
- Email: $0-6/month (Google Workspace or similar)
- Maintenance: Minimal

**Total to Launch: $10-15 (domain only)**

---

## ⏱️ Timeline

### **Day 1-2: Setup**
- Buy domain
- Set up hosting (Vercel/Netlify)
- Set up email addresses
- Choose template/framework

### **Day 3-4: Content**
- Write all pages (use this PRD as template)
- Customize for your business details
- Proofread everything

### **Day 5: Launch**
- Deploy website
- Test all pages
- Configure DNS
- Submit to Google

### **Post-Launch:**
- Add URLs to App Store Connect
- Update app with legal links
- Monitor support emails

---

## 🎯 Success Criteria

### **Must-Haves for App Store Approval:**

- ✅ Privacy policy URL works
- ✅ Terms of service URL works
- ✅ Contact method works (email)
- ✅ Data deletion process explained
- ✅ Medical disclaimers prominent
- ✅ Website loads fast (<3 seconds)
- ✅ Mobile-friendly
- ✅ HTTPS enabled

### **Nice-to-Haves:**

- Professional design
- FAQ section
- Blog (optional)
- Press kit
- Testimonials

---

## 📝 Example Next.js File Structure

```
regume-website/
├── pages/
│   ├── index.tsx                 # Homepage
│   ├── privacy-policy.tsx        # Privacy Policy
│   ├── terms-of-service.tsx      # Terms
│   ├── medical-disclaimer.tsx    # Medical Disclaimer
│   ├── cookie-policy.tsx         # Cookies
│   ├── dmca-policy.tsx          # DMCA
│   ├── data-deletion.tsx        # Data Deletion
│   ├── contact.tsx              # Contact
│   ├── about.tsx                # About
│   └── faq.tsx                  # FAQ
├── components/
│   ├── Layout.tsx               # Header + Footer
│   ├── Header.tsx               # Navigation
│   └── Footer.tsx               # Footer links
├── styles/
│   └── globals.css              # Global styles
├── public/
│   └── logo.png                 # ReguMe logo
└── package.json
```

---

## 🚨 Critical Warnings

### **DO NOT SKIP:**

1. ❌ **Medical Disclaimer** - You WILL be rejected without this
2. ❌ **Privacy Policy** - Required by law and Apple
3. ❌ **Terms of Service** - Protects you legally
4. ❌ **Contact Email** - Apple requires this

### **HIGHLY RECOMMEND:**

- Lawyer review of legal documents ($500-2000 investment)
- Professional email addresses (not Gmail)
- Business entity (LLC) for liability protection
- General liability insurance for health apps

### **BEFORE APP STORE SUBMISSION:**

- ✅ All URLs in App Store Connect work
- ✅ All pages load on mobile
- ✅ Email addresses respond
- ✅ Legal pages are complete

---

## 📞 Next Steps

### **Immediate Actions:**

1. **Buy Domain:** regume.com (or alternative)
2. **Set Up Hosting:** Vercel (free, fast)
3. **Set Up Emails:** privacy@, support@, legal@, dmca@
4. **Copy Content:** Use this PRD as templates
5. **Customize:** Add your business details
6. **Deploy:** Push to production
7. **Test:** Verify everything works
8. **Submit:** Add URLs to App Store Connect

### **Order of Operations:**

1. Domain + hosting (Day 1)
2. Write content (Day 2-3)
3. Deploy website (Day 4)
4. Test thoroughly (Day 5)
5. Update app with links (Day 6)
6. Submit to App Store (Day 7)

---

## ✅ Success Indicators

You're ready to submit when:

- ✅ Privacy policy URL returns 200 (loads)
- ✅ Terms URL returns 200 (loads)
- ✅ Support email receives messages
- ✅ Website loads on iPhone (mobile test)
- ✅ HTTPS works (secure connection)
- ✅ All legal disclaimers present
- ✅ Contact information accurate

---

**This website is your ticket to App Store approval. Take it seriously!**

**Estimated time: 3-5 days**
**Estimated cost: $10-15 (domain)**
**Impact: 100% required for approval**

---

## 🎯 Final Checklist Before App Store Submission

- [ ] Website live at public URL
- [ ] All 10 required pages complete
- [ ] Privacy policy URL in App Store Connect
- [ ] Terms URL in App Store Connect
- [ ] Support URL in App Store Connect
- [ ] Emails working (test them)
- [ ] Mobile responsive
- [ ] Fast loading (<3 seconds)
- [ ] HTTPS enabled
- [ ] In-app links to legal pages added

**When all checked: SUBMIT TO APP STORE ✅**

