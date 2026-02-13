# Up To Here, Inc. Website
### www.uptohere.org

> *Every battle, every triumph, every moment led you up to here.*

A one-page, responsive website for **Up To Here, Inc.** — a nonprofit dedicated to empowering and inspiring women veterans through holistic wellness and peer-to-peer support.

---

## 🚀 Quick Deploy to GitHub Pages

### Step 1 — Create a GitHub Repository
1. Go to [github.com](https://github.com) and log in
2. Click **New Repository**
3. Name it `uptohere.org` (or your preferred name)
4. Set to **Public**
5. Click **Create repository**

### Step 2 — Upload Files
Upload all files in this folder to the repository root:
- `index.html` ← main website
- `README.md` ← this file
- `logo1.png`, `logo2.png` ← logos
- `3.png`, `4.png`, `6.png`, `7.png`, `8.png` ← site images
- `profile.png` ← profile photo

### Step 3 — Enable GitHub Pages
1. In your repository, go to **Settings → Pages**
2. Under **Source**, select **Deploy from a branch**
3. Set branch to `main` and folder to `/ (root)`
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io/uptohere.org`

### Step 4 — Connect Custom Domain (uptohere.org)
1. In GitHub Pages settings, add your custom domain: `uptohere.org`
2. Add a `CNAME` file to your repo with the content: `uptohere.org`
3. In your domain registrar (GoDaddy, Namecheap, etc.), add DNS records:
   ```
   A     @     185.199.108.153
   A     @     185.199.109.153
   A     @     185.199.110.153
   A     @     185.199.111.153
   CNAME www   yourusername.github.io
   ```

---

## 🌐 Deploy to Cloudflare Pages (Alternative)

1. Push your code to GitHub (steps 1-2 above)
2. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
3. Click **Create a project → Connect to Git**
4. Select your repository
5. Build settings:
   - **Framework**: None
   - **Build command**: (leave empty)
   - **Output directory**: `/`
6. Click **Save and Deploy**
7. Connect your domain in Cloudflare DNS settings

---

## 📁 File Structure

```
uptohere/
├── index.html        # Main one-page website
├── README.md         # This file
├── logo1.png         # Colorful gradient logo
├── logo2.png         # Blue circle logo
├── profile.png       # Profile photo
├── 3.png             # Women community photo
├── 4.png             # Hands raised hero photo
├── 6.png             # Celebration/confetti photo
├── 7.png             # Woman veteran saluting
└── 8.png             # Colorful logo variant
```

---

## 🎨 Brand Colors

| Color | Hex | Usage |
|-------|-----|-------|
| Blue | `#2C99E5` | Primary brand, CTAs |
| Hot Pink | `#BA1F19` | Accent |
| Gold | `#F7931E` | Highlights, secondary CTAs |
| Dark | `#0a0e1a` | Background |

**Fonts:** Poppins ExtraBold (headings) · Podkova Regular (body)

---

## ✉️ Contact

Update the email address throughout `index.html` if it changes from `moreinfo@uptohere.org`.

For form submissions, consider integrating [Formspree](https://formspree.io) or [Netlify Forms](https://www.netlify.com/products/forms/) for free form handling without a backend.

---

©2026 Up To Here, Inc. All rights reserved.
