# CSS Specificity and Inheritance Bug
This repository demonstrates a common issue in CSS related to specificity and inheritance.  The bug showcases how unexpected styling can arise when dealing with multiple selectors and inheritance hierarchies. The solution provides a detailed explanation and fix for the issue.

## Bug Description
The bug occurs due to a conflict between the inheritance of styles from the parent element and the explicit styles specified for the child element. The intended behavior is overridden because of the specificity of the selectors.

## How to Reproduce
1. Clone the repository.
2. Open `bug.html` in your browser.
3. Observe the unexpected styling of the `.child.special` element.

## Solution
The solution involves understanding and properly applying CSS specificity rules.  The fix demonstrates how to prioritize the correct styles to achieve the desired outcome. See `bugSolution.css` for the corrected code and explanations in comments.

## Additional Notes
This example highlights the importance of carefully considering CSS specificity and the cascading nature of styles when writing CSS. Using more specific selectors can help avoid such issues.