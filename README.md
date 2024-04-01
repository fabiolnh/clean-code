# Clean Code

## Code Smell

- Variable names should be comprehensive: Rename variables.
- Magic Numbers: Name the numbers to static variables.
- Comments: Avoid commenting excessively. Code should be self-explanatory. Comments should be rare. Use methods to explain functionality.
- Dead Code (Commented code): Exclude it. Do not commit commented-out code. Git provides version control. If you want to keep the code for future use, consider using a feature flag (e.g., a variable to toggle functionality on or off).
- Blank Lines: Do not use blank lines within methods. Exclude them.
- Duplicated Code: Extract duplicated code into a method (in general). There may be exceptions.
- Variable Declarations: Avoid declaring variables too far from their utilization.
- Early Returns: In a lot of "ifs", abort conditions as early as possible. Use "return" and "continue".
- Excessive Ternaries: Replace overly complex ternary expressions with "if" statements.
- Exceptions: Instead of returning error codes, throw exceptions.
