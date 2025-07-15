# Power-BI-Sales-Data-Analysis
# 📊 Power BI Sales Data Analysis

This Power BI project analyzes and transforms sales data using various data cleaning, transformation, and modeling steps. The report is built in **Power BI Desktop (.pbix)** format.

## 📁 File Structure

- `All_sales.pbix`: Main Power BI report file containing all transformations, calculations, and merged tables.
- `Transformation_Steps.pdf` or `Transformation_Steps.docx`: Document with step-by-step explanation of all actions performed in Power Query and Power BI.

---

## Section 1: Data Loading and Initial Cleanup

1. **Load the Dataset**  
   Imported sales data from Excel into Power BI using `Get Data`.

2. **Power Query Editor**  
   All data cleaning and shaping operations were done inside the Power Query Editor.

---

## Section 2: Data Cleaning Tasks

3. **Removed Unnecessary Columns**  
   - Deleted columns not required for analysis (e.g., `Region_and_Sales_Rep`).

4. **Renamed Columns for Clarity**  
   - Applied consistent and readable names like `Sales Representative`, `Sale Date`, `Product ID`, etc.

5. **Reordered Columns**  
   - Arranged columns logically starting from `Sale Date`, `Product ID`, `Sales Representative` to financial metrics.

6. **Corrected Data Types**  
   - Date, numeric, and categorical fields were converted to appropriate types.

7. **Formatted Currency Fields**  
   - `Sales Amount`, `Unit Cost`, and `Unit Price` were formatted as currency.

8. **Removed Null Rows**  
   - Filtered out records with missing `Sales Representative` data.

---

## Section 3: Data Transformation

9. **Conditional Column: Sales Performance**  
   - Categorized sales as `High`, `Medium`, or `Low` based on `Sales Amount`.

10. **Calculated Column: Total Profit**  
   - Formula: `(Unit Price - Unit Cost) * Quantity Sold`

11. **Calculated Column: Final Sale Price**  
   - Formula: `Sales Amount * (1 - Discount)`

---

## Section 4: Appending & Merging

12. **Duplicated Table: Historical Sales**  
   - Created `Historical_Sales` table filtered for sales before `01-Jan-2023`.

13. **Appended Tables**  
   - Combined `All_Sales` and `Historical_Sales` into a unified table.

14. **Merged External Product Info**  
   - Joined external `Product_Info` table containing `Product Name` and `Category Manager` using `Product ID`.

---

## Section 5: Final Steps

15. **Loaded Cleaned Data**  
   - Clicked `Close & Apply` to make all cleaned and transformed data available for building visuals.

---


---

## 📝 Notes

- This file is created for assignment/reporting purposes.
- `.pbix` can be opened with Power BI Desktop.

---

## 🔗 Author

- 👩 **Hasti Gohel**  
- GitHub: [HastiGohel](https://github.com/HastiGohel)
- LinkedIn : [HastiGohel](https://www.linkedin.com/in/hasti-gohel1527/)
