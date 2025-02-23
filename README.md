# CSS Specificity Bug

This repository demonstrates a common issue in CSS related to specificity.  The bug lies in unexpected styling behavior due to the order and specificity of CSS rules.

The `bug.css` file contains the problematic CSS. The `bugSolution.css` file provides a solution.

## Bug Description

We have a nested element structure where specificity interferes with our expected styling. The intended color doesn't show up due to the more specific rule overriding the less specific one.  The solution modifies the specificity to ensure that the correct style is applied.