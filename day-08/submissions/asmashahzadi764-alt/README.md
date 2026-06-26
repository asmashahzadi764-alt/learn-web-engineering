# Build a Flexbox Layout

# Overview

This assignment focuses on building a complete webpage layout using **CSS Flexbox**. The project includes a structured page with a header, navigation sidebar, and main content area. The layout demonstrates the effective use of Flexbox properties such as `flex-direction`, `flex`, `gap`, and alignment to create a responsive and organized interface.

Reusable utility classes and BEM-inspired naming conventions were used to keep the code clean, modular, and easy to maintain.

---

# Live Demo

🔗 **Live Website**

https://asmashahzadi764-alt.github.io/learn-web-engineering/day-08/submissions/asmashahzadi764-alt/

---

# Learning Objectives

* Build complete page layouts using CSS Flexbox
* Understand Flexbox containers and items
* Practice nested Flexbox layouts
* Create reusable utility classes
* Organize webpage sections using semantic HTML
* Improve responsive layout skills

---

# Project Structure

```text
├── index.html
├── style.css
└── README.md
```

---

# Project Description

The webpage is divided into **three main sections**.

## 1. Header

The header is placed at the top of the page and contains two flexible items arranged vertically.

Features:

* 20vh height
* Black outer border
* Two red bordered header items
* Vertical Flexbox layout

---

## 2. Navigation Sidebar

The navigation section appears on the left side of the page.

Features:

* Width: 20%
* Five navigation items
* First navigation item occupies more space using Flexbox
* Vertical Flexbox layout

---

## 3. Main Content

The main content occupies 80% of the available width.

It contains three card sections:

### First Section

* Four cards displayed horizontally
* First card is larger than the remaining cards

### Second Section

* Two columns
* Left column contains three stacked blocks
* Right column contains two vertically aligned blocks

### Third Section

* Same layout as the second section
* Demonstrates reusable Flexbox components

---

# CSS Features

## Utility Classes

Reusable utility classes include:

```css
.flex--row
.flex--column
.border
.border--red
.border--green
.border--blue
```

These classes simplify layout creation and improve code readability.

---

## Flexbox Layout

The project uses Flexbox throughout the page for:

* Header
* Navigation
* Main content
* Cards
* Nested layouts

Important properties used:

* display: flex
* flex-direction
* flex
* gap
* justify-content
* align-items

---

## Borders

Different colored borders are used to visualize the layout during development.

| Class            | Border Color |
| ---------------- | ------------ |
| `.border`        | Black        |
| `.border--red`   | Red          |
| `.border--blue`  | Blue         |
| `.border--green` | Green        |

---

# Expected Output

The final webpage displays:

* A responsive header with two sections.
* A left navigation sidebar.
* A main content area containing three Flexbox card layouts.
* Nested Flexbox containers with proper spacing and alignment.
* Clean structure using reusable utility classes.

---

# Technologies Used

* HTML5
* CSS3
* CSS Flexbox

---

# Concepts Practiced

* CSS Flexbox
* Nested Flexbox
* Responsive Layouts
* Utility Classes
* BEM-inspired Naming
* Semantic HTML
* Flex Grow
* Flex Direction
* Gap Property
* Component-Based Design

---

# Reflection

This assignment enhanced my understanding of building complete webpage layouts using CSS Flexbox. I practiced creating nested Flexbox structures, organizing content into reusable components, and improving layout responsiveness through utility classes. It also strengthened my skills in writing clean, scalable, and maintainable HTML and CSS.

---

## Author

**Asma Shahzadi**

---
