# Excel-Data-Analysis-Car-Sales
Simple Analysis of a car sales dataset, with specific actions performed to clean the data in Excel, analysis with formulas, pivot table, charts and spreadsheet visualization
### Source:
[Kaggle](https://www.kaggle.com/)
### Original dataset and .csv file:
[Car Sales Dataset](https://www.kaggle.com/gagandeep16/car-sales)
### Preliminary actions: 
saved from .csv to .txt file (sometimes my Excel does NOT convert directly a .csv file), upload in excel, converted to .xlsx file.
### Data cleaning: 
1. some alignment, spell checking in Manufacturer and Model (one correction for Cadillac Escalade in car models), 
2. delete both two Saab models as NO known models, and impossible to understand what models could be referred to,
3. format as number column C,G,H,I,J,K,L,M,N and P, 
4. format with no decimal value (with ,) column C,G,H,I,J,K, M,N and P, 
5. transform all text in column E in Passenger, 
6. delete row Town&Country Model of Crysler as too many value missing, 
7. for column C, Sales in Thousands: manual correcting some values with point, cutting the dor (.) and adding a zero, this looks reasonable, then renamed the column as Unit Sales
8. for column D, Price in Thousands: for all values where there is 1 digit only after the dot (.) added 2 zero; for all values where there are 2 digits only after the dot (.) added 1 zero; for all values where there are 2 digits only: added the dot(.) plus 3 zeros; all manual, all very boring, but necessary for the analysis; for price missing in row 4 (Acura CL) deleted the row; at the end renamed the column with Price and formatted as Currency USD
9. for column D, Year Resale Value: for all values where there is 1 digit only after the dot (.) added 2 zero; for all values where there are 2 digits only after the dot (.) added 1 zero; for all values where there are 2 digits only: added the dot(.) plus 3 zeros; 
10. after that changing position of column D to new column E and of column F in new column D, this for better reading
11. for column L (Curb Weight): for all values where there is 1 digit only after the dot (.) added 2 zero; for all values where there are 2 digits only after the dot (.) added 1 zero; for all values where there are 2 digits only: added the dot(.) plus 3 zeros; google search (Wikipedia) for missing value for Cadillac Seville, answer is 3900, inserted this value in column;
12. at the end pls see the original sheet and the cleaned data sheet
### Preliminary analysis: 
first analysis with new column and use of formulas IFS, COUNTIF, SUMIFS and VLOOKUP
### Pivot Table and data visualization: 
1 table and 7 different pivot tables with chart visualizations
### Spreadsheet: 
2 spreadsheets with several charts, first spreadsheet about total unit sales and total value sales per manufacturers, second spreadsheet with analysis about price and year retention value
### Link to my Excel worksheet:
[Data Visualization Car Sales ](https://1drv.ms/x/s!Ajw--mdpw7pbgZlGXnLRrjKCmHfqcw?e=7Qrjsp)

