This project analyzes the monthly sales ledger of GlobalTech Electronics, a multi-category technology distributor. The raw dataset was collected from disjointed sales systems, containing multiple duplicates, casing inconsistencies, and disconnected supplier data. 

As a Junior Data Analyst, I cleaned the dataset, merged it with the master supplier database, calculated transaction-level profit margins, and generated multi-dimensional summaries to deliver critical insights for executive decision-making.

---

## 2. Business Challenges Addressed
* **Data Duplication:** Resolved transaction logging errors to ensure database integrity.
* **Supplier Data Disconnection:** Consolidated sales logs with the supplier catalog.
* **Profitability Mapping:** Identified revenue and unit volume performance across product categories and key suppliers.

---

## 3. Tech Stack & Methods Used
* **Tool:** Google Sheets / LibreOffice Calc
* **Data Cleaning:** `Remove Duplicates`, text standardization, case correction, and number formatting.
* **Data Enrichment:** Sheet-to-sheet relational lookup using `VLOOKUP` with absolute cell references (`$`).
* **Financial Calculations:** Calculated transaction-level profitability: `Gross Profit Margin % = (Revenue - COGS) / Revenue`.
* **Data Aggregation:** Built interactive `Pivot Tables` to analyze category revenues and supplier logistics volume.

---

## 4. Key Business Insights
* **Top Revenue Generator:** The **Screens** category is the highest revenue driver, generating exactly **€2,099.89** this month.
* **Key Supplier (Volume):** **LinkWire Solutions** is the largest supply partner by volume, shipping a total of **95 units** (USB-C Cables).
* **Audio Profitability:** The **Audio** category achieved a net profit of **€1,104.00**, maintaining a robust 60.00% gross profit margin.

---

## 5. Strategic Recommendations
1. **Strengthen Screen Inventory:** Since "Screens" is the top revenue generator, ensure optimal stock levels with *ScreenTech Ltd* to prevent out-of-stock scenarios.
2. **Bulk Freight Negotiations with LinkWire:** Leverage the high shipping volume (95 units) with *LinkWire Solutions* to negotiate better wholesale shipping rates, potentially increasing profit margins.
3. **Audio Category Expansion:** With a 60% margin and €1,104.00 in clean profits, expanding the Audio product catalog (e.g., adding headphones or soundbars) could yield highly profitable growth.
