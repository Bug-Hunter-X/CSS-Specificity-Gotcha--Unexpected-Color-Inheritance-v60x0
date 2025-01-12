# CSS Specificity Gotcha: Unexpected Color Inheritance

This repository demonstrates a subtle bug related to CSS selector specificity. The bug arises from an unexpected interaction between ID selectors, class selectors, and element selectors, leading to unpredictable color inheritance.

## Bug Description
The `bug.css` file contains CSS rules that define colors for various elements. Due to the order of selectors and their specificity, the final color applied to certain elements might be unexpected.

## Solution
The solution is implemented in `bugSolution.css`. It involves a deeper understanding of CSS selector precedence to correct the unexpected color inheritance by adjusting selector specificity or applying more targeted rules to override unwanted behavior. This solution ensures predictable and expected styling.