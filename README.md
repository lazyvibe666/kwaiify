# Kwaiify - Premium Link Directory

A modern, aesthetically pleasing, and highly functional directory of over 200+ useful websites. Built with a sleek Glassmorphism UI, intelligent art-aware responsive layouts, and seamless category filtering.

## 🌟 Features

* **Glassmorphism UI:** Premium Apple-style frosted glass cards, floating headers, and deep-blur modal overlays.
* **Intelligent Art-Aware Layout:** The layout dynamically shifts to the right on desktop to ensure the beautiful background artwork is never obscured. On mobile, a massive bottom padding allows users to scroll past the content to reveal the artwork seamlessly.
* **Instant Search & Keyboard Shortcuts:** Instantly filter 200+ websites by name or description. Use `Cmd+K` (or `Ctrl+K`) to instantly focus the search bar.
* **Dynamic Category Filtering:** Swipeable category bar with horizontal scrolling. The redundant genre tags on individual cards dynamically hide when browsing a specific category to keep the UI clean.
* **Premium Login Modal:** A beautifully crafted, deep-blur social login modal featuring refined gradients and micro-animations.
* **Hardware Accelerated Animations:** Buttery smooth card hover effects that utilize 3D transforms (`translate3d`) to prevent rendering glitches on modern browsers.
* **Zero Dependencies:** Built entirely with vanilla HTML, CSS, and JavaScript. No build steps or heavy frameworks required.

## 📂 Project Structure

* `index.html` - The core application file containing all layout, CSS, JavaScript logic, and the embedded JSON database of 200+ hand-curated links.
* `logo_transparent.png` - The transparent logo.
* `bg_new.png` - The beautiful pastel pink background artwork.
* `bg.jpg` - The legacy kawaii background.

## 🚀 How to Run

Since Kwaiify is built with vanilla web technologies, you can run it instantly without any complex setup!

1. Clone or download this repository.
2. Open `index.html` directly in any modern web browser (Chrome, Safari, Firefox).
3. **Optional (For Local Server):** If you want to run it via a local web server (useful for certain browser security policies with local files):
   ```bash
   python3 -m http.server 8000
   ```
   Then navigate to `http://localhost:8000` in your browser.

## 🎨 Technologies Used

* **HTML5:** Semantic structure and accessibility.
* **CSS3:** Advanced Grid/Flexbox layouts, CSS Variables, `backdrop-filter`, and CSS Masks for edge fading.
* **JavaScript (ES6):** Dynamic rendering, search filtering, and DOM manipulation.
* **FontAwesome:** For crisp, scalable icons.
* **Google Fonts:** Utilizing 'Poppins' for a clean, modern geometric look.
* **Google S2 Favicon API:** Automatically fetches high-quality favicons for all 200+ websites dynamically.

