 GlobalTech Electronics: Sales & Profit Margin Analysis

Hi! Welcome to my first real data analysis project. I built this to practice my spreadsheet skills (cleaning dirty data, combining tables, and analyzing business performance) and to see how data can actually help a business make better decisions.

---

## 1. The Problem
I was working with a monthly sales export from GlobalTech Electronics. The raw data had a few issues that would make any analysis inaccurate:
* It had duplicate transaction rows (the same order was logged twice).
* The product categories had messy writing (some were uppercase, some lowercase, like "audio" and "Audio").
* We didn't know who the suppliers were or how much profit we were actually keeping on each item.

My goal was to clean the data, connect it to our supplier catalog, and figure out which products and suppliers are doing the best.

---

## 2. What I Did (Step-by-Step)
1. **Data Cleaning:** First, I removed the duplicate orders using the built-in duplicate tool. Then, I fixed the inconsistent spelling in the Category column so the filters and pivots would work correctly.
2. **Connecting Tables:** I used `VLOOKUP` to match the Product Name from our sales list to a separate Suppliers sheet. This brought in the correct Supplier Name and Email automatically.
3. **Math & Margins:** I calculated the Gross Profit Margin for every single order using a simple formula: `(Total Revenue - COGS) / Total Revenue`. I formatted everything as Currency and Percentages so it's easy to read.
4. **Summing it up:** I created Pivot Tables to group the data by category and supplier to answer specific business questions.

---

## 3. What I Found (The Insights)
* **Where the money is:** The **Screens** category made the most revenue by far (**€2,099.89** this month). 
* **Most active supplier:** We shipped **95 units** of USB-C Cables from **LinkWire Solutions**. They handle our largest volume.
* **Audio profit:** The **Audio** category is highly profitable. It brought in **€1,104.00** in clean profit after costs, keeping a steady 60.00% margin.

---

## 4. My Recommendations for the CEO (If I were the manager)
1. **Keep Screens Stocked:** Screens are our biggest moneymaker. We should work closely with our screen supplier (*ScreenTech Ltd*) to make sure we never run out of inventory.
2. **Ask for a Volume Discount:** Since we are buying and shipping 95 units from *LinkWire Solutions*, we should ask them for a bulk discount. If we lower our cost, our profit margin will go up even more.
3. **Expand the Audio Catalog:** Since Audio has such a good profit margin (60%) and brought in over €1,000 in net profit, it might be a great idea to add more audio products (like headphones) to the shop.

---
*Feel free to download the `GlobalTech Electronic.xlsx` file in this repository to check out my formulas and Pivot Tables!*
