# climbing-hold-atlas
A structured dataset and visual project tracking the origin, cost, and story behind climbing holds and gear across global brands.
 
---

## 🌐 Live Site
https://track001.github.io/climbing-hold-atlas/

<details>
<summary>How GitHub Pages works</summary>

GitHub Pages turns this repository into a live website.

- `index.html` = the homepage
- `/data` = JSON files that power the content
- Any changes pushed to `main` automatically update the site

Flow:
1. Edit files in the repo
2. Commit changes
3. GitHub rebuilds the site
4. Updates go live at the URL above

No backend or hosting setup required (:

</details>

---

# Climbing Hold Atlas

A living record of climbing holds, gear, and brands - mapped by origin, cost, and context.

This project starts as a structured dataset and evolves into an interactive visualization of the global climbing industry through a routesetter’s lens in application to "The Tiny Home's Homewall".

Focus:
- where holds come from
- how much they cost
- who makes them
- the relationships behind each purchase

Future direction:
- interactive globe
- brand mapping
- visual timelines

## 🌐 Live Site

- Main site: https://track001.github.io/climbing-hold-atlas/

### 🔗 Data Endpoints (for debugging)

- Brands: https://track001.github.io/climbing-hold-atlas/data/brands.json
- Orders: https://track001.github.io/climbing-hold-atlas/data/orders.json

---

<details>
<summary>⚙️ How this ties into the architecture (and how to debug GitHub Pages)</summary>

### 🧱 Architecture

This project is a static site built with:

- `index.html` → UI + rendering logic
- `data/brands.json` → brand metadata (origin, company info)
- `data/orders.json` → purchase history (items, cost, relationships)

The page loads data at runtime using:

```js
fetch('./data/brands.json')
fetch('./data/orders.json')
