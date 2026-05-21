# Make vs. Buy Analysis in Power BI — Case Study

An end-to-end Power BI case study focused on building a powerful **Make versus Buy analysis tool** for supply chain decision-making. The project develops a quote analysis tool, calculates costs across various production volumes, and integrates internal manufacturing cost data — demonstrating how Power BI can replace traditional spreadsheets for complex supply chain analytics.

## Project Overview

Organizations constantly face the decision of whether to manufacture a product in-house (**Make**) or source it from an external supplier (**Buy**). This project builds a full analytical model in Power BI to support that decision — calculating extended and full costs, modeling volume scenarios, assessing internal manufacturing costs, and communicating results through interactive visuals.

**Key business questions answered:**
- What is the full cost of buying from external suppliers at various production volumes?
- Which supplier offers the lowest cost option?
- How do costs change as production volumes scale up or down?
- What are the internal manufacturing costs of the Make option?
- Should the organization make or buy, accounting for capital investment and cost of quality?


## What's Inside

### The Buy Option
- Introduced the **Make vs. Buy framework** in supply chain decision-making
- Explored the **quotes dataset** and analyzed available suppliers
- Calculated **Extended Cost and Full Cost** for each supplier
- Identified the **lowest cost supplier** using cost visualizations
- Understood the concepts of **incremental vs. sunk costs**

### Creating a Volume Parameter and Scenario Analysis
- Built a **volume parameter** to dynamically adjust production quantities
- Created a **scenario analysis tool** to visualize how full costs shift with volume changes
- Handled **non-recurring expenses** in cost calculations
- Analyzed costs for **volumes outside the quoted range**
- Generated **order volume recommendations** based on cost modeling
- Implemented **row-level security** to control data visibility by user role

### The Make Option
- Assessed the **internal manufacturing costs** of the Make option
- Distinguished between **incremental and sunk costs** in the make decision
- Calculated **required unit capacity** for in-house production
- Computed **Full Cost with capital investment** factored in
- Performed a final **Make vs. Buy comparison** to support the decision
- Incorporated **Cost of Quality** into the overall analysis
- Delivered a complete, results-driven wrap-up

---

## 🛠️ Tools & Techniques

| Tool / Feature | Usage |
|---|---|
| Power BI Desktop | Data modeling & visualization |
| DAX | Cost calculations, measures & KPIs |
| Volume Parameters | Dynamic what-if scenario modeling |
| Scenario Analysis | Cost behavior across production volumes |
| Row-Level Security | Role-based data access control |
| Make vs. Buy Framework | Supply chain decision support |
| Cost of Quality | Quality-adjusted cost analysis |

## Dashboard
### 1. Supplier Selection
<img width="509" height="286" alt="Supplier Selection" src="https://github.com/user-attachments/assets/bf67ce3c-254f-4e0c-8c45-fa25f6b17356" />

### 2. Scenario Analysis
<img width="508" height="287" alt="Scenario Planner" src="https://github.com/user-attachments/assets/7c5f38dd-5854-4568-886a-ad6a2f818ac1" />

### 3. Make vs Buy
<img width="508" height="287" alt="Make vs Buy" src="https://github.com/user-attachments/assets/9eba398d-3330-48fb-afc2-8e0b5c1415fa" />

