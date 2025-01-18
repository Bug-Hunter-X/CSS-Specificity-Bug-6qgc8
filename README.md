# CSS Specificity Bug

This repository demonstrates a common CSS bug related to specificity.  Inline styles unexpectedly override ID selectors due to specificity rules.

## Bug Description

The CSS code attempts to style an element using an ID selector, but an inline style declaration overrides it.

## Solution

The solution involves carefully examining the CSS specificity and reorganizing the CSS rules to achieve the desired style.  In most cases, increasing the specificity of the ID selector (by adding more selectors) or removing the conflicting inline styles can solve the issue.

## How to reproduce

1. Clone the repository.
2. Open `index.html` in a web browser.
3. Observe the unexpected styling due to the conflict between inline and ID selector styles.
4. View `bugSolution.css` to see how the problem is resolved. 