# 📌 Pinterest-Style Pin Layout Clone

A beginner-friendly front-end project where I practiced building layouts, solving CSS problems, and understanding how real interfaces come together.

**Live Site:** https://sblaize33.github.io/Pintrest-Portfolio/

---

## 🛠️ Technologies Used

- **HTML5** — semantic structure
- **CSS3** — layout, positioning, transitions, media queries
- **Google Fonts** — Inter
- **Git / GitHub** — version control
- **GitHub Pages** — deployment

---

## 🌟 Overview

This project recreates the basic look of Pinterest's pin feed using HTML and CSS. My goal wasn't to build a full product — it was to understand how layouts work, how elements interact, and how to fix things when they don't behave the way I expect.

I'm early in my engineering journey, and this project helped me build confidence by learning through hands-on practice.

---

## 🌱 Learning Journey

When I started, CSS felt unpredictable. Through this project I learned to slow down, inspect what's happening in the browser, and treat each element like a box with rules I can control.

**What I learned about myself:**

- I can break problems down instead of getting overwhelmed
- Bugs are normal — and usually teach me something important
- Small CSS changes can completely shift a layout, so reading my code carefully matters
- I don't need to know everything — I just need to keep learning step by step

---

## 🧠 What I Built

### ✔ Semantic HTML
- Used `<header>`, `<div>`, `<img>`, `<h3>`, and `<button>` to organize the page
- Wrote descriptive `alt` text on every image for screen reader accessibility
- Kept structure readable and consistently indented

### ✔ Masonry Grid Layout
- Built a Pinterest-style multi-column feed using CSS `column-count` and `column-gap`
- Used `break-inside: avoid` on each pin card so images never split across columns
- Achieved the masonry effect with pure CSS instead of JavaScript — simpler than I expected going in

### ✔ Responsive Design
- Wrote media queries that adapt the layout to screen size:
  - 3 columns on desktop
  - 2 columns under 900px
  - 1 column under 600px
- Images scale fluidly using `width: 100%`

### ✔ Fixed Navigation Header
- Built the header with Flexbox using `justify-content: space-between` to separate logo, search bar, and nav links
- Used `position: fixed` so the header stays locked to the top of the viewport while the feed scrolls
- Added `z-index: 1000` so the header always layers above the pin cards
- Learned the difference between `fixed` and `absolute` positioning through trial and error

### ✔ Styling & Branding
- Integrated Google Fonts (Inter) with `preconnect` for faster loading
- Matched Pinterest's brand red (`#e60023`) for the logo badge and Save button
- Debugged font inheritance issues so styles applied consistently across elements
- Added `border-radius`, `box-shadow`, and padding to give cards depth

### ✔ Interactions
- Added a hover effect using `transform: scale(1.1)` with a `transition` for smoothness
- Styled hover states on nav links and the Save button for clearer feedback

---

## 🐛 Problems I Solved

**CSS specificity conflict** — My global `img { width: 100% }` rule was competing with `.pin-card img`. I opened Chrome DevTools, inspected which rule was winning, and learned how the CSS cascade decides between selectors. I fixed it by writing more specific selectors.

**Header alignment** — Getting the logo, search bar, and nav links to sit correctly took several attempts. I worked through it using Flexbox properties and learned how `flex: 1` and `max-width` interact.

**Column splitting** — Pin cards were breaking awkwardly across columns until I found `break-inside: avoid`, which taught me that CSS columns need explicit rules about where content can and can't break.

---

## 🧩 Where My Learning Went After This

- Working through the freeCodeCamp JavaScript curriculum — currently on operators, boolean logic, and debugging exercises
- Completed the Treehouse Full Stack JavaScript starter track, including a functions and arrays project
- Continuing to strengthen fundamentals: the Box Model, inline vs. block behavior, and the CSS cascade
- Practicing how to talk through my problem-solving process out loud

---

## 🗂 Why This Project Is Complete

This was built as a focused learning exercise, not a product I intended to keep expanding. It did exactly what I needed it to do: it took me from "CSS feels random" to understanding layout, positioning, the cascade, and responsive design well enough to debug my own work.

I've since moved on to JavaScript fundamentals, which is where my learning time is going now. I'm leaving this project as-is because it's an honest snapshot of where I was and what I figured out at this stage.

---

## 🧑‍💻 Author

**Shavon Blaize**
Aspiring Front-End Developer | Early-Career Engineer

