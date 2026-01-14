# Customer Behavior & Profitability Analysis

## 📊 Project Overview
An in-depth customer segmentation and profitability analysis conducted for a retail/e-commerce business. Using transaction data in Excel, this project applied RFM (Recency, Frequency, Monetary) analysis to segment the customer base, identify high-value behaviors, and uncover retention risks. The insights led to a framework for tiered, targeted marketing strategies aimed at maximizing customer lifetime value.

**Full Case Study:** [Read the detailed analysis on Medium](https://medium.com/@horla1/understanding-customer-behavior-and-maximizing-profitability-an-analysis-of-marketing-strategies-df5fec85bf31)

## 🎯 Business Objectives
*   **Increase Profitability:** Identify which customer segments contribute the most to revenue and profit.
*   **Reduce Churn:** Pinpoint "At-Risk" customers and develop strategies to retain them.
*   **Optimize Marketing Spend:** Move from broad campaigns to targeted actions based on customer value and behavior.
*   **Understand the 80/20 Rule:** Quantify how much revenue comes from the top segment of customers.

## 🔍 Key Insights & Strategic Recommendations
| Customer Segment | Key Characteristics | Proposed Strategy |
| :--- | :--- | :--- |
| **High-Value Loyalists** | Top 20% by revenue, frequent purchases, high engagement. | **Tiered Rewards:** Create an exclusive loyalty program with early access, premium support, and personalized offers. |
| **At-Risk Spenders** | Historically high value but recent decline in engagement (high recency score). | **Win-Back Campaigns:** Deploy targeted reactivation emails with special incentives and surveys to understand their departure. |
| **Mass Market** | Large volume, moderate frequency, lower average order value. | **Upsell/Cross-Sell:** Use bundling recommendations and volume discounts to increase average basket size. |
| **Need-Based / Occasional** | Low frequency, purchase only with specific needs or promotions. | **Re-engagement Triggers:** Use triggered emails based on browsing behavior or time since last purchase. |

## 🛠️ Technical Implementation

### Methodology & Tools
*   **Tool:** Microsoft Excel (Advanced Formulas, PivotTables, Data Visualization)
*   **Methodology:** RFM (Recency, Frequency, Monetary) Analysis, Customer Segmentation, Cohort Analysis
*   **Process:** Data cleaning and preparation → RFM scoring and cohort creation → Segment analysis and profiling → Insight generation and strategy formulation.

### Analytical Approach

1.  **Data Preparation:** Aggregated and cleaned customer transaction data, focusing on key fields like Purchase Date, Customer ID, Order Value, and Product Category.

2.  **RFM Scoring & Segmentation:** Applied the RFM (Recency, Frequency, Monetary) model using Excel formulas and PivotTables:
    *   **Recency (R):** Calculated as the number of days since each customer's last purchase. Customers were ranked, with the most recent purchasers receiving the highest scores. This identified **"At-Risk Spenders"** who had not purchased in a critical recent timeframe.
    *   **Frequency (F):** Counted the total number of transactions per customer over the analysis period. This metric separated **"High-Value Loyalists"** (frequent buyers) from **"Need-Based/Occasional"** customers.
    *   **Monetary (M):** Summed the total revenue contributed by each customer. This directly quantified customer value and was instrumental in validating the **80/20 rule**, showing that a small segment contributed the majority of profits.

3.  **Segment Analysis:** Combined RFM scores to create four actionable customer segments, each with distinct behavioral profiles:
    *   **High-Value Loyalists (Champions):** High scores across all three RFM dimensions.
    *   **At-Risk Spenders:** Historically high Monetary value but declining Recency scores.
    *   **Mass Market:** Moderate Frequency and Monetary scores, representing the reliable core.
    *   **Need-Based / Occasional Shoppers:** Low Frequency, purchasing primarily during promotions or for specific needs.

4.  **Profitability & Strategic Mapping:** Analyzed the revenue concentration within segments and mapped each segment to a tailored marketing strategy to improve retention, increase share-of-wallet, and maximize Customer Lifetime Value (CLV).

### Key Calculations & Excel Techniques
*   **Pareto Analysis:** Used to confirm that ~80% of revenue came from ~20% of customers.
*   **Cohort Tables:** Built to visualize customer retention over time.
*   **Advanced Formulas:** Leveraged `SUMIFS`, `COUNTIFS`, `VLOOKUP/XLOOKUP`, and pivot table calculated fields for dynamic analysis.

## 📈 Results & Impact
*   **Identified the "High-Value Loyalist" segment** responsible for approximately **80% of company revenue**, validating the Pareto Principle.
*   **Mapped the customer journey**, identifying the specific point where "At-Risk Spenders" began to disengage.
*   **Delivered a clear, actionable marketing framework** that shifted strategy from one-size-fits-all to personalized, segment-specific campaigns aimed at improving retention and CLV (Customer Lifetime Value).

## 💡 Lessons Learned
*   **Simple Tools, Powerful Insights:** Deep business insight can be derived using foundational tools like Excel when paired with a clear analytical framework (like RFM).
*   **The Story is Key:** Translating data segments into relatable customer personas (e.g., "At-Risk Spender") is crucial for driving business action.
*   **Actionability Over Complexity:** The most valuable analysis directly leads to specific, testable recommendations for the business team.

---
*This project demonstrates the application of core customer analytics techniques to solve a real business problem. For questions or opportunities.*
