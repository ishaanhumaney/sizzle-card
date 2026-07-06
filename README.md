# SizzleCard

A lightweight, highly scannable, and interactive recipe card built entirely with semantic HTML5 and vanilla CSS3. No heavy frameworks, no bloated bundlers, and zero JavaScript. 

It handles complex user states—like crossing out ingredients and marking preparation steps as completed—using smart CSS sibling selectors tied to accessible checkbox inputs.

## Key Features

* **Pure CSS State Management:** Uses the `:checked` pseudo-class and sibling selectors (`+` and `~`) to handle interactive strikethroughs and checkmark changes instantly.
* **Accessible Architecture:** Retains native keyboard navigation and screen-reader accessibility by keeping checkboxes fully functional but visually hidden behind custom UI layers.
* **Fluid Responsive Layout:** Built using modern Flexbox mechanics, ensuring the card centers perfectly on massive desktop displays and wraps cleanly on cramped mobile viewports.
* **Polished Micro-interactions:** Smooth transition curves on color shifts and border states provide tactile feedback without impacting browser performance.

## Tech Stack Breakdown

* **HTML5:** Semantic document structure (`<ol>`, `<ul>`, `<label>`, `<span class="item-text">`) prioritizing web accessibility and reading order.
* **CSS3:** Native variable-free modern styling utilizing system font stacks, crisp box shadows, and independent flex layouts.

## Web-Based Quick Start

You don't need to install anything locally to play with or modify this codebase.

### Run in GitHub Codespaces
1. Click the green **Code** button at the top right of this repository.
2. Switch to the **Codespaces** tab.
3. Click **Create codespace on main**.
4. Once the web-based VS Code environment loads, right-click `index.html` and use a built-in live server extension or preview tool to view the page.

### Quick Local Option
If you prefer traditional methods, clone the repository and simply double-click the `index.html` file to launch it instantly in any modern web browser.

## Project Structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml        # Basic sanity check workflow
├── .gitignore            # Keeps environment junk out of the repo
├── index.html            # Semantic markup and recipe structure
├── style.css             # Layout calculations and custom checkbox themes
└── README.md             # This documentation
```

## Roadmap
[ ] Add a dark mode toggle using pure CSS custom properties.

[ ] Implement responsive media queries tailored for ultra-small device profiles.

[ ] Create a multi-card carousel component for featuring a collection of recipes.
