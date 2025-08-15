This project uses the **Online Retail dataset** to group customers based on their purchase behavior using **RFM analysis** (Recency, Frequency, Monetary).

## Steps
1. Cleaned the data (removed duplicates, missing IDs, and cancelled orders).
2. Calculated **RFM values**:
   - Recency = days since last purchase  
   - Frequency = number of purchases  
   - Monetary = total spending  
3. Gave each customer an **RFM Score** (1–5).
4. Segmented customers into groups:
   - Champions
   - Loyal Customers
   - Big Spenders
   - At Risk
   - Others
5. Created **visualizations**:
   - Bar chart of customer segments  
   - Heatmap of monetary value by Recency & Frequency scores  

## Tools
- Python (Pandas)  
- Seaborn, Matplotlib  
- Jupyter Notebook  
