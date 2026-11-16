# TJsmartnews Theme

A modern, responsive Bangla news portal theme built with a classic newspaper aesthetic. Cleanly separated and semantically structured, this theme is production-ready for integration into **WordPress**, **Next.js**, or **Laravel Blade**.

---

## ✨ Theme Highlights

| Feature | Description |
| :--- | :--- |
| **Masthead** | Bold Bangla logo **"টিজে স্মার্ট নিউজ"** paired with a tagline in *Noto Serif Bengali* |
| **Top Bar** | Displays the Bangla date (`১ অগ্রহায়ণ ১৪৩৩`), local weather, and quick navigation links |
| **Breaking Ticker** | Animated scrolling news ticker featuring a high-contrast red **"ব্রেকিং"** badge |
| **Hero Layout** | `2/3 + 1/3` grid layout — main featured story alongside a sidebar (Most Read, Ad space, Newsletter signup) |
| **Category Sections** | Dedicated sections for **সর্বশেষ**, **মতামত**, **ভিডিও**, **রাজনীতি**, and **খেলা** — each with distinct visual styling |
| **Color Palette** | Deep red (`brand-600`) accents on crisp white and ink surfaces for a classic Bangla newspaper feel |
| **Typography** | **Noto Serif Bengali** for editorial headlines + **Hind Siliguri** for clean, readable body copy |
| **Responsive Design** | Mobile-first architecture that adapts and collapses gracefully across all screen sizes |

---

## 🎨 Customization Tips

* **Change Brand Color:** Update `brand-500` and `brand-600` in your `tailwind.config.js` file (e.g., use `#0ea5e9` for blue or `#059669` for green).
* **Swap Logo:** Replace the `<h1>` masthead block with an `<img>` tag to use a custom graphic logo.
* **Add Dark Mode:** Append Tailwind `dark:` utility variants to components — the layout structure is already built to support dark themes.
* **Connect a Real Backend:** Replace the static article cards with dynamic loops from your preferred CMS or framework (WordPress Loop, Laravel `@foreach`, or Next.js `.map()`).

---

## 🚀 Framework Readiness

All sections and UI components are modular and semantically marked up, making it straightforward to port into:
- **WordPress** (Custom Theme / Block Theme)
- **Next.js** (React Components / App Router)
- **Laravel** (Blade Templates)