# week_7_Q4_tds

# Supply Chain Analytics: Correlation Matrix Visualization  

## Business Context  
OptimalFlow Logistics is a supply chain consulting firm that helps manufacturing companies optimize procurement and inventory management.  

A major automotive manufacturer provided supplier performance data from **62 procurement transactions** over the past quarter. The goal is to analyze relationships between supply chain variables to support **supplier selection, inventory planning, and cost optimization**.  

The dataset includes the following metrics:  
- **Supplier_Lead_Time**: Days from order placement to delivery  
- **Inventory_Levels**: Current stock quantities (units)  
- **Order_Frequency**: Number of orders placed per month  
- **Delivery_Performance**: On-time delivery rate (%)  
- **Cost_Per_Unit**: Unit cost in dollars ($)  

---

## Task Overview  
This project delivers a **correlation analysis and visualization in Excel** following best practices from the *Visualizing Forecasts with Excel* module.  

### Deliverables:  
1. **Correlation Matrix (CSV)** – Computed using Excel’s Data Analysis ToolPak  
2. **Heatmap (PNG)** – Conditional formatting applied with **Red-White-Green** palette  
   - Red = Low correlation  
   - White = Neutral correlation  
   - Green = High correlation  
3. **README.md** – Documentation with project details and contact  

---

## Methodology  

### Step 1: Enable Analysis ToolPak  
- Go to **File → Options → Add-ins → Analysis ToolPak → Go → Check “Analysis ToolPak” → OK**  

### Step 2: Generate Correlation Matrix  
- Navigate: **Data → Data Analysis → Correlation**  
- Select all 5 data columns, check **“Labels in first row”**  
- Output to new worksheet  

### Step 3: Apply Conditional Formatting (Heatmap)  
- Copy correlation matrix to a new sheet  
- Highlight correlation values (exclude labels)  
- Navigate: **Home → Conditional Formatting → Color Scales**  
- Select **Red-White-Green** palette  

### Step 4: Export Outputs  
- **Save correlation matrix** as `correlation.csv`  
- **Take screenshot of heatmap** (size between **400x400 and 512x512 px**) → save as `heatmap.png`  

---

## Repository Structure  

📂 Supply-Chain-Correlation
│── README.md
│── correlation.csv
│── heatmap.png


---

## Validation Checklist  
✅ `README.md` contains project description and **email**  
✅ `correlation.csv` includes correct correlation matrix values  
✅ `heatmap.png` shows Excel conditional formatting with **Red-White-Green** scale  
✅ Heatmap image dimensions are within **400x400 – 512x512 px**  

---

## Contact  
📧 Email: **22f3000814@ds.study.iitm.ac.in**  

---

