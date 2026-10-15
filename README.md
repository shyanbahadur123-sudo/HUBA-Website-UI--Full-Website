# HUBA Nepal — Pure HTML5 & CSS3 Website UI Recreation

A pixel-perfect UI recreation of the official [HUBA Nepal](https://www.hubanepal.com/) website, built strictly using **HTML5 and CSS3 only** with zero JavaScript, zero frameworks, and zero build tool dependencies.

---

## 🏔️ Project Overview

- **Reference Website:** [https://www.hubanepal.com/](https://www.hubanepal.com/)
- **Brand:** HUBA Nepal (High-altitude technical apparel, Himalayan gear, streetwear, kids wear, accessories & perfumes crafted in Nepal)
- **Technology:** Pure **HTML5** & **CSS3**
- **Architecture:** 100% Static Web Application (no Node.js, npm, Vite, React, or JavaScript required)

---

## 📁 Project Structure

```
HUBA-Website-UI/
│
├── index.html           # Main semantic HTML5 webpage
├── style.css            # Complete responsive CSS3 stylesheet
├── README.md            # Project documentation and deployment guide
├── .gitignore           # Git ignore rules
│
└── assets/              # Local brand imagery and icons
    ├── delivery.png     # Worldwide Delivery feature badge
    ├── huba-logo.png    # Official HUBA brand monogram logo
    ├── huba-street.png  # Streetwear collection emblem
    ├── huba-street.jpg  # Streetwear graphic
    ├── hubakids-logo.png# HUBA Kids collection emblem
    ├── made-in-nepal.png# Made in Nepal authentic badge
    ├── refund.png       # Exchange & Refund guarantee badge
    └── icons/           # Additional icon assets
```

---

## 🎨 Sections Recreated

Every visible section from the original homepage is reproduced with pixel-level precision:

1. **Announcement Bar:** Festive notice banner with Dashain festive offer view trigger.
2. **Sticky Navigation Header:** Brand wordmark, desktop dropdown menus, and utility links (Search, About Us, Account, Cart).
3. **Hero Section:** High-resolution campaign banner, responsive typography, and outline CTA button.
4. **The Pre Fall Edit:** Product showcase with rounded product cards, pricing in NPR, Dashain discount badges, and quick-action buttons.
5. **New Arrivals & Trending:** Pure CSS tabbed switcher showcasing latest releases and bestsellers.
6. **Simulation Collection:** Full-width campaign banner and technical outerwear product grid.
7. **Streetwear Collection:** Urban apparel showcase featuring authentic Streetwear brand badge.
8. **HUBA Kids:** Youth collection campaign banner and apparel cards.
9. **Winter Collection:** High-fashion campaign banner and editorial layout.
10. **Accessories (Caps & Bags):** Dual-category showcase with pure CSS tab selection.
11. **HUBA X LE ARDOR Perfumes:** Solarin & Lunaris Eau de Parfum crafted in Nepal.
12. **Flagship Retail Stores:** Architectural photography and contact information for 6 retail locations (Lalitpur, Chitwan, Pokhara, Damak, Bhaktapur, Butwal).
13. **Effortless Shopping & Brand Pillars:** Worldwide Delivery, Made in Nepal local craftsmanship, and Exchange & Refund guarantees.
14. **Footer:** Monogram brand crest, multi-column navigation links, customer service info, and copyright notice.
15. **Interactive Modals (Pure CSS):** Search modal, account modal, bag drawer, quick view modal, and Dashain offer popup powered completely by CSS `:target` and checkbox toggles.

---

## 🚀 How to Run the Website

Because this project is built entirely in **pure HTML5 and CSS3**, there are **no dependencies to install and no build commands required**.

### Option 1: Direct File Open (Easiest)
1. Download or clone this repository to your computer.
2. Double-click **`index.html`** or right-click and select **"Open with"** -> your preferred web browser (Google Chrome, Firefox, Safari, Edge).
3. The website will load and function immediately!

### Option 2: Using Any Local Static Server (Optional)
If you prefer running a local HTTP server:
```bash
# Python 3
python3 -m http.server 8000

# or with PHP
php -S localhost:8000
```
Then visit `http://localhost:8000` in your browser.

---

## 🌐 How to Publish on GitHub Pages

Publishing this website for free on GitHub Pages takes less than a minute:

1. **Push your code to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit of HUBA Nepal HTML/CSS website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/HUBA-Website-UI.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub.
   - Click on **Settings** > **Pages** (in the left sidebar).
   - Under **Build and deployment** -> **Source**, select **Deploy from a branch**.
   - Under **Branch**, select `main` and folder `/ (root)`.
   - Click **Save**.

3. **View your live website**:
   - Within 1–2 minutes, GitHub will generate your live URL:
     `https://<your-username>.github.io/HUBA-Website-UI/`

---

## 📱 Responsive Design

The layout is built with standard CSS Flexbox, CSS Grid, and media queries:
- **Desktop & Widescreen:** 1440px+ and 1920px
- **Laptops:** 1024px – 1366px
- **Tablets:** 768px – 1024px
- **Mobile Phones:** 320px – 480px (with mobile drawer navigation)

---

## 📄 License & Attribution

This website recreation is built for educational and demonstration purposes. All brand assets, logos, and imagery remain the property of [HUBA Nepal](https://www.hubanepal.com/).
