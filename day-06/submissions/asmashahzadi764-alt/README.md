# Cards Layout with BEM

# Overview

This assignment focuses on creating a structured card layout using the **BEM (Block Element Modifier)** naming convention. The project demonstrates how reusable CSS classes, spacing, borders, and inline-block layouts can be combined to build clean and organized user interface components.

The webpage contains two card sections with different layouts while maintaining consistent styling and component structure.

---

# Live Demo

🔗 **Live Website**

[https://asmashahzadi764-alt.github.io/learn-web-engineering/day-06/submissions/asmashahzadi764/](https://asmashahzadi764-alt.github.io/learn-web-engineering/day-06/submissions/asmashahzadi764-alt/)

---

# Learning Objectives

* Understand the BEM naming convention
* Create reusable UI components
* Practice `inline-block` layouts
* Apply consistent spacing using relative units
* Use `calc()` for responsive sizing
* Build structured card layouts with HTML and CSS

---

# Project Structure

```text
├── index.html
├── style.css
└── README.md
```

---

# Project Description

The webpage consists of **two card containers**.

### First Cards Container

* Contains **3 cards**
* Each card has:

  * A title section
  * A description section
  * An icon container
* The icon is displayed inside a **48 × 48 pixel** blue bordered box.

### Second Cards Container

* Contains **5 cards**
* Every card includes:

  * Title
  * Description
* The second container is separated from the first using **1rem top margin**.

---

# CSS Features

## Borders

Different modifier classes are used to apply border colors.

| Class            | Border |
| ---------------- | ------ |
| `.border`        | Black  |
| `.border--red`   | Red    |
| `.border--green` | Green  |
| `.border--blue`  | Blue   |

---

## Card Layout

Each card has:

* Width: **300px**
* Padding: **1em**
* Display: **inline-block**

The cards align horizontally while maintaining equal spacing.

---

## Card Content

Each card contains reusable BEM elements:

* `card__title`
* `card__description`
* `card__content`
* `card__icon`

The title and description use:

```css
padding: 0.25em 1em;
```

The icon has fixed dimensions:

```css
width: 48px;
height: 48px;
```

---

# BEM Naming Convention Used

### Block

* `cards`
* `card`

### Elements

* `card__content`
* `card__title`
* `card__description`
* `card__icon`

### Modifiers

* `cards--last`
* `border--red`
* `border--green`
* `border--blue`

Using BEM keeps the code modular, reusable, and easier to maintain.

---

# Expected Output

The webpage displays:

* A bordered cards container with **three cards**.
* Every card contains text and an icon section.
* A second cards container appears below with **five cards**.
* Proper spacing, borders, and alignment are maintained throughout the layout.

---

# Technologies Used

* HTML5
* CSS3

---

# Concepts Practiced

* BEM Naming Convention
* CSS Display (`inline-block`)
* CSS Borders
* Relative Units (`em`, `rem`)
* CSS `calc()`
* Reusable Components
* Responsive Layout Principles

---

# Reflection

This assignment strengthened my understanding of the BEM methodology and component-based CSS design. I learned how to organize reusable card layouts, maintain consistent spacing, and create structured interfaces using semantic class names. Implementing reusable modifiers and layout techniques improved both the readability and maintainability of my code.

---
## Author

**Asma Shahzadi**

---
