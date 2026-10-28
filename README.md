# Pure CSS Admin Dashboard

A lightweight, responsive admin panel dashboard interface built using **pure HTML5 and CSS3**. This project focuses on fundamental CSS layout models, stacking context management (`z-index`), custom table design, and pure CSS interactive components without relying on JavaScript or external CSS frameworks.

## 🚀 Key Features

* **Pure CSS Dropdown Menu:** Interactive navigation dropdown built strictly with CSS `:hover` states and positioning selectors.
* **Layer & Stacking Management:** Fixed header layout with correct `z-index` layering to ensure seamless dropdown overlay above table elements.
* **Vertical Sidebar:** Dedicated side navigation menu with active and hover states (`:not(.active)`).
* **Styled Data Table:** Custom HTML table featuring zebra striping (`:nth-child(odd)`), row highlights, and colored status badges.
* **No Framework Dependencies:** Constructed entirely with native CSS features (Float, Position, Pseudo-classes, Combinators).

## 🛠️ Built With

* **HTML5:** Semantic document structure.
* **CSS3:** Custom styles, positioning (`fixed`, `absolute`), pseudo-classes, and layout management.
* **FontAwesome 6:** Icon set for navigation and action buttons.

## 📁 Project Structure

```text
├── index.html     # Main HTML document
├── style.css      # Core stylesheet containing menu & table styles
└── README.md      # Project documentation

git clone https://github.com/yusif9999/css-dropdown.git
