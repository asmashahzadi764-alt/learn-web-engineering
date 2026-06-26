# Mentorship Dashboard with Flexbox


# Overview

This assignment demonstrates how to build a responsive **Mentorship Dashboard** using **CSS Flexbox** and reusable utility classes. The layout is divided into two sections: a metrics dashboard displaying key mentorship statistics and a details section containing navigation cards.

The project follows a component-based structure with reusable classes for borders, containers, spacing, and Flexbox layouts, resulting in clean and maintainable code.

---

# Live Demo

🔗 **Live Website**

https://asmashahzadi764-alt.github.io/learn-web-engineering/day-07/submissions/asmashahzadi764-alt/

---

# Learning Objectives

* Understand CSS Flexbox layouts
* Build responsive dashboard interfaces
* Create reusable utility classes
* Design card-based UI components
* Practice spacing and alignment using Flexbox
* Organize code using reusable CSS classes

---

# Project Structure

```text
├── index.html
├── style.css
└── README.md
```

---

# Project Description

The webpage is divided into **two main sections**.

## 1. Metrics Section

This section contains **three dashboard cards** displaying important mentorship statistics:

* Active Matches
* Completed Mentorships
* Pending Requests

Each card contains:

* A title
* A large numeric value
* A 32 × 32 icon placeholder

---

## 2. Details Section

The second section displays **five navigation cards**.

Each card includes:

* A heading
* A short description

Cards included:

* Browse Mentors
* My Matches
* Goals and Progress
* Settings
* Community Mentors

The cards automatically wrap onto new rows using Flexbox.

---

# CSS Features

## Flexbox Utilities

Reusable utility classes are used throughout the project:

```css
.container
.container--row
.container--column
.container--wrap
.grow
```

These classes simplify layout creation and improve code reusability.

---

## Card Layout

Each card includes:

* Width: **300px**
* Padding: **1em**
* Background: `antiquewhite`

The parent sections use:

* Background: `aliceblue`
* Gap: `1em`
* Padding: `1em`

---

## Utility Classes

The project includes reusable utility classes for:

* Flexbox Containers
* Borders
* Flex Grow
* Layout Direction
* Wrapping
* Spacing

Border modifiers:

* `.border`
* `.border--red`
* `.border--green`
* `.border--blue`

---

## Typography

* Font Family: `monospace`
* Card Title: `1.25em`
* Metric Value: `2em`

---

## Responsive Layout

The dashboard uses **CSS Flexbox** for:

* Horizontal alignment
* Vertical alignment
* Flexible spacing
* Responsive wrapping
* Reusable layouts

---

# Expected Output

The final webpage displays:

* A responsive mentorship dashboard.
* Three metric cards aligned horizontally.
* Five information cards arranged using Flexbox wrapping.
* Proper spacing, borders, and consistent card design.
* Reusable utility classes for clean and maintainable code.

---

# Technologies Used

* HTML5
* CSS3
* CSS Flexbox

---

# Concepts Practiced

* CSS Flexbox
* Utility Classes
* Card Components
* Responsive Layout Design
* Flex Grow
* Flex Wrap
* CSS Borders
* Reusable CSS
* Component-Based Design

---

# Reflection

This assignment strengthened my understanding of CSS Flexbox and responsive dashboard layouts. By creating reusable utility classes and organizing content into card components, I learned how modern web interfaces can be built with clean, scalable, and maintainable code. The project also improved my understanding of spacing, alignment, and responsive design principles.

---

## Author

**Asma Shahzadi**

---
