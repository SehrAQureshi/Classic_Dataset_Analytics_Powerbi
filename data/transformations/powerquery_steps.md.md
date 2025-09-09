# 🔄 Data Cleaning & Transformation – Power Query (Power BI)

The raw dataset contained duplicates, missing values, and inconsistent product categories.  
All cleaning and transformations were performed in **Power BI Power Query** before modeling.

### 🧹 Key Cleaning Steps
1. **Removed duplicates** from Orders table.  
2. **Handled null values** by replacing missing totals with 0 and filling missing categories.  
3. **Standardized product names** (e.g., “Classic Car”, “classic cars”, “Cars-Classics” → **Classic Cars**).  
4. **Created a Date table** for proper time-series analysis.  
5. **Merged queries** to link Orders with Product and Customer details.  
6. **Added calculated columns** for Profit = Sales – Cost.  
7. Ensured data types (Date, Number, Currency) were correctly set.  

---

✅ These steps ensured the dataset was clean, consistent, and ready for dashboarding in Power BI.
