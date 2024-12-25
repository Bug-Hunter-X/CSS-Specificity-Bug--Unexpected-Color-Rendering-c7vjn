# CSS Specificity Bug: Unexpected Color Rendering

This repository demonstrates an uncommon bug in CSS related to selector specificity and the cascading order. The bug showcases how the interaction between `id` selectors and class selectors can lead to unexpected color rendering results.

## Bug Description
The issue stems from the complex interplay between CSS specificity and the order of rules in a stylesheet.  The rendered color doesn't always align with what one might intuitively expect based on selector specificity alone.

## How to Reproduce
1. Clone this repository.
2. Open `bug.css` to see the problematic CSS code.
3. Create an HTML file that includes an element with both the ID `myElement` and the class `myClass`.
4. Link the `bug.css` file to your HTML.
5. Observe the rendered color of the element. You may find the color is not the expected `green`.

## Solution
The solution, provided in `bugSolution.css`, involves carefully considering CSS specificity and ordering rules to ensure the desired color is consistently applied.