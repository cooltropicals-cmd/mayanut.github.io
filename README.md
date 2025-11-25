# The MayaNut Company Website

Welcome to the source code for **The MayaNut Company** (https://mayanut.com) – a static, multi-language website introducing MayaNut beverages and the tropical tree *Brosimum alicastrum*.

The site is designed for **GitHub Pages** (or any static host) and is built with plain **HTML, CSS, and vanilla JavaScript** – no build tools required.

---

## Features

- **Hero section** with animated gradient background, snowflake overlay, and a call-to-action button linking to the Store section.
- **MayaNut beverage hero layout**  
  - Desktop: Text image on the left, glass image on the right, CTA and arrow in a 2×2 “square” layout.  
  - Mobile: Text and button on the left, glass and arrow on the right, all scaled down for small screens.
- **Multi-language support** (via separate HTML files) with a Language dropdown:
  - English (`index.html`)
  - Español (`index-es.html`)
  - Português (`index-pt.html`)
  - Français (`index-fr.html`)
  - Deutsch (`index-de.html`)
  - Italiano (`index-it.html`)
  - Русский (`index-ru.html`)
  - 中文 (`index-zh.html`)
  - 日本語 (`index-ja.html`)
  - हिन्दी (`index-hi.html`)
  - اردو (`index-ur.html`)
  - বাংলা (`index-bn.html`)
  - Bahasa Indonesia (`index-id.html`)
  - العربية (`index-ar.html`)
  - Kiswahili (`index-sw.html`)
  - Hausa (`index-ha.html`)
  - Filipino (`index-fil.html`)
  - Yorùbá (`index-yo.html`)
- **Store preview section**  
  Placeholder products and images that represent future MayaNut beverages, powders, and flours.
- **About section**  
  Multiple cards describing:
  - The MayaNut Company
  - Founder August Kokus
  - Where the trees are being grown
  - Mission and fascination with *Brosimum alicastrum*
- **Image expand / lightbox** in the About section for key images (fruit, trees, nursery, founder).
- **Top navigation bar** with:
  - Holiday greeting
  - Centered logo on mobile
  - Language selector (with hover highlight)
  - Fixed hamburger menu (works on desktop and mobile)
- **Full-screen navigation modal** with links:
  - HOME, STORE, ABOUT (on-page anchors)
  - RESEARCH, BLOG, FAQ, CONTACT (external/internal pages)
- **Ricky Easter Egg**  
  In the navigation modal, the logo can be dragged to reveal a hidden dedication text, and clicking the “Ricky” image returns to the main hero.
- **Welcome popup**  
  A one-time welcome message explaining the plantation and rough timeline.
- **Chat assistant (FAQ bot)**  
  A small chat bubble in the bottom-right that opens a panel answering simple questions about:
  - MayaNut / *Brosimum alicastrum*
  - The company and founder
  - Where it grows
  - Research page (`research.html`) for scientific info
- **Footer**  
  - Privacy Policy & “Do Not Sell My Info” links open a small modal.
  - Instagram icon linked to the official account.
  - Copyright notice.

---

## File Structure

The exact structure can vary, but a typical layout:

```text
.
├── index.html               # English main page
├── index-es.html            # Spanish
├── index-pt.html            # Portuguese
├── index-fr.html            # French
├── index-de.html            # German
├── index-it.html            # Italian
├── index-ru.html            # Russian
├── index-zh.html            # Chinese
├── index-ja.html            # Japanese
├── index-hi.html            # Hindi
├── index-ur.html            # Urdu
├── index-bn.html            # Bengali
├── index-id.html            # Bahasa Indonesia
├── index-ar.html            # Arabic
├── index-sw.html            # Swahili
├── index-ha.html            # Hausa
├── index-fil.html           # Filipino
├── index-yo.html            # Yoruba
├── research.html            # Research page (optional / WIP)
├── blog.html                # Blog page (optional / WIP)
├── faq.html                 # FAQ page (optional / WIP)
├── contact.html             # Contact page (optional / WIP)
├── mayanut-the-maya-nut-company-logo.png
├── the-maya-nut-company-favicon-logo.png
├── mayanut-maya-nut-beverage-brosimum-alicastrum.png
├── rach20.png               # Hero glass image
├── arrow-the-maya-nut-company-mayanut.png
├── ricky.jpeg               # Easter egg image
├── maya-nut-mayanut-fruit-brosimum-alicastrum.jpg
├── august-kokus-augustkokus-mayanut-brosimum-alicastrum.jpg
├── maya-nut-mayanut-plant-tree-nursery.jpg
├── maya-nut-mayanut-plant-tree-moraceae.jpg
└── README.md
