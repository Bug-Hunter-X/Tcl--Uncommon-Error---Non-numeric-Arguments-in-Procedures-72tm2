# Tcl Uncommon Error: Non-numeric Arguments in Procedures

This repository demonstrates a subtle error that can occur in Tcl when procedures expect numeric arguments but receive non-numeric input. The `bug.tcl` file shows the erroneous code, and `bugSolution.tcl` presents a corrected version.

**Problem:** The `badproc` procedure in `bug.tcl` attempts to add two arguments, but it doesn't check if these arguments are indeed numbers. If you pass a non-numeric string as an argument, an error will occur.

**Solution:** The `bugSolution.tcl` file shows how to improve this code by adding error handling or type checking. This solution adds input validation to ensure that the arguments are numbers before attempting to add them. This prevents errors and makes the procedure more robust.

**How to run the code:**
1. Save the code from `bug.tcl` and `bugSolution.tcl` into separate files.
2. Execute the scripts using a Tcl interpreter (e.g., wish).
3. Observe the errors and the improved behavior of the corrected version.