# S Designs — Premium Social Media & Web Development Agency

![S Designs](assets/Logo%20(1).png)

A futuristic, high-converting single-page landing site for **S Designs** by Shabir Ahmad — a freelance social media content design and web development business targeting small businesses, restaurants, and cafés.

---

## 🔗 Live Site

**[View Live →](https://s-designs.netlify.app)**

---

## ✨ Features

- **Futuristic Dark Mode UI** — Matte black with neon green + electric blue accents
- **3D Perspective Grid** — Animated infinite scrolling grid floor in the hero
- **Custom Cursor** — Neon ring cursor that expands on interactive elements
- **Glitch Text Effect** — Headline glitches on hover with RGB split
- **Scroll-Triggered Animations** — Elements reveal with smooth transitions via IntersectionObserver
- **Animated Counters** — Stats count up when scrolled into view
- **3D Tilt Cards** — Service cards tilt on mouse movement
- **Horizontal Drag-Scroll Portfolio** — Gallery scrolls sideways with drag interaction
- **Marquee Ticker** — Auto-scrolling service keywords
- **Interactive Testimonials** — Clients can submit reviews via a modal (saved to localStorage)
- **Star Rating System** — Clickable 5-star selector for testimonial submissions
- **Websites Showcase** — Browser-frame mockup cards linking to live projects
- **Working Contact Form** — Powered by [Formspree](https://formspree.io)
- **WhatsApp Integration** — Floating button with pre-filled message
- **Noise Grain Overlay** — Subtle film grain for premium feel
- **Fully Responsive** — Flawless on every device from desktop to mobile

---

## 🎨 Design System

| Token | Value | Usage |
|-------|-------|-------|
| Background | `#000000` / `#030303` | Page background |
| Surface | `#0a0a0a` | Alternate sections |
| Card | `#0e0e0e` | Card backgrounds |
| Text | `#ffffff` | Primary text |
| Grey | `#888888` | Body text |
| Neon Green | `#00ff6a` | Primary accent (~10%) |
| Electric Blue | `#0088ff` | Secondary accent (~5%) |

**Typography:**
- **Headings:** [Orbitron](https://fonts.google.com/specimen/Orbitron) — Futuristic, geometric, uppercase
- **Body:** [Inter](https://fonts.google.com/specimen/Inter) — Clean, readable sans-serif

---

## 📁 Project Structure

```
S designs website/
├── index.html          # Complete single-file landing page (HTML + CSS + JS)
├── README.md           # This file
└── assets/
    ├── Logo (1).png    # S Designs logo
    ├── Heading.png     # About section image
    ├── portfolio-coffee.png
    ├── portfolio-restaurant.png
    ├── portfolio-boutique.png
    └── portfolio-branding.png
```

---

## 🚀 Getting Started

### Option 1: Open Directly
Just double-click `index.html` — it works standalone with no build tools.

### Option 2: Local Server
```bash
# Python
python -m http.server 8888

# Node
npx serve .
```

### Option 3: Deploy to Netlify
1. Push this repo to GitHub
2. Connect to [Netlify](https://netlify.com)
3. Set publish directory to `/` (root)
4. Deploy — done

---

## ⚙️ Configuration

### Contact Form (Formspree)
The form is connected to Formspree. To use your own:
1. Create a free account at [formspree.io](https://formspree.io)
2. Create a new form
3. Replace the form `action` URL in `index.html`:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

### WhatsApp Button
Update the phone number in the WhatsApp link:
```html
<a href="https://wa.me/YOUR_NUMBER?text=YOUR_MESSAGE">
```

### Social Links
Search for these URLs in `index.html` and replace with your own:
- Instagram: `https://www.instagram.com/shabir.designs/`
- Facebook: `https://www.facebook.com/profile.php?id=61573277892570`

---

## 📱 Sections

1. **Hero** — Full-impact headline with 3D grid, floating shapes, and CTA
2. **Marquee** — Auto-scrolling service keywords
3. **About** — Split layout with image, bio, and animated stats
4. **Services** — 2×2 grid with 3D tilt cards (Content, AI Strategy, Branding, Web Dev)
5. **Websites** — Browser-frame cards linking to live client sites
6. **Portfolio** — Horizontal drag-scroll gallery
7. **Testimonials** — Client reviews with interactive submission system
8. **Process** — Vertical timeline (Discovery → Creation → Growth)
9. **Contact** — Working form + email, WhatsApp, Instagram links
10. **Footer** — Logo, copyright, social icons

---

## 🛠️ Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, grid, flexbox, animations, 3D transforms
- **Vanilla JavaScript** — No frameworks, no dependencies
- **Google Fonts** — Orbitron + Inter
- **Formspree** — Form backend
- **localStorage** — Testimonial persistence

---

## 📄 License

© 2026 S Designs by Shabir Ahmad. All rights reserved.

---

## 👤 Author

**Shabir Ahmad**
- 📧 shabirahmad.tech@gmail.com
- 📱 [WhatsApp](https://wa.me/923249116764)
- 📸 [Instagram](https://www.instagram.com/shabir.designs/)
- 📘 [Facebook](https://www.facebook.com/profile.php?id=61573277892570)
