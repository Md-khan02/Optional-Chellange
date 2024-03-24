
# Description
This Python program is designed to compare three numbers and print out the largest. It serves as an educational tool to illustrate common types of errors encountered in programming: compilation errors, runtime errors, and logical errors.

# Errors in the Program
The program includes intentional errors for educational purposes. Users are encouraged to identify and correct these errors as an exercise in debugging Python code.

### Errors List
Runtime Error:

 number3 is mistakenly assigned a string value instead of an integer, which will cause a TypeError during comparison operations since Python cannot compare integers and strings directly.
Compilation Errors:

Missing colon (:) at the end of the elif statement. This syntax error prevents the program from running.
Misspelled variable name numer3 instead of number3 in the else statement, leading to a NameError since the misspelled variable is not defined.
Logical Error:

The program does not handle data types properly nor checks for errors in variable names effectively. It assumes all inputs are valid and correctly spelled, which could lead to issues when the program is expanded or modified.

# Correcting the Errors
Below are brief guidelines on how to correct the mentioned errors. This exercise is left to the reader to implement.

Fix the Runtime Error:

Convert number3's value to an integer using int() for proper comparison.
Resolve Compilation Errors:

Add a colon (:) at the end of the elif statement to correct the syntax error.
Correct the spelling of number3 in the else statement to reference the correct variable.
Address the Logical Error:

Implement error handling or checks to ensure the variables are of the correct type and correctly spelled before the comparison logic is executed.

# Conclusion
This repository is a practical demonstration of common errors in Python programs. Users are encouraged to use this program as a learning tool to improve their debugging skills and understanding of Python syntax and logical flow.

