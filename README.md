# Uncommon DomainError in Julia Math Functions with Complex Numbers

This repository demonstrates an uncommon error that can occur in Julia when working with mathematical functions and complex numbers.  The `DomainError` arises unexpectedly when certain functions (those internally using `sqrt`, for example) encounter complex numbers with a negative real part.

The `bug.jl` file contains the erroneous code, showcasing the error. The `bugSolution.jl` provides a solution to handle this scenario gracefully.

This is a valuable example for developers working with numerical computation in Julia, highlighting the importance of robust error handling for complex number inputs in mathematical functions.