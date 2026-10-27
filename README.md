# ☕ Aravali Brew Cafe

A bilingual (English and Hindi), fully responsive website for **Aravali Brew Cafe**, a specialty coffee cafe in Ajmer, Rajasthan. Built with plain HTML and CSS, with no frameworks and no JavaScript.

🔗 **Live site:** https://adhyyanverma9080-max.github.io/Aravali-Brew-cafe-/


<!-- Add screenshots to assets/images/ and uncomment the lines below -->
<!-- ![Home page](assets/images/screenshot-home.png) -->
<!-- ![Menu page](assets/images/screenshot-menu.png) -->

---

## ✨ Features

- **Bilingual:** every page is available in English and Hindi, with an EN | हिंदी toggle in the header.
- **Responsive design:** works on phones, tablets and desktops, with a pure-CSS hamburger menu on small screens.
- **Interactive menu without JavaScript:** Drinks, From the Kitchen and Something Sweet tabs use the CSS `:target` selector. Clicking an item shows its photo using hidden radio buttons.
- **Print-friendly menu:** printing `menu.html` or `menu-hindi.html` produces a clean black-and-white A4 page with no header, photos or footer.
- **Photo gallery:** a CSS grid layout with hover effects and captions.
- **Contact and booking page:** table request form, opening hours, phone, email and WhatsApp link, plus an embedded Google Map and a "Get directions" link.
- **Smooth animations:** rise, fade and wipe effects written in CSS only.

---

## 📄 Pages

| Page | English | Hindi |
|---|---|---|
| Home | `index.html` | `index-hindi.html` |
| Menu | `menu.html` | `menu-hindi.html` |
| Gallery | `gallery.html` | `gallery-hindi.html` |
| Our Story | `our-story.html` | `our-story-hindi.html` |
| Contact / Reserve a table | `contact.html` | `contact-hindi.html` |

---

## 🎨 Design

**Colour palette**

| Colour | Hex | Use |
|---|---|---|
| Charcoal green | `#252B29` | Page background, header |
| Warm cream | `#F4EEE3` | Text, menu section background |
| Amber | `#F2A93B` | Highlights, buttons, links |
| Burnt orange | `#B8692F` | Prices and links on cream |
| Deep green | `#202624` | Footer |

**Fonts**

- **Playfair Display:** headings
- **Cormorant Garamond:** italic accents, prices, captions
- **DM Sans:** body text, navigation, forms

Icons come from [Font Awesome](https://fontawesome.com/) (loaded from a CDN).

---

## 🗂️ Project structure

```
Aravali-Brew-cafe-/
├── index.html
├── index-hindi.html
├── menu.html
├── menu-hindi.html
├── gallery.html
├── gallery-hindi.html
├── our-story.html
├── our-story-hindi.html
├── contact.html
├── contact-hindi.html
├── README.md
└── assets/
    ├── style.css          # one shared stylesheet for all pages
    └── images/
        ├── logo.png
        ├── menu/          # food and drink photos
        └── gallery/       # gallery photos
```

---

## 🚀 Run locally

1. Clone the repository:
   ```bash
   git clone https://github.com/adhyyanverma9080-max/Aravali-Brew-cafe-.git
   ```
2. Open the folder and double-click `index.html`, or use the **Live Server** extension in VS Code.

No build step or dependencies are needed.

---

## 🌐 Deployment

The site is hosted with **GitHub Pages**:

1. Go to **Settings → Pages**.
2. Set the source to the `main` branch and the root folder.
3. Save. The site goes live at the URL above after a minute or two.

> **Tip:** if CSS changes don't show up after deploying, hard refresh with `Ctrl + Shift + R`, or add a version number to the stylesheet link, for example `assets/style.css?v=2`.

---

## 🖨️ Printing the menu

Open the menu page and press `Ctrl + P`. The print styles (`@media print` in `style.css`) hide the navigation, tabs, photos and footer. They list Drinks, From the Kitchen and Something Sweet with their prices on a clean A4 page.

---

## 📍 About the cafe

**Aravali Brew Cafe**, established 2017
Central Hub, Jaipur Road, opposite Patel Stadium, Hathi Bhata, Ajmer, Rajasthan 305001

- 📞 +91 63771 18119
- ✉️ hello@aravalibrew.cafe
- 📷 Instagram: [@aravalibrews](https://www.instagram.com/aravalibrews/)

**Opening hours**
- Monday to Friday: 8:00 AM to 10:00 PM
- Saturday and Sunday: 8:00 AM to 11:00 PM

---

## 🛠️ Built with

- HTML5
- CSS3 (Grid, Flexbox, custom animations, media queries, print styles)
- Font Awesome
- Google Maps embed

---

## 👤 Author

**Adhyyan Verma & Rajat sharama **

---

## 📜 License

This project was created for educational purposes. Cafe name, logo and photos belong to Aravali Brew Cafe. Add a license here if you plan to share the code publicly, for example MIT.
