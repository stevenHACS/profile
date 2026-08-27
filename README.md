# Steven Ter - Professional Resume Website

A modern, clean, and professional personal resume portfolio website designed for **Steven Ter** (Senior Scrum Master & Agile Delivery Lead). Built with an executive aesthetic—free of gimmicks, lightweight, responsive, dark/light theme aware, and print/PDF-optimized.

---

## 🌟 Key Features

- **Executive Aesthetic**: Clean Swiss typography, crisp spacing, subtle status badges, and an understated corporate palette.
- **Accurate Career Record**: Fully details all roles, achievements, and metrics (ANZ GenAI Enablement & ECC Amazon Connect, Medibank Mobile & Messaging, Victorian Dept of Health, Source Agility/CES, EnergyAustralia, DB Results, TAL).
- **Recruiter & Executive Optimizations**:
  - **Category Filtering**: Instant filtering by *All*, *GenAI & Innovation*, *Banking & Finance*, *Health & Government*, *Agile Coaching & CoE*.
  - **Live Search**: Instant keyword filtering across all roles, competencies, and achievements.
  - **High-Impact Metric Badges**: Highlights 54% cycle time reduction, 85% GenAI intent matching, 80+ person PI planning.
  - **1-Click Copy**: Fast clipboard copying for email and phone number with subtle toast notifications.
  - **Dedicated Print / PDF Stylesheet**: Clicking "Export PDF" or pressing `Ctrl + P` / `Cmd + P` prints an ultra-clean, un-cluttered 2-3 page executive resume formatted specifically for recruiters and ATS.
  - **Dark / Light Mode**: Smooth theme toggling with system preference auto-detection.

---

## 🚀 How to Preview Locally

Because this site uses zero-dependency vanilla web standards, you can preview it instantly:

1. **Option 1 (Instant)**: Simply double-click `index.html` in your file explorer to open it in your browser.
2. **Option 2 (Local Server)**: Run any local HTTP server in this directory:
   ```bash
   npx serve .
   # or
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` (or `http://localhost:3000`) in your browser.

---

## 🌐 How to Publish Online for FREE (Choose Any Option)

### Option 1: GitHub Pages (Recommended - 2 Minutes)

1. Create a new repository on [GitHub](https://github.com/new) (e.g. `steven-ter-resume` or `steventer.github.io`).
2. Upload all files from this folder (`index.html`, `css/`, `js/`, `README.md`) to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of resume website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   git push -u origin main
   ```
3. In your GitHub repository:
   - Go to **Settings** > **Pages** (in the left sidebar).
   - Under **Build and deployment** > **Branch**, select `main` and `/ (root)`.
   - Click **Save**.
4. Your website will be live in ~30 seconds at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME`!

---

### Option 2: Netlify (Drag & Drop - 30 Seconds)

1. Go to [Netlify Drop](https://app.netlify.com/drop).
2. Drag and drop this entire folder (`Gemini Projects`) into the browser window.
3. Your site will instantly be live at a custom URL (e.g. `steven-ter.netlify.app`), with free HTTPS and custom domain support.

---

### Option 3: Vercel (1-Click)

1. Install Vercel CLI or connect via [Vercel Dashboard](https://vercel.com).
2. Run `npx vercel` in this folder, or import your GitHub repository into Vercel.
3. Deploy!

---

## 📄 Custom Domain Setup (Optional)

If you own a custom domain (e.g., `steventer.com` or `steventer.me`):
1. In your GitHub Pages / Netlify / Vercel settings, go to **Custom Domains** and type in your domain.
2. Add a CNAME record at your domain registrar (Namecheap, GoDaddy, Cloudflare, Google Domains) pointing to your deployment target.

---

## 🛠️ File Structure

```text
├── index.html          # Main HTML structure with semantic sections & SEO schema
├── css/
│   └── style.css       # Custom variables, dark mode styling, and @media print rules
├── js/
│   └── main.js         # Theme toggle, search, category filters, and copy toasts
└── README.md           # Instructions for previewing, publishing, and maintaining
```

---

## ✏️ Making Future Updates

- **Add a new role**: Open `index.html`, navigate to the `<!-- Timeline Container -->` inside the `<section id="experience">`, and add or update a `.experience-item` card.
- **Update contact info**: Update the phone and email inside both the Hero card and the Contact section in `index.html`.
