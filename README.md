# Customer & Retail Insights

This portfolio showcases two projects analyzing customer purchasing behavior and store performance trials in the retail snack category. Each project demonstrates data-driven insights to inform category strategy and promotional decision-making.

## Project 1: Customer Segment & Chips Purchasing Behavior Analysis

**Objective**  
Understand customer segments and their purchasing behavior in the chips category, enabling the Category Manager to make informed decisions for product assortment and promotions.

**Story**  
Customers behave differently based on lifestage and premium tier. By analyzing transactions and demographics, we can uncover:  
- Who buys chips and when  
- Which pack sizes and brands are preferred  
- Which segments drive the most sales  

**Approach**  
- **Data Preparation:** Cleaned transaction and customer datasets, handled outliers, and removed non-chip products.  
- **Feature Engineering:** Extracted features such as pack size, brand, and customer segment.  
- **Exploratory Analysis:** Examined sales trends, seasonality, and segment contributions.  
- **Insight Generation:** Calculated metrics like average units per customer and average price per unit, and analyzed brand affinity.  

**Key Insights**  
- **Sales Drivers:** Most chip sales come from Budget - Older Families, Mainstream - Young Singles/Couples, and Mainstream - Retirees.  
- **High Spend Segments:** Higher sales often driven by more customers, some by higher units per customer or higher price per packet.  
- **Willingness to Pay:** Mainstream Midage and Young Singles/Couples are willing to pay higher prices per packet, suggesting impulse buying behavior.  
- **Brand Preference:** Mainstream Young Singles/Couples are 23% more likely to purchase Tyrrells and show strong affinity for Twisties 270g packs.  

**Strategic Implications**  
- Place Tyrrells and popular pack sizes in high-traffic, discretionary areas frequented by Young Singles/Couples.  
- Run targeted promotions during peak periods (e.g., holidays) to encourage impulse purchases.  
- Focus premium campaigns on high-value customers to grow margins, while supporting mainstream segments with volume-driven promotions.  

---

## Project 2: Trial Store Performance Evaluation

**Objective**  
Assess the impact of a promotional trial conducted in stores 77, 86, and 88, comparing results against selected control stores to determine changes in sales and customer behavior.

**Story**  
Promotional trials allow testing strategies before a full rollout. By comparing trial stores to similar controls, we can distinguish between natural variability and true promotional impact.

**Approach**  
- **Control Store Selection:** Identified stores similar in sales and customer patterns using correlation and magnitude distance.  
- **Data Scaling:** Normalized pre-trial data for fair comparison.  
- **Statistical Testing:** Applied t-tests and confidence intervals to measure significance.  
- **Visualization:** Tracked sales and customer trends across pre-trial and trial periods.  

**Key Findings**  

| Trial Store | Control Store | Key Findings |
|------------|---------------|--------------|
| 77 | 233 | Sales and customer count both increased significantly — strong trial effect. |
| 86 | 155 | Customer visits rose, but sales impact not significant — possible pricing effect. |
| 88 | 178 | Higher sales but lower customer counts — spending per customer increased. |

**Strategic Implications**  
- The trial had positive but varied effects across stores.  
- Suggests reviewing promotion design, pricing, and timing before scaling.  
- Future trials could incorporate segment-level analysis and customer behavior monitoring for optimized ROI.  

---

## Conclusion

Together, these projects demonstrate how data-driven insights can guide retail strategy:  
- Understand which customers drive sales, what they buy, and at what price.  
- Identify opportunities for targeted promotions and assortment optimization.  
- Measure trial store performance to scale successful strategies and avoid ineffective ones.  

By combining customer insights and experimental analysis, retailers can maximize sales, enhance customer experience, and make confident strategic decisions.
