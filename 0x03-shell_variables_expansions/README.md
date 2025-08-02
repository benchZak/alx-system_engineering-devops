# Shell Variables Expansions

This repository contains scripts that demonstrate various shell variable expansions and manipulations in Bash.

## Scripts

### 0. Create an alias
- **File:** `0-alias`
- **Description:** Creates an alias `ls` with the value `rm *`.

### 1. Hello you
- **File:** `1-hello_you`
- **Description:** Prints "hello user", where user is the current Linux user.

### 2. Add /action to PATH
- **File:** `2-path`
- **Description:** Adds `/action` to the PATH environment variable, making it the last directory the shell looks into.

### 3. Count directories in PATH
- **File:** `3-paths`
- **Description:** Counts and prints the number of directories in the PATH environment variable.

### 4. List environment variables
- **File:** `4-global_variables`
- **Description:** Lists all environment variables.

### 5. List all variables and functions
- **File:** `5-local_variables`
- **Description:** Lists all local variables, environment variables, and functions.

### 6. Create local variable
- **File:** `6-create_local_variable`
- **Description:** Creates a new local variable named `BEST` with value `School`.

### 7. Create global variable
- **File:** `7-create_global_variable`
- **Description:** Creates a new global variable named `BEST` with value `School`.

### 8. Addition with environment variable
- **File:** `8-true_knowledge`
- **Description:** Prints the result of 128 plus the value stored in the environment variable `TRUEKNOWLEDGE`.

### 9. Division with environment variables
- **File:** `9-divide_and_rule`
- **Description:** Prints the result of `POWER` divided by `DIVIDE` (both environment variables).

### 10. Exponentiation with environment variables
- **File:** `10-love_exponent_breath`
- **Description:** Displays the result of `BREATH` to the power `LOVE` (both environment variables).

### 11. Binary to decimal conversion
- **File:** `11-binary_to_decimal`
- **Description:** Converts a binary number stored in `BINARY` environment variable to base 10.

### 12. Letter combinations
- **File:** `12-combinations`
- **Description:** Prints all possible combinations of two lowercase letters (a-z), except 'oo', in alphabetical order.

### 13. Print float with 2 decimal places
- **File:** `13-print_float`
- **Description:** Prints a number stored in `NUM` environment variable with two decimal places.

## Requirements
- All scripts are written for Bash shell
- All scripts are exactly two lines long (shebang + command)
- All files are executable (`chmod u+x`)

## Author
[Your Name] - ALX Software Engineering Student
