#  CSS Units & Layout

## Overview

This assignment focuses on building a responsive page layout using different CSS units including `%`, `em`, `rem`, `vh`, and `px`. The project demonstrates how relative and viewport-based units can be combined to create flexible layouts that adapt to different screen sizes.

The layout consists of a header section and a body section containing two columns with multiple rows. CSS Flexbox is used to organize elements efficiently while maintaining responsiveness.

---

## Live Demo

🔗 **Live Website**

https://asmashahzadi764-alt.github.io/learn-web-engineering/day-05/submissions/asmashahzadi764/

---

## Learning Objectives

* Understand CSS Units (`%`, `em`, `rem`, `vh`, `px`)
* Create responsive layouts
* Use CSS Flexbox
* Apply BEM-style class naming
* Use the `calc()` function
* Build viewport-aware designs

---

## Project Structure

```text
├── index.html
├── style.css
└── README.md
```

---

## Layout Description

The page contains:

### Header Section

* Light gray background
* Black border
* Height set to `10vh`

### Body Section

* Light blue background
* Black border
* Height dynamically calculated using:

```css
height: calc(100vh - 10vh - 1rem);
```

This ensures the body occupies the remaining viewport height after the header.

---

## Column Layout

The body section contains two columns:

### Column 1

* Width: `30%`
* Background: `antiquewhite`
* Red border
* Contains 4 rows

### Column 2

* Width: `70%`
* Background: `antiquewhite`
* Red border
* Contains 6 rows

Both columns are displayed side-by-side using Flexbox.

---

## CSS Units Used

| Unit   | Purpose                    |
| ------ | -------------------------- |
| px     | Borders                    |
| em     | Padding and spacing        |
| rem    | Gap between sections       |
| vh     | Responsive heights         |
| %      | Column widths              |
| calc() | Dynamic height calculation |

---

## CSS Features Implemented

### Flexbox Layout

```css
.flex-container {
  display: flex;
}
```

### Vertical Layout

```css
.flex--column {
  flex-direction: column;
}
```

### Dynamic Height Calculation

```css
height: calc(100vh - 10vh - 1rem);
```

### Responsive Column Widths

```css
#col-1 {
  width: 30%;
}

#col-2 {
  width: 70%;
}
```

---

## Expected Output

The final webpage displays:

* A gray header section at the top.
* A blue content area below the header.
* Two columns positioned horizontally.
* Four rows inside the first column.
* Six rows inside the second column.
* Responsive sizing using viewport and percentage units.

---

## Technologies Used

* HTML5
* CSS3
* Flexbox

---

## Concepts Practiced

* CSS Units
* Relative Sizing
* Viewport Units
* Percentage-Based Layouts
* Flexbox
* BEM Naming Convention
* Responsive Design
* CSS calc() Function

---

## Reflection

This assignment improved my understanding of how different CSS units behave in responsive layouts. Using viewport units, percentages, and the calc() function helped me create a flexible design that adapts to screen size changes. It also reinforced my understanding of Flexbox and structured CSS class naming practices.

---

## Author

**Asma Shahzadi**

---
