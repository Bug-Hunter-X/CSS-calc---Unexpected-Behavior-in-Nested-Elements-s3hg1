# CSS calc() Unexpected Behavior in Nested Elements
This repository demonstrates an uncommon bug related to the CSS `calc()` function when used with units within nested elements. The problem arises from how `calc()` handles unit conversions and the order of operations, especially when the parent element's dimensions aren't definitively set.

The `bug.css` file contains the problematic code, while `bugSolution.css` offers a corrected implementation.

## Bug Description
The `calc()` function, while powerful, can produce incorrect results if not carefully implemented, particularly when mixing percentages and fixed units like pixels. This often manifests in unexpected layout discrepancies in nested elements.