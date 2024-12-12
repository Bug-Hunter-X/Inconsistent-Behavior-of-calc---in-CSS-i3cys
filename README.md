# Inconsistent Behavior of calc() in CSS

This repository demonstrates an uncommon bug related to the CSS `calc()` function. The bug manifests as inconsistent rendering across different browsers and situations when combining percentages, viewport units, and nested `calc()` expressions.  The example provided showcases how a seemingly simple `calc()` expression can produce unexpected results. The solution illustrates how to mitigate the issue by simplifying the expression or using alternative layout techniques.

## Bug Report

The main problem involves unexpected results from nested or complex `calc()` expressions that combine percentages and viewport units.  This can lead to inconsistent layout across different browsers and screen sizes.  The original CSS is in `bug.css` and the corrected CSS is in `bugSolution.css`

## How to Reproduce

1. Clone this repository.
2. Open `index.html` in your browser.
3. Observe the different layouts and rendering issues between browsers (it may be subtle on some configurations)
