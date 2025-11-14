# Basic-functions-in-excel
This exercise introduces fundamental Microsoft Excel skills through hands-on data manipulation. Users create a spreadsheet, enter a sample dataset, and apply basic functions like SUM, AVERAGE, and COUNT to perform calculations and derive insights from the data, building core Excel functionality familiarity.

Step-by-Step Guide: Excel Data Entry and Basic Functions

Here are the instructions for the Excel exercise you provided in the problem statement:
1. Create a New Excel Workbook
Open Microsoft Excel.
Select Blank workbook to start fresh. You can also access a new sheet via the free Microsoft Excel web application.

2. Enter a Sample Dataset
Create a simple student grade table in the worksheet:

Student Name	Math	Science	English	Total	Average
John Doe	85	78	92		
Jane Smith	90	88	85		
David Lee	72	65	70		
No.of students

Enter the headers in cells A1 through F1.
Enter the student data in rows 2 through 4 under the respective headers.

3. Use Basic Functions (SUM, AVERAGE, COUNT)
A. Use SUM for the "Total" Column:
Click cell E2.
Type the formula =SUM(B2:D2) and press Enter. The sum 255 appears.
Use the fill handle (the small green square in the bottom-right of cell E2) to drag the formula down to cell E4 to calculate totals for all students.

B. Use AVERAGE for the "Average" Column:
Click cell F2.
Type the formula =AVERAGE(B2:D2) and press Enter. The average 85 appears.
Use the fill handle to drag the formula down to cell F4 to calculate averages for all students.

C. Use COUNT to Tally Students:

Click cell A6 and type Number of Students:.
Click cell B6.
Type the formula =COUNT(B2:B4) and press Enter. The result 3 appears, counting the number of entries in the Math column.
