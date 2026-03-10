# Reid - Founding Cohort Landing Page

This repository contains a simple, mobile-first static landing page built for Netlify. The goal of this page is to invite qualified real estate agents into the Reid founding cohort.

## Project Structure
- `index.html`: The clean, semantic markup outlining the content structure.
- `styles.css`: The CSS stylesheet powering the modern, premium aesthetic without using heavy frameworks.
- `README.md`: Project documentation.

## Tech Stack
- **HTML5**
- **Vanilla CSS**
- **Fonts**: Inter (Google Fonts)

## Customization & Setup
1. **Typeform Integration**: Open `index.html`, locate the `<div class="typeform-embed-wrapper">` block inside the `form-side` element, and replace the placeholder text with your actual Typeform embed snippet.
2. **Product Visual**: The `#apply` section on the left column currently contains a styled `<div class="mockup-placeholder">`. Swap this element out with an `<img />` tag containing your polished UI screenshot or mockup when ready.

## Design Aesthetic
- **Colors**: Deep dark ink text (`#0C1220`, `#101827`) on a crisp light background (`#F4F6FA`, `#FFFFFF`) with a striking blue accent (`#2563EB`).
- **Typography & Details**: Features a clean system font stack emphasizing geometric precision (Inter), confident tone, and clean spacing. The form layout uses a two-column desktop interface ensuring the focus stays comfortably on conversion.

## Deployment (Founders Subdomain)
Publishing this site to `founders.meetreid.ai` is a breeze since you already have `meetreid.ai` hosted on Netlify. It requires creating a new Site for this repository and pointing a subdomain to it.

1. **Push this code to a new Git repository** (e.g., GitHub, GitLab) under a name like `reid-founders-landing`.
2. **Log into Netlify** and click **Add New Site > Import an existing project**.
3. Select the repository you just created.
4. Leave the build settings blank (there is no build command or output directory needed for static HTML) and click **Deploy Site**.
5. Once deployed, Netlify will give the site a random URL (like `happy-lamport-12345.netlify.app`).
6. Click **Site Settings**, go to **Domain management**, and click **Add a domain**.
7. Type in exactly: `founders.meetreid.ai`.
8. Netlify will detect that you already manage `meetreid.ai` on their platform. It will ask if you want to add this as a subdomain. Confirm by clicking **Add domain**.
9. Netlify will automatically handle the DNS routing and provision the free SSL certificate for you.

Within a few minutes, your landing page will be entirely live and secure at `https://founders.meetreid.ai`!
