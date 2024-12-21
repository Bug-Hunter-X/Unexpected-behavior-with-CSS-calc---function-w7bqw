# Unexpected behavior with CSS calc() function
This repository demonstrates a common issue encountered when using the `calc()` function in CSS. The problem arises from incorrect usage of units within the `calc()` expression, specifically mixing percentages and fixed units in a way that leads to unexpected behavior or layout inconsistencies. The solution demonstrates best practices for avoiding these issues.

## Bug Description
The `calc()` function in CSS is a powerful tool for performing calculations within style declarations. However, using it incorrectly, particularly when combining percentages and fixed units like pixels, can easily lead to unexpected outcomes.  One common error is attempting to calculate a percentage based on a value that is still being calculated by the `calc` function. This often results in unpredictable results and inconsistent layout. 

## Solution Description
The solution focuses on careful unit management and understanding the order of operations within `calc()`.  Using fixed units where appropriate and ensuring consistent usage of units will resolve most instances of unpredictable results. 