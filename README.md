# Google Sheets Clone

This is a simple Google Sheets clone built using **HTML**, **CSS**, and **JavaScript**. The clone implements basic spreadsheet functions, such as:

- `SUM`
- `AVERAGE`
- `MIN`
- `MAX`
- `COUNT`
- `COUNTA`

## Features


- Perform basic spreadsheet calculations.
- Easy-to-use interface with input cells and a results display area.
- The following functions are supported:
  - **SUM**: Adds a range of numbers.
  - **AVERAGE**: Calculates the average of a range of numbers.
  - **MIN**: Finds the minimum value from a set of numbers.
  - **MAX**: Finds the maximum value from a set of numbers.
  - **COUNT**: Counts the number of numerical values in a range.
  - **COUNTA**: Counts the number of non-empty cells in a range.
- **Cell Selection**:
  - Select multiple cells by holding `Shift` and using the arrow keys (left, right, up, down) to extend the selection.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone git@github.com:AnuradhaHariharan/spreadsheet.git
2.Navigate to the project directory:
   ```bash
   cd spreadsheets
   ```
3.Open the index.html file:
Once you're in the project directory, open the index.html file in your preferred web browser.


## Test Cases

**Test Case 1**: SUM
Formula: =SUM(A1:A4)
Description: This function adds the values in cells A1 to A4.

**Test Case 2**: AVERAGE
Formula: =AVERAGE(A1:A4)
Description: This function calculates the average of the values in cells A1 to A4.

**Test Case 3**: MIN
Formula: =MIN(A1:A4)
Description: This function returns the minimum value from the range A1 to A4.

**Test Case 4**: MAX
Formula: =MAX(A1:A4)
Description: This function returns the maximum value from the range A1 to A4.

**Test Case 5**: COUNT
Formula: =COUNT(A1:A4)
Description: This function counts the number of numerical values in the range A1 to A4.

**Test Case 6**: COUNTA
Formula: =COUNTA(A1:A4)
Description: This function counts the number of non-empty cells in the range A1 to A4.

## Future Enhancements
User Authentication:

**Add user login and registration functionality.**
Users will be able to create their own accounts and save their spreadsheets to their profiles.
Database Integration:

**Implement a backend with a database to store user sheets, allowing them to save, load, and update sheets across sessions.**
Technologies like Node.js and MongoDB can be used for storing user data and spreadsheet contents.
Advanced Calculations:

**Implement more advanced spreadsheet functions like:**
IF Statements: Conditional logic to perform calculations based on certain criteria.
VLOOKUP/HLOOKUP: Searching for data in large datasets.
Pivot Tables: Summarizing data in a table format.
Charts: Adding graphical charts to visualize data.

**Fully Responsive:**

Ensure the application is fully responsive and works smoothly on mobile devices.
Export/Import Sheets:

Allow users to export their sheets to formats like CSV or Excel, and import existing sheets into the app for editing.


## Deployed link:

https://anuradhahariharan.github.io/spreadsheet/
