# 🍜 Tasty Food — Food Delivery Website

> *"Night-market neon on butcher paper."*
> A premium food delivery landing page built with the **Street Food** design system.

---

## 📸 Preview

Open `index.html` directly in your browser to view the full website.
Requires an active internet connection for Google Fonts & Unsplash images.

---

## 🎨 Design Language — Street Food Theme

This project follows a carefully crafted **flat design system** inspired by the warmth of street food markets — think butcher paper textures, neon signage accents, and bold slab typography.

### 🎯 Core Principles

| Principle | Rule |
|-----------|------|
| 🚫 **No Gradients** | The system is intentionally flat — gradients are not allowed |
| 🔴 **Single Accent Rule** | Only ONE accent color (`#F23C3C`) drives all interactions |
| 🫧 **Negative Space** | Let the warm neutral background breathe — whitespace is a feature |
| ✨ **Micro-animations** | Subtle hover lifts, shadow reveals, and scroll-triggered fade-ins |

### 🖌️ Color Palette

```
┌──────────────────────────────────────────────────────┐
│                                                      │
│   ██████  Primary     #1A0F05   Headlines & text     │
│   ██████  Secondary   #7A6A54   Borders & captions   │
│   ██████  Tertiary    #F23C3C   CTA accent (ONE!)    │
│   ██████  Neutral     #F5E9CF   Page background      │
│   ██████  Surface     #FCF3DC   Card backgrounds     │
│   ██████  On-Primary  #FCF3DC   Text on dark/accent  │
│                                                      │
└──────────────────────────────────────────────────────┘
```

### 🔤 Typography

| Style | Font | Size | Weight | Usage |
|-------|------|------|--------|-------|
| **Display** | Bowlby One | `4.5rem` | 400 | Hero headline only |
| **H1** | Bowlby One | `2.4rem` | 400 | Section headings |
| **Body** | DM Sans | `1rem` | 400 | Paragraphs & descriptions |
| **Label** | DM Sans | `0.78rem` | 700 | Tags, badges, uppercase captions |

> 💡 Both fonts are loaded from [Google Fonts](https://fonts.google.com/) via `<link>` in the HTML `<head>`.

### 📐 Spacing & Rounding

| Token | Value | Usage |
|-------|-------|-------|
| `spacing-sm` | 8px | Tight gaps, tag padding |
| `spacing-md` | 16px | Standard gaps between elements |
| `spacing-lg` | 32px | Section padding, large gaps |
| `rounded-sm` | 4px | Badges, tags |
| `rounded-md` | 8px | Buttons, inputs |
| `rounded-lg` | 14px | Cards, form containers |

---

## 📄 File Structure

```
📂 CSS selectors/
├── 📄 index.html      → Full website markup (semantic HTML5)
├── 🎨 style.css       → Complete stylesheet (design tokens + components)
└── 📖 README.md       → You are here!
```

---

## 🏗️ Website Sections

The page is structured into **10 distinct sections**, each serving a clear purpose:

| # | Section | Description | Key Element |
|---|---------|-------------|-------------|
| 1️⃣ | **Navbar** | Sticky navigation with blur backdrop | 🔴 "Order Now" CTA button |
| 2️⃣ | **Hero** | Full-viewport with food photography overlay | Display headline + stats bar |
| 3️⃣ | **How It Works** | 3-step onboarding flow | 📱 Browse → 🛒 Order → 🍽️ Enjoy |
| 4️⃣ | **Best Sellers** | 4-column food card grid | Price, rating, badge, hover zoom |
| 5️⃣ | **Stats** | Dark banner with key metrics | 25+ Cities · 500+ Restaurants · 2M+ Orders |
| 6️⃣ | **Restaurants** | Horizontal restaurant cards | Cuisine tags, ratings, delivery time |
| 7️⃣ | **Testimonials** | 3 customer review cards | Star ratings + avatar initials |
| 8️⃣ | **CTA Banner** | Red accent conversion section | Single "Start Ordering Now" button |
| 9️⃣ | **Contact** | Side-by-side info + form | Name, phone, email, subject, message |
| 🔟 | **Footer** | 4-column footer | Links, social, legal, copyright |

---

## 🖼️ Images — Real Photography

All images are sourced from **[Unsplash](https://unsplash.com/)** — no placeholders or dummy icons.

| 🍽️ Image | 📷 What It Shows |
|----------|-----------------|
| Hero Background | Gourmet food spread on a rustic table |
| Biryani Card | Aromatic chicken biryani in a copper handi |
| Pizza Card | Freshly baked farmhouse pizza with melted cheese |
| Tacos Card | Crunchy chicken tacos with fresh salsa |
| Brownie Card | Belgian chocolate brownie with vanilla ice cream |
| Royal Kitchen | Butter chicken curry with naan bread |
| Pizza Paradise | Classic Italian pizza with fresh toppings |
| Dragon Wok | Asian stir-fry noodles in a wok |
| Burger Barn | Juicy gourmet burger with lettuce and cheese |

---

## ⚙️ Tech Stack

| Layer | Technology |
|-------|-----------|
| 📐 **Structure** | HTML5 (Semantic elements) |
| 🎨 **Styling** | Vanilla CSS (Custom Properties, Flexbox, Grid) |
| ✨ **Animations** | CSS `@keyframes` + `IntersectionObserver` API |
| 🔤 **Fonts** | Google Fonts (Bowlby One, DM Sans) |
| 🖼️ **Images** | Unsplash CDN |
| 📱 **Responsive** | 3 breakpoints — Desktop · Tablet · Mobile |

---

## 📱 Responsive Breakpoints

```
Desktop (default)    → Full layout, 4-col food grid, 2-col restaurants
Tablet  (≤ 1024px)  → 2-col food grid, single-col restaurants
Mobile  (≤ 768px)   → Single column everything, hamburger nav menu
```

---

## ✅ Do's and Don'ts

### ✅ Do

- ✅ Use Tertiary (`#F23C3C`) for **exactly one** primary action per screen
- ✅ Let the Neutral background carry the composition — negative space is a feature
- ✅ Keep typography consistent — Bowlby One for display, DM Sans for everything else
- ✅ Use real food photography — no clip art or placeholder icons

### ❌ Don't

- ❌ Introduce gradients — this system is flat on purpose
- ❌ Mix Tertiary with alternate accent colors — the single-accent rule is load-bearing
- ❌ Use more than 2 font families — the type system is intentionally constrained
- ❌ Add heavy shadows or 3D effects — keep it clean and paper-like

---

## 🚀 How to Run

1. 📂 Navigate to the `CSS selectors` folder
2. 🖱️ Double-click `index.html` (or right-click → Open With → Chrome)
3. 🌐 Make sure you have an **active internet connection** for fonts & images
4. 🎉 Enjoy the full **Tasty Food** experience!

---

## 👨‍💻 Author

Built as a learning project exploring **CSS selectors**, **design systems**, and **modern web layout techniques**.

---

<p align="center">
  Made with ❤️ and 🍕 by the Tasty Food team
</p>
