# Food Ninja Mockup

A responsive single-page recipe mockup built with HTML and Tailwind CSS (via CDN).

## Overview

This project is a static front-end layout for a recipe website concept called **Food Ninja**. It includes:

- A sidebar navigation (`Home`, `About`, `Contact`)
- Auth action buttons (`Log in`, `Sign up`)
- A hero/header section for recipes
- A recipe card grid with images, author, and prep time badges
- A styled `Load more` action button

## Tech Stack

- HTML5
- Tailwind CSS (CDN: `https://cdn.tailwindcss.com`)
- Local image assets

## Project Structure

```text
CAT/
|- index.html
|- blueberry-pie.jpg
|- noodles.jpg
|- italian-pizza.jpg
```

## Run Locally

1. Open the project folder.
2. Launch `index.html` in your browser.

No build step or package installation is required.

## Notes

- This is a static UI mockup and does not include JavaScript logic or backend integration.
- Navigation links and buttons are currently placeholders (`#`).

## Possible Improvements

- Add real page routing or multi-page structure.
- Connect recipe cards to dynamic data.
- Improve accessibility (landmarks, ARIA where needed, keyboard checks).
- Move from Tailwind CDN to a build setup for production optimization.
