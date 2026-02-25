# My PDF Reader - Product Website

This folder contains the complete source code for the "My PDF Reader" product website. It is designed to be hosted for free on **GitHub Pages**.

## 📂 File Structure

- **`index.html`**: The main landing page. Contains:
  - Hero section with "Download" CTA.
  - "Why Choose Us" features.
  - **Downloads**: Primary (Universal) and Advanced (Architecture-specific).
  - **Security**: Checksum placeholders and VirusTotal badges.
  - **Help & FAQ**: Explanations for Permissions, Large Files, and Rescan.
- **`privacy.html`**: A standalone Privacy Policy page compliant for Play Store distribution.
- **`css/style.css`**: Main stylesheet using the App's Blue branding (`#3591DD`) and responsive design.
- **`js/main.js`**: Handles smooth scrolling for navigation links.

---

## 🚀 Deployment Guide (GitHub Pages)

You can publish this website in less than 2 minutes using GitHub Pages.

### Option 1: The Easiest Way (Move to `/docs`)
GitHub Pages natively supports serving from a folder named `/docs` in the root of your repository.

1. **Rename** this folder from `/website` to `/docs`.
2. Commit and Push the changes to GitHub.
3. Go to your GitHub Repository **Settings > Pages**.
4. Under **Source**, select **Deploy from a branch**.
5. Select your branch (e.g., `main` or `master`).
6. In the folder dropdown, select `/docs`.
7. Click **Save**.

### Option 2: Using GitHub Actions (Keep `/website`)
If you prefer to keep the folder named `/website`:

1. Go to **Settings > Pages**.
2. Under **Source**, select **GitHub Actions**.
3. Create a workflow that specifically targets the `/website` directory.

### Step 3: Verify
Once saved, GitHub will provide a URL (e.g., `https://yourusername.github.io/your-repo/`). Click it to verify your live site!

---

## 🛠 Future Improvements

1. **SEO**: Update the `<meta name="description">` tags in `index.html` with more specific keywords as you grow.
2. **Analytics**: Add Google Analytics or a privacy-focused alternative to track download clicks.
3. **Checksums**: When you release new versions, update the `[PENDING_BUILD_HASH]` placeholders in `index.html` with the actual SHA-256 output of your APKs to build developer trust.

---
*Built with ❤️ for My PDF Reader*
