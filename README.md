# IoTeams IIUM — Official Website
## 🌐 Live Website

👉 **[Visit IoTeams IIUM](VERCEL LINK)**

---

## 🌐 Supabase Storage
Project: ioteamskict-club
Database password: IoTeamsCLUBkict

---

## 📁 Project Structure

```
ioteams-website/
├── index.html                  # Homepage
├── 404.html                    # Custom not-found page
├── .gitignore
├── README.md
│
├── pages/
│   ├── our-story.html          # About & team
│   ├── programmes.html         # 3 IoT learning tracks
│   ├── events.html             # Upcoming & past events
│   ├── gallery.html            # Photo & video gallery
│   ├── blog.html               # Blog listing
│   ├── blog-details.html       # Single blog post
│   ├── apply.html              # Membership application
│   └── contact.html            # Contact page
│
├── assets/
│   ├── css/
│   │   └── main.css            # All custom styles
│   ├── js/
│   │   ├── main.js             # Shared JS (nav, scroll, AOS)
│
```

---

## 🚀 Getting Started

### View Locally

```bash
# Clone the repository
git clone https://github.com/YOUR-ORG/ioteams-website.git
cd ioteams-website

# Open with VS Code Live Server (recommended)
code .
# Then: Right-click index.html → Open with Live Server

# OR just open directly in browser
open index.html
```

### Making Changes

```bash
# 1. Always pull latest first
git pull origin main

# 2. Make your changes in VS Code

# 3. Test locally with Live Server

# 4. Commit and push
git add .
git commit -m "Description of your changes"
git push origin main

# GitHub Pages auto-deploys within 1-2 minutes
```

## 🎨 Design System

All design tokens are in `assets/css/main.css` under `:root {}`:

```css
/* Change brand colors here */
--gold:   #C9A84C;   /* Primary accent */
--teal:   #1ABCB0;   /* Secondary accent */
--black:  #0A0A0A;   /* Background */
--white:  #F9F7F2;   /* Text */

/* Change fonts here */
--font-heading: 'Playfair Display', serif;
--font-body:    'DM Sans', sans-serif;
--font-mono:    'Space Mono', monospace;
```

---

## 🌍 Deployment (GitHub Pages)

### First Time Setup

1. Push the project to a GitHub repository
2. Go to **Repository → Settings → Pages**
3. Source: **Deploy from a branch**
4. Branch: **`main`** / **`/ (root)`**
5. Click **Save**

### Rules

- ✅ Always `git pull origin main` before starting work
- ✅ Test locally with Live Server before pushing
- ✅ Use descriptive commit messages
- ✅ Images store via Supabase
- ❌ Never push directly to `main` (use PRs)
- ❌ Never commit API keys or secrets
- ❌ Never push broken or untested code to `main`