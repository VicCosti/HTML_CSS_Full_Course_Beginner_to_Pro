# ✨ Lesson 3: Hovers, Transitions, Shadows

> **Course:** HTML & CSS Course
> **Type:** Hands-on Exercises
> **Topics:** `:hover`, `:active`, `transition`, `box-shadow`, `opacity`

🔗 **[View live demo](https://viccosti.github.io/HTML_CSS_Full_Course_Beginner_to_Pro/Lesson_3_Hovers_Transitions_Shadows/)**

---

## 📋 Overview

This lesson builds directly on the buttons and product card from **Lesson 2**, adding interactivity through CSS `:hover` states and smooth `transition` effects. Each exercise targets a different CSS property — opacity, background color, shadows, borders — to demonstrate how small interactive details make a static UI feel alive and responsive.

Rather than starting from scratch, every exercise reuses the exact class names and base styles from Lesson 2, with hover/transition rules added on top — so the two lessons can be compared side by side to see exactly what changed.

---

## ✅ Exercises

| # | Task | Hover Property Added |
|---|------|----------------------|
| 3a | Uber "Request now" button | `opacity` |
| 3b | Amazon "Add to Cart" button | `background-color` |
| 3c | GitHub "Sign up" button | `box-shadow` |
| 3d | Bootstrap "Get started" + "Download" buttons | `background-color`, `color` |
| 3e | LinkedIn "Apply on company website" + "Save" buttons | `background-color`, `border-width` |
| 3f 🏆 **Challenge** | Product card (continued from 2f) — hover effects added throughout | `color`, `background-color`, plus `:active` states on buttons |

---

## 🔍 What Changed from Lesson 2 → Lesson 3

Every button kept its Lesson 2 structure and base styling. On top of that, each one gained:

- A `transition` rule (defining duration and which property animates smoothly)
- A `:hover` rule (defining the new value that property takes on mouse-over)

**Example — Uber button:**
```css
/* Lesson 2 */
.uber_button {
  background-color: black;
  color: white;
  ...
}

/* Lesson 3 — added */
.uber_button {
  ...
  transition: opacity 0.7s;
}
.uber_button:hover {
  opacity: 0.7;
}
```

**Extra touch on the challenge exercise (3f):** beyond what was asked, `:active` states were added to the "Add to Cart" and "Buy Now" buttons (reducing opacity on click), simulating the pressed-button feedback seen on real e-commerce sites.

---

## 📁 Project Files

| File | Description |
|---|---|
| [`index.html`](./index.html) | Exercise prompts and completed solutions for 3a–3f |
| [🔗 Live demo](https://viccosti.github.io/HTML_CSS_Full_Course_Beginner_to_Pro/Lesson_3_Hovers_Transitions_Shadows/) | Rendered version — hover over the buttons to see the transitions in action |

---

## 🧠 Key Concepts Applied

- **`:hover` pseudo-class** — defining a different style state for when the user's cursor is over an element
- **`:active` pseudo-class** — providing visual feedback at the moment of a click, not just on hover
- **`transition`** — animating property changes smoothly over time instead of switching instantly
- **`box-shadow`** — adding depth and elevation feedback on interaction
- **Iterative development** — extending an earlier project (Lesson 2) with new features rather than rebuilding from scratch

---

## 📚 What I Learned

- How `transition` controls *which* property animates and *how long* the animation takes, separate from the `:hover` rule that defines the end state
- That subtle interactive details — opacity fades, color shifts, shadows — are what separate a static mockup from something that feels like a real, working interface
- How to layer new CSS on top of an existing project incrementally, keeping the same class structure while extending its behavior
- The difference between `:hover` (mouse presence) and `:active` (the moment of interaction/click), and when each is appropriate

---

## 🛠️ Concepts Referenced

![CSS3](https://img.shields.io/badge/Language-CSS3-blue?style=flat-square)
![Transitions](https://img.shields.io/badge/Concept-Transitions-orange?style=flat-square)
![Pseudo--classes](https://img.shields.io/badge/Concept-Pseudo--classes-lightgrey?style=flat-square)
![Interactivity](https://img.shields.io/badge/Concept-Interactivity-green?style=flat-square)
