# Data Cleaning Process

## Overview
This project involves cleaning and formatting data in an Excel file to ensure consistency and accuracy. Below are the specific steps taken to clean the dataset.

## Steps Performed

1. **Remove Duplicates**
   - Identified and removed duplicate rows (e.g., row 46 with "Barack Obama").

2. **Create 'president-fixed' Column**
   - Converted the 'President' column to proper case using the `PROPER()` function.

3. **Add Filters**
   - Applied filters to all columns for easier sorting and data analysis.

4. **Fix the 'Party' Column**
   - Standardized and corrected values in the 'Party' column.

5. **Remove Spaces in 'Vice' Column**
   - Used the `TRIM()` function to remove extra spaces and created a new column named 'vice-fixed'.

6. **Convert Salary Type**
   - Changed the 'Salary' column from text to number format and removed additional zeros.

7. **Fix Date Columns**
   - Reformatted date columns to use the 'Short Date' format for consistency.

8. **Delete Useless Columns**
   - Removed unnecessary columns: `firstone`, `president-fixed`, `prior`, and `vice-fixed` to keep the dataset clean.

## How to Use
- Open the cleaned Excel file.
- Use filters to explore and analyze the data.
- Ensure formatting consistency before performing further analysis.

## Contributing
Feel free to suggest improvements or additional cleaning steps by opening an issue or submitting a pull request.

by ENNAH Ghizlane

