# CSS Box Model & Display Property

## Overview

This assignment demonstrates the practical use of the **CSS Box Model** and **Display Property**. The goal was to create four paragraph containers with different widths and style the nested span elements to behave like block-level elements.

The project applies multiple CSS classes using a BEM-style naming convention and showcases how margins, padding, borders, and display values affect page layout.

---

## Live Demo

🔗 **Live Website:**

https://asmashahzadi764-alt.github.io/learn-web-engineering/day-04/submissions/asmashahzadi764/

---

## Learning Objectives

* Understand the CSS Box Model
* Practice using multiple CSS classes
* Apply BEM-style modifier classes
* Use the `display` property effectively
* Control element dimensions with CSS
* Work with margins, padding, and borders

---

## Project Structure

```text
├── index.html
├── style.css
└── README.md
```

---

## HTML Implementation

The page contains four paragraph (`<p>`) elements. Each paragraph contains three span (`<span>`) elements.

### Paragraph Classes

* `box`
* `box--small`
* `box--medium`
* `box--large`
* `box--extra-large`

### Span Elements

Each paragraph contains:

* Span 1
* Span 2
* Span 3

---

## CSS Features

### Paragraph Styling

* 2px solid black border
* Display set to `inline-block`
* Different widths using modifier classes

| Class            | Width |
| ---------------- | ----- |
| box--small       | 100px |
| box--medium      | 200px |
| box--large       | 300px |
| box--extra-large | 400px |

### Span Styling

* 1px solid red border
* Display set to `block`
* 5px margin
* 5px padding

This causes the spans to stack vertically inside each paragraph container.

---

## Expected Output

The page displays:

* Four black bordered boxes aligned horizontally.
* Each box has a different width.
* Three red bordered spans stacked vertically inside every box.

This demonstrates how changing the `display` property affects layout behavior and how the CSS Box Model influences spacing and sizing.

---

## Technologies Used

* HTML5
* CSS3

---

## Key Concepts Practiced

* CSS Box Model
* Display Property
* Inline-Block Layout
* Block Elements
* Margins
* Padding
* Borders
* BEM Naming Convention

---

## Reflection

This assignment helped me better understand how the CSS Box Model works and how different display values influence webpage layouts. By experimenting with inline-block and block elements, I gained practical experience in controlling spacing, alignment, and element sizing using CSS.

---

## Author

**Asma Shahzadi**

---

