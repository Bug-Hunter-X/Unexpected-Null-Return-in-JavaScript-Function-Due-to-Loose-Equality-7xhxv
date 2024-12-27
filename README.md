# Unexpected Null Return in JavaScript Function Due to Loose Equality

This repository demonstrates a common JavaScript bug involving loose equality (`==`) comparisons with `null`. The function `foo` intends to add two numbers but returns `null` unexpectedly under certain conditions due to the way `null` is handled in loose equality checks.  This can be subtle and cause difficult-to-debug errors in larger codebases.

The `bug.js` file showcases the erroneous behavior. The `bugSolution.js` file provides a corrected version using strict equality (`===`).  Strict equality prevents unexpected type coercion, resolving the issue.