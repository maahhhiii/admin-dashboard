# 📊 Dashly - Advanced Admin Dashboard Template

Dashly is a modern, responsive, and high-level web interface designed for administrators to track analytical business datasets, evaluate transaction logs, and manage user interactions cleanly. Built from scratch using modern semantically structured HTML5 markup and organized CSS layout principles.

---

## ✨ Key Technical Features

* **Fixed Sidebar Component**: A dedicated left-side vertical navigation bar that stays locked in place during window scroll using `position: fixed`.
* **Glassmorphic Header Bar**: A sleek, sticky layout top-bar utilizing background filters for depth contrast against primary card spaces.
* **4-Column Responsive Metrics Row**: Flexbox metric card structures designed with clean, proportional scaling targets to display analytics data cleanly.
* **Functional Activity Timeline**: A chronological custom event tracker utilizing linear vertical connector markers styled via pure CSS properties.
* **Interactive Table Data View**: A beautifully balanced table spreadsheet template featuring specialized status badge indicators (`Completed`, `Pending`, `Shipped`).
* **Micro-Interactions & Hover Feedback**: Integrated CSS states (`:hover`, `:active`) and visual transitions (`transition: 0.3s`) that organically respond to user mouse interactions.

---

## 🛠️ Built With

* **HTML5** - Structured semantic element tags (`<aside>`, `<main>`, `<section>`).
* **CSS3** - Customized properties via CSS Root variables (`:root`), Flexbox structures, dynamic margins, custom sizing ratios, and micro-transformations.
* **FontAwesome (v6.5.1)** - Vector iconography layout support for streamlined graphical visual representations.

---

## 📂 Project Directory Structure

```text
├── index.html        # Main landing frame containing structural markdown blocks
├── style.css         # Modern styling file detailing custom themes and flex properties
└── image/            # Assets directory for structural image templates
    ├── logo.png      # Graphical branding emblem image asset
    └── profile.png   # Administrative user placeholder photo asset
    └── dashboard-banner.png
    └── sales-chart-placeholder.png

## 🚀 Quick Execution Guide

To view and run this application locally on your computer workstation:

1. **Clone or Download** this repository folder workspace locally.
2. Ensure your image files match the path setups inside your local `image/` file tree root.
3. Open your project folder directory and double-click **`index.html`** to launch the dashboard application directly inside any standard internet web browser engine.

## 👩‍🏫 Project Evaluation / VIVA References

If evaluating this project for web development fundamentals:
* **Layout Management**: This project bypasses messy positioning properties by relying on robust **Flexbox rules** (`display: flex`) paired with percentage boundaries (`width: 65%`, `width: 35%`) to distribute layouts.
* **Global Theme Maintainability**: Color scheme styling configurations are managed inside a centralized **CSS Root system** (`:root`), promoting modular adjustments to global backgrounds or texts instantly.
