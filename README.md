# 🛒 Customer Value Segmentation – RFM Analysis (Woolworths Chip Category)

## 📖 Project Overview

This project applies **RFM (Recency, Frequency, Monetary) segmentation** and **product performance analytics** to Woolworths’ chip category. By analysing **242,128 transactions** from **70,217 customers**, we classify shoppers into **8 distinct customer segments** (Champions, Loyal, Promising, New, Can’t Lose Them, Need Attention, At Risk, and Lost) and evaluate brand, flavour, and pack-size preferences.

<img width="1389" height="790" alt="image" src="https://github.com/user-attachments/assets/a9a2fefd-ae27-4378-9469-9132561234c5" />


The goal is to generate insights that support **customer retention**, **promotional optimisation**, and **range efficiency** in the chip category’s next review cycle.

---

## 🎯 Key Findings

* **Retention risk is high:** 32.8% of customers are Lost and 13.5% At Risk. Nearly half the base requires urgent retention actions.
* **Revenue concentration:** Champions (10.1%) spend the most per head, but Loyal Customers (22.9%) contribute the most revenue (35%).
* **Demographic insights:** Retirees and Older Couples dominate Loyal/At Risk, while Young Singles/Couples cluster in Lost/New groups.
* **Product drivers:** Doritos, Pringles, and Kettle are category anchors. Niche brands (e.g., Cheezels, Cobs) over-index in some segments, suggesting targeted range reviews.
* **Pack sizes:** Medium packs (\~52%) dominate; small packs (1.9% of sales, only 3 SKUs) may be underdeveloped.
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/a12780ec-fe73-475c-b086-8cf2180e6366" />

<img width="1291" height="989" alt="image" src="https://github.com/user-attachments/assets/8284b6d7-4ff6-48ff-82c7-9199ba51f023" />

<img width="1310" height="989" alt="image" src="https://github.com/user-attachments/assets/77021ac2-956f-422c-b415-57a5dd6acbde" />

<img width="1389" height="790" alt="image" src="https://github.com/user-attachments/assets/288686fd-9beb-489c-b272-f4ba98ef9ea1" />

---

## 🛠️ Tools & Methods

* **Python:** Pandas, NumPy, Matplotlib, Seaborn
* **Segmentation:** RFM scoring with quartiles, mapped to 8 actionable groups
* **Product Analysis:** Brand concentration, pack-size breakdown, flavour performance, seasonal/weekly trends
* **Data Storytelling:** Visualisations and a presentation deck

---

## ⚖️ Critical Reflection

* **Strengths:** Simple, interpretable segmentation framework with clear retention signals. Combines customer and product views.
* **Limitations:** RFM assumes past behaviour predicts future value; lacks qualitative context (e.g., motivations). Premium vs Budget tiers may not reflect actual spend behaviour.
* **Future Directions:** Layer clustering (K-means on flavour/size preferences), test retention campaigns, and explore cross-category linkages (snacks, beverages).

---

## 💡 Recommendations

**Customer Retention**

* Upsell **Champions** with premium bundles or exclusives.
* Maintain consistency for **Loyal Customers** but introduce gradual upgrades.
* Onboard **New Customers** with safe flavours, then trial bold variants.
* Re-engage **At Risk / Need Attention** with flavour-led promos (Cheese for Need Attention; Salt & Vinegar/Meat for At Risk).

**Product & Range Optimisation**

* Rationalise long-tail SKUs (\~50% contribute <20% of sales).
* Reduce flavour clutter; double down on top sellers.
* Expand small-pack range to test unmet demand.
* Prioritise **Medium packs** for promotions; monitor saturation in Large packs.

**Strategic Growth Levers**

* Don’t equate Premium tier with value — high spenders are often Budget shoppers.
* Treat shelf space as dynamic: boost mid-tier performers seasonally; prune stagnant brands.
* Consider redefining segmentation logic by layering frequency, flavour, and demographic clusters.

---

