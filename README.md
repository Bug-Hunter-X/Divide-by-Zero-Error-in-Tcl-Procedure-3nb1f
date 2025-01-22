# Tcl Divide-by-Zero Bug

This repository demonstrates a common error in Tcl: a divide-by-zero error that can occur if input validation is not properly implemented. The `bug.tcl` file contains the erroneous code, while `bugSolution.tcl` provides a corrected version.

The bug is present in the `badproc` procedure, which does not check for a zero divisor before performing the division. This can lead to a runtime error if the first argument is 0.

The solution adds a check to prevent the division by zero.  It handles the case where 'a' is 0 gracefully.

This example highlights the importance of robust input validation in any programming language.