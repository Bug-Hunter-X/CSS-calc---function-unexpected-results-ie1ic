# CSS calc() Unexpected Results

This repository demonstrates an uncommon error encountered when using the `calc()` function in CSS. The error involves the use of percentages and fixed values in `calc()` without sufficient attention to the surrounding element's context and unit consistency.

The `bug.css` file contains the buggy code. `bugSolution.css` provides a corrected implementation with explanations.

## Problem
The `calc()` function in CSS is a powerful tool, but it can behave unexpectedly if percentages and fixed-size units are combined without a thorough understanding of the calculation context and unit consistency.  Inconsistent unit usage or missing information about parent element dimensions can lead to incorrect or unexpected output.

## Solution
The corrected code in `bugSolution.css` addresses these issues by providing a more robust and predictable implementation that addresses these inconsistencies, ensuring that calculations always produce the intended results.