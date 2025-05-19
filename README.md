
# 📊 Customer Performance Dashboard

This Power BI dashboard provides detailed customer performance insights by leveraging advanced DAX calculations, dynamic visualizations, and interactive storytelling. The goal is to uncover high-value customer segments, evaluate demographic-based revenue patterns, and offer actionable intelligence for marketing, sales, and executive teams.

---

## 🔍 Business Challenge

Companies often launch marketing campaigns without understanding which customer segments drive the most revenue. This dashboard addresses that gap by:

- Identifying high-value customer groups
- Highlighting key demographics (e.g., customers with children, gender)
- Offering localized insights (e.g., top-performing countries)

---

## 🧠 Key Metrics & DAX Measures

### Revenue Measures
- **Total Revenue** – Revenue from all orders
- **CWC Revenue** – Revenue from customers with children
- **CWOC Revenue** – Revenue from customers without children
- **% Female Revenue** / **% Male Revenue** – Contribution by gender

### Visual & Conditional Formatting
- **CF Female / CF Male** – Highlights dominant gender segment
- **Avg Revenue (Age Group)** – Average revenue by age bracket
- **CF Age-Group** – Colors age groups above average (yellow)
- **Avg Caption** – Sentence-level summary for age group performance

### Country-Level Insights
- **Top Country CWC** – Country with the highest CWC revenue
- **% CWC in Country** – Proportion of CWC in that country
- **Revenue by Country** – Total revenue per country
- **Country Caption** – Dynamic narrative: e.g., _“Germany leads with 57.43% of customers with children…”_

### Customer Leaderboard
- **Customer Revenue** – Calculates revenue per customer
- **Top Customers** – Ranks customers dynamically with `RANKX` and `TOPN`
- **Dynamic Customers Title** – Adapts title based on slicer selection

---

## 🌍 Key Insights

- 👨‍👩‍👧‍👦 **Customers with children** generate the majority of total revenue.
- ♀️ **Female customers** slightly outperform males in total revenue.
- 📊 The **41–60 age group** drives the highest revenue.
- 🌍 **Germany** stands out as the top country in the children segment.
- 🏆 **Top 3 customers** account for a significant share of overall revenue.

---

## 🛠️ Tools & Skills Demonstrated

- **Power BI** – Interactive dashboard creation
- **DAX** – Advanced measures with `CALCULATE`, `SUMX`, `RANKX`, `TOPN`
- **Star Schema Modeling** – Dimensional modeling with `RELATED`
- **Dynamic Storytelling** – Narrative KPI summaries and color cues
- **Responsive Design** – Slicers, dark/light mode, dynamic titles

---

## 📁 Repository Structure

```
📦 customer-performance-dashboard/
 ┣ 📄 customer-performance-dax.txt   # All custom DAX measures used
 ┣ 📊 dashboard image.png/           # Include dashboard images
 ┣ 📄 README.md                      # Project overview and documentation
 ┣ 📊 Customer Performance.pbix/     # Include Power BI project
```

---

## 🧠 How to Use

1. Open the Power BI `.pbix` file (not included here for privacy).
2. Connect to your dataset with similar schema:
    - `FactTable` (OrderQuantity, ProductID, CustomerID)
    - `DimCustomer` (Gender, Age Group, Country, TotalChildren)
    - `DimProduct` (ProductID, Price)
3. Import the provided DAX measures.
4. Customize visuals and slicers as needed.

---

## 📬 Contact

**Stanley Chinor Okoro**  
[GitHub Profile](https://github.com/timelesshov) • [LinkedIn](https://www.linkedin.com/in/timelesshov) • 📧 stanley.chinor@gmail.com

---

> “Turning data into dynamic customer stories for smarter decisions.”
