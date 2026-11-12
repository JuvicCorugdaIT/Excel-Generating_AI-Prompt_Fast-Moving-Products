**Excel Inventory Tracker for Fast-Moving Products AI Prompt**  
  
---  
**Copy-and-use prompt**  
Act as an Excel automation specialist, inventory-control analyst, and career-portfolio mentor. Create a **small-business inventory workbookproject** for a fictional shop or warehouse. The workbook should track fast-moving products and provide useful summaries for a manager without requiring advanced database or programming knowledge.  
**1. Business scenario**  
- Business Name:  
- Number of stock-keeping units:  
- Names of product categories:  
- Write below the products following this format: Lot Number (Unique), Product, SKU, Category, Supplier, Quantity, Reorder Level, Unit Cost, Sales:  
   
**2. Workbook design**  
Create an Excel workbook with these sheets:  
1. **Read Me** --- purpose, instructions, definitions, and data limitations.  
2. **Product Master** --- Lot number, SKU, product name, category, unit, supplier, opening stock, reorder level, and unit cost.  
3. **Stock Movements** --- date, reference number, SKU, movement type (RECEIPT, SALE, ADJUSTMENT), quantity, and notes.  
4. **Current Stock** --- calculated on-hand quantity, reorder status, stock value, and last movement date.  
5. **Fast Movers** --- ranked products using a clearly explained sales/quantity metric.  
6. **Dashboard** --- management KPIs, charts, filters/slicers where supported, and concise observations.  
7. **Data Checks** --- duplicate SKUs, invalid movement types, missing product references, negative-stock warnings, and date validation.  
Use Excel Tables, structured references, data validation, conditional formatting, and formulas where appropriate. Make formulas readable and avoid volatile functions unless necessary.  
**3. Summary Tables**  
- create formula-driven summary tables and charts that behave like a  
 pivot-style report, clearly labeled **Summary (formula-driven)**.  
- If using Power Query, VBA, Office Scripts, or Excel COM automation, state the required Excel edition/platform and any macro/security implications. Provide a non-macro alternative when feasible.  
**4. Metrics and business logic**  
Define each metric before implementing it. Include at least:  
- total distinct SKUs;  
- total units on hand;  
- total inventory value;  
- number of products at or below reorder level;  
- units sold by product and category;  
- top 10 fast-moving products over a selected period;  
- average weekly sales or another transparent velocity measure;  
- estimated weeks of stock remaining, only where the data supports a meaningful estimate.  
Clearly distinguish **sales volume** from **revenue** and **profit**. Do not infer profit unless selling price and cost data are supplied.  
Document how returns, adjustments, and negative stock are treated.  
**5. Automation and refresh**  
Provide a simple, beginner-friendly refresh process. If using Python, generate a script that validates the input data and rebuilds or refreshes the workbook. If using Excel formulas only, explain how the user adds transactions and refreshes calculations.  
The automation must:  
- validate required columns and data types;  
- flag unknown SKUs and invalid movement types;  
- preserve the original source CSV or workbook;  
- avoid silently overwriting the only copy;  
- save a timestamped output or create a backup before replacement;  
- produce a clear success/error summary.  
Use `openpyxl` or another appropriate library for workbook creation, but be transparent about PivotTable limitations. Do not rely on unsupported features.  
**6. Required deliverables**  
Generate:  
- `README.md` --- project overview and how to open/use the workbook.  
- `data/products.csv` --- fictional product master.  
- `data/stock_movements.csv` --- fictional transaction history.  
- `scripts/build_inventory.py` or a documented Excel-only procedure.  
- `Fast_Moving_Inventory.xlsx` --- the finished workbook.  
- `docs/Data_Dictionary.md` --- field definitions and business rules.  
- `docs/User_Guide.md` --- how to enter stock movements and interpret  
   
 the dashboard.  
- `docs/Monthly_Inventory_Report.md` --- sample manager report based  
   
 on the sample data.  
- `docs/Office_Memo.md` --- memo explaining the new inventory  
   
 reporting procedure.  
If file creation is unavailable, provide complete source data and code, plus precise workbook-building instructions.  
**7. Visual and usability standards**  
Use a restrained, professional business style. Apply consistent date, currency, and quantity formats. Freeze useful header rows, set sensible column widths, use filters, and make key warnings understandable without relying on color alone. Avoid clutter and decorative charts that do not answer a business question.  
**8. Final quality checks**  
Reconcile sample totals across sheets. Verify formulas and ranges. Check that sample transactions produce sensible stock balances. Ensure charts and summaries use the intended date range. Confirm that all applicable data is labeled. Never claim the workbook was tested in Excel unless it was actually opened and tested.  
