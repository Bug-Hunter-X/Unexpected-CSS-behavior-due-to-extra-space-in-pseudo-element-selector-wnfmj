# Unexpected CSS behavior due to extra space in pseudo-element selector

This repository demonstrates a subtle bug in CSS that can be difficult to debug. The problem lies in an extra space within the pseudo-element selector of a CSS rule. This extra space prevents the rule from applying correctly to the pseudo-element, leading to unexpected behavior and rendering issues.

## Bug Description

The bug is demonstrated in the `bug.css` file. The CSS rule attempts to style the `::before` pseudo-element of an HTML element with the class `my-element`. However, due to an extra space in the selector (`:: before`), the rule is not applied, and the expected content is not displayed.

## Solution

The solution, shown in `bugSolution.css`, is straightforward. The extra space is removed from the pseudo-element selector, resulting in a correct selector that applies the CSS rule as intended.