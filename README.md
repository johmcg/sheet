# Sheet - Spreadsheet Web App

Sheet is a Spreadsheet web application based on FreeCodeCamp's Spreadsheet tutorial. The following functions are supported within Sheet, allowing users to perform advanced calculations and data manipulation directly within their cells.

## Function Overview

The following functions are available for use in your Sheet cells:

* **Statistical Calculations:**
    * `sum(range)`: Calculates the sum of the numbers in the specified range.
    * `average(range)`: Calculates the average (mean) of the numbers in the specified range.
    * `median(range)`: Calculates the median of the numbers in the specified range.
    * `count(range)`: Returns number of items in range.
* **Filtering and Checking:**
    * `even(range)`: Returns a list of even numbers from the specified range.
    * `someeven(range)`: Returns `TRUE` if at least one number in the range is even, `FALSE` otherwise.
    * `everyeven(range)`: Returns `TRUE` if all numbers in the range are even, `FALSE` otherwise.
* **List Manipulation:**
    * `firsttwo(range)`: Returns the first two numbers from the specified range.
    * `lasttwo(range)`: Returns the last two numbers from the specified range.
    * `increment(range)`: Returns a new list with each number in the range incremented by 1.
    * `nodupes(range)`: Returns a list of unique numbers from the specified range.
* **Search and Inclusion:**
    * `has2(range)`: Returns `TRUE` if the range contains the number 2, `FALSE` otherwise.
* **Data Generation:**
    * `random(min, max)`: Generates a random integer between `min` and `max` (inclusive).
    * `range(start, end)`: Generates a list of integers from `start` to `end` (inclusive).

## Usage in Sheet Cells

To use these functions, enter the function name followed by the required arguments within a cell, using standard Sheet cell range notation.

**Examples:**

1.  **Summing a Range (A1 to A10):**

    * In cell B1, enter: `=sum(A1:A10)`

2.  **Finding the Average of a List (1, 5, 10, 15):**

    * In cell C1, enter: `=average(1, 5, 10, 15)`

3.  **Filtering Even Numbers from Range D1 to D20:**

    * In cell E1, enter: `=even(D1:D20)`
    * *Note: The result will be a list of numbers. Displaying this list may depend on how Sheet handles list outputs within cells.*

4.  **Generating a Random Number Between 1 and 100:**

    * In cell F1, enter: `=random(1, 100)`

5.  **Generating a range of numbers from 1 to 10:**

    * In cell G1, enter: `=range(1,10)`

6.  **Checking if the range A1:A5 contains the number 2:**

    * In cell H1, enter: `=has2(A1:A5)`

**Important Considerations:**

* **Range Notation:** Use standard Sheet range notation (e.g., `A1:B5`).
* **List Outputs:** Functions like `even`, `firsttwo`, `lasttwo`, `increment`, and `nodupes` return lists. How these lists are displayed in cells may vary.
* **Error Handling:** Ensure you provide the correct number and type of arguments to each function. Incorrect usage may result in errors.

