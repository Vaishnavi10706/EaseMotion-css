# CSS-only Radial Action Menu

A modern **CSS-only expanding radial action menu** built using only HTML and CSS.

When the user hovers over the center button, multiple action buttons smoothly expand outward in a circular arrangement.

## Features

- 🎯 Pure HTML & CSS
- ✨ Smooth hover animation
- 🔄 Rotating center button
- 📱 Responsive layout
- 🚫 No JavaScript required
- 🎨 Easy to customize

## Folder Structure

```
radial-action-menu/
├── demo.html
├── style.css
└── README.md
```

## How it Works

- The action buttons are initially hidden using:
  - `opacity: 0`
  - `scale(0)`

- On hover:
  - Buttons expand outward using CSS `transform`.
  - The center button rotates by **45°**.
  - All animations are handled with CSS transitions.

## Customization

You can easily:

- Add more action buttons
- Change icons or emojis
- Modify colors
- Increase the menu radius
- Change animation duration
- Replace emojis with SVG icons

## Technologies Used

- HTML5
- CSS3
