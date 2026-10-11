# IVORY FILMS | Haute Époque Wedding Cinema & Fine Art Stills

An editorial-grade luxury wedding cinematography and still photography portfolio website with tactile paper grain textures, interactive focal-rail galleries, real-time analog grain slider controller, and an atmospheric dark greyish mode.

## ✨ Features
- **Brand Identity:** Refined editorial typography and ligature motifs inspired by French and Italian fine art ateliers.
- **Adjustable Analog Grain:** Full-page film grain texture overlay with a real-time slider controller (0% clean digital to 100% Super 8 tactile grain) and `localStorage` persistence.
- **Dark / Light Theme Switcher:** 
  - **Light Mode:** Subtle antique paper grain (`#e6e3de`) with warm bronze accents (`#6b6440`).
  - **Dark Mode:** Deep warm greyish charcoal slate (`#181715`) with champagne-tinted text (`#c7c2b0`) and charcoal surface cards (`#23221e`).
- **Dynamic Focal-Rail:** Custom horizontal scrolling rails for films (16:9) and photography (4:3) with real-time center-focus scaling.
- **Cinematic Film Lightbox:** Modal video dialog supporting high-definition wedding trailers and short films.
- **Interactive Inquiries:** Multi-day destination wedding inquiry modal with validation and feedback banner.
- **Frequently Asked Questions:** Curated accordion Q&A covering global commissions, deliverables, pricing, and process.
- **Infinite Press Ticker:** Dual-track marquee showcasing features in Vogue, Harper's Bazaar, Brides, The Lane, Over The Moon, etc.
- **Responsive Mobile Navigation:** Sticky header that adapts its label based on the active section in view, paired with a modern mobile bottom navigation bar.

## 🚀 Live Demo
- **GitHub Pages:** [https://mayur-64.github.io/wedding-portfolio-2/](https://mayur-64.github.io/wedding-portfolio-2/)

## 📁 Project Structure
```
wedding-portfolio-2/
├── index.html           # Main editorial website with embedded styles & logic
├── .nojekyll            # Ensures clean asset serving on GitHub Pages
├── README.md            # Project documentation
└── assets/
    ├── favicon.svg      # Atelier monogram favicon
    ├── hero-loop.mp4    # Optional background / teaser footage
    └── images/          # Curated WebP photography & film stills
```

## 🛠 Local Preview
```bash
python3 -m http.server 8102 --directory /root/wedding-portfolio-2
```
