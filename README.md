# Campus Store Sales - Data Cleaning Project

**My first Excel data cleaning project** 📊

### The Messy Data I Found:
- Mixed dates: `8/1/2025`, `14-08-2025`, `2026`
- 2 rows with `Qty = 0` 
- 1 row with `500% Discount`
- Cashier names: `aisha`, `AISHA`, `Aisha`

### How I Fixed It - Excel Only:
1.  **Dates** → Standardized to `YYYY-MM-DD` with Text to Columns
2.  **Bad Rows** → Filtered + deleted `Qty = 0` 
3.  **Discount** → Capped at 100% with `=IF()`
4.  **Text** → Key Table + `XLOOKUP` to standardize names

### Lesson Learned:
Clean data > Fancy charts. If the data is wrong, the insight is wrong.

**LinkedIn Post:** [Paste your LinkedIn link here] 

#DataAnalytics #Excel #PortfolioProject #NigeriaTech
