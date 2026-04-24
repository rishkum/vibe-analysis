# General Guidance
- Prioritize readability and maintainability.
- Add comments explaining *why* something is done, not just *what*.

# R Specific Guidelines
- ALWAYS use `tidyverse` (e.g., `dplyr`, `tidyr`, `ggplot2`, `readr`) instead of base R functions. For example, use `read_csv()` rather than `read.csv()`.
- Use the pipe operator `%>%` (or `|>`) to chain functions sequentially.
- Use `snake_case` for all variable and function names.

# Python Specific Guidelines
- Use `pandas` for data manipulation, aiming for vectorized operations rather than base loops.
- Use `snake_case` for variables and functions, and `PascalCase` for classes.
- Provide type hints for all function arguments and return types.
