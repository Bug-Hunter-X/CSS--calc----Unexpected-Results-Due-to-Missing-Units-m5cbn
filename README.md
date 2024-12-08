# CSS `calc()` Unexpected Results Due to Missing Units

This repository demonstrates a common issue when using the `calc()` function in CSS: inconsistent or missing units can lead to unexpected results and broken layouts.

The `bug.css` file shows a case where missing units cause `calc()` to fail, resulting in incorrect element sizing or positioning. The `bugSolution.css` file corrects this by explicitly defining units for all values used in calculations.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` (or a similar HTML file that references `bug.css`) in a web browser.
3. Observe the unexpected rendering due to the faulty `calc()` usage.
4. Replace `bug.css` with `bugSolution.css` and observe the correct rendering.

## Solution
Always specify units (such as `px`, `em`, `rem`, `%`) for all values used within the `calc()` function to ensure consistent calculations and reliable CSS behavior.