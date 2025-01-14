# CSS Hover Specificity Bug

This repository demonstrates a common issue in CSS involving hover effects not working as expected due to specificity problems when dealing with nested elements and their background colors.  The `bug.css` file contains the problematic code, while `bugSolution.css` provides a solution.

The problem arises because the default list item style and the hover style have lower specificity compared to a nested element with a background-color style. The solution uses more specific selectors to ensure the hover style takes precedence.