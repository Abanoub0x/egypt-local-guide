# egypt-local-guide 🇪🇬

A modern, highly responsive web application acting as a premium digital portal to Egypt's premier historical destinations, scenic adventures, and local discoveries. Engineered using semantic HTML5 structures and production-grade CSS3 layouts, this project implements local asset loading, fluid flexbox components, and adaptive viewport transformations.

---

## 🚀 Live Demo

- **Production URL:** [https://egyptlocalguide.netlify.app/](https://egyptlocalguide.netlify.app/)
- **Repository Link:** [https://github.com/Abanoub0x/egypt-local-guide](https://github.com/your-github-username/egypt-local-guide)

---

## ✨ Features Implemented in Code

* **Immersive Hero Section with Contrast Tinting:** The landing interface utilizes a `min-height: 80vh` viewport layout that features a centered background image layered with a dynamic dual-layer `linear-gradient` overlay (`rgba(0, 0, 0, 0.2)`). This lowers background brightness to dramatically optimize foreground readability.
* **Micro-interactions & 3D Depth Transitions:** The main profile section integrates advanced multi-property transition logic (`0.3s ease`). Upon hover, the component shifts through a mathematical midpoint to smoothly render a `-4px` vertical translation lift (`translateY`), an organic color blend, and an expanded shadow layer (`rgba(0, 0, 0, 0.4)`).
* **Circular Layout Geometry:** Travel showcase items feature high-contrast circular profile imagery (`border-radius: 50%`) calibrated with `object-fit: cover` boundaries, allowing various dimensions of local pictures to fill the layout without distortion or stretching.
* **Modern Flexbox Matrix Control:** Uses distributed layouts (`justify-content: space-around`) alongside native element spacing (`gap: 10px`) to automatically align content items without creating individual element margin conflicts.
* **Mobile Breakpoint Adaptability:** A structured media query breakpoint (`max-width: 768px`) automatically flips complex horizontal user views into vertical stacks (`flex-direction: column`), reducing the hero space and shifting side-paddings into top-margins to preserve compact screens.
* **Contained Text Constraints:** Text cards use responsive percentage boundaries (`width: 90%` / `94%`) combined with hard upper pixel caps (`max-width`) and `margin: 0 auto` to keep headings perfectly scannable and centered on massive ultrawide monitors.

---

## 🛠️ Built With

* **HTML5:** Semantic document tags ensuring clear outline architecture and structural SEO layouts.
* **CSS3:** Advanced responsive rendering rules, backdrop filters, self-hosted font integrations, and layered text-shadow depth.
* **Typography:** Self-hosted, low-latency variable web fonts loaded locally through custom `@font-face` definitions:
  - **Montserrat:** Applied globally for clean, modern interface reading and headings.
  - **Playfair Display:** Utilized selectively for stylized, elegant editorial narratives.

---

## 📂 Project Structure

```text
egypt-local-guide/
├── css/            # Production stylesheets containing web font rules and animations
├── fonts/          # Locally bundled typography assets (Montserrat & Playfair Display)
├── images/         # Optimized photographic elements and graphics
├── index.html      # Main application core file containing semantic element layout
└── README.md       # Technical project documentation and details