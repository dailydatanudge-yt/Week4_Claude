---
name: csv-quality-skills-demo
description: Checks a CSV file for data quality issues. Use when the user asks to validate, check, or profile a CSV file.
---

# CSV Quality Check

When checking a CSV file, follow these steps in order:

1. Read the file. Report the row count and column names.
2. Check for these issues:
   - Missing values (empty cells)
   - Duplicate rows
   - Invalid dates
   - Negative numbers in quantity or price columns
3. For each issue, report:
   - The row number
   - The column
   - Severity: high, medium, or low
   - A suggested fix
4. End with a one-line summary: total issues found.
5. Do NOT modify the original file.