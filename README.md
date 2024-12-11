# Uncommon CSS `calc()` Errors

This repository demonstrates some uncommon errors that can occur when using the `calc()` function in CSS.  These errors often stem from unexpected behavior related to spacing, unit compatibility, and complex nested expressions.  The `bug.css` file showcases these issues, while `bugSolution.css` provides the corrected code.

**Issues Demonstrated:**

* **Spacing in `calc()` expressions:** Incorrect spacing around operators can lead to calculation failures.
* **Unit incompatibility:** Mixing incompatible units within a `calc()` expression can produce unexpected results.
* **Complex nested expressions:**  Nested `calc()` functions and variable usage require careful attention to unit consistency and order of operations.

**How to Reproduce:**

1. Clone this repository.
2. Open `bug.css` and examine the provided CSS code.
3. Observe the incorrect behavior when rendering these CSS rules in a browser.
4. Compare the `bug.css` with `bugSolution.css` to see the corrected code.

**Contributing:**

Contributions are welcome! If you have encountered other unusual or difficult-to-debug issues with CSS `calc()`, feel free to open an issue or submit a pull request.