# Retail Store Sales – Data Cleaning (Excel + Power Query)

Cleaned a messy 12,575-row retail transactions dataset — missing values in Item, Price, Quantity, Total Spent, and Discount.

**Dataset:** [Retail Store Sales – Dirty for Data Cleaning (Kaggle)](https://www.kaggle.com/datasets/ahmedmohamed2003/retail-store-sales-dirty-for-data-cleaning)

## What I did
- Rebuilt missing Quantity / Price / Total Spent using `Total Spent = Quantity × Price`
- Validated every row with an error-check column → 0 mismatches
- Recovered ~9% of missing Item names by matching Category + fixed Price per item (unmatched rows flagged, not guessed)
- Replaced missing Discount values with `n/a`
- Flagged every estimated value (`is_item_estimated`) for full transparency

## Result
| Column | Before | After |
|---|---|---|
| Item | 91% valid | 100% valid |
| Price / Qty / Total Spent | 95% valid | 100% valid |
| Discount Applied | 68% valid | 100% valid |

## Tools
Excel, Power Query (M)

## 🎥 Video Walkthrough
[Watch on YouTube](https://youtu.be/Li1BpmOGv0o)

---
**Author:** Abdelrahman | Data Analyst & AI Automation Specialist
[LinkedIn](https://www.linkedin.com/in/abdelrahman-bahaa-lotfy-8ba35131b) · [GitHub](https://github.com/abdelrahmanbahaa-lotfy)

## ✅ Key Takeaway
Instead of dropping or guessing missing values, this project used relationships already inside the data (Quantity × Price = Total, and fixed Price per Item) to recover real values — and clearly flagged every assumption for transparency.

---
**Author:** Abdelrahman | Data Analyst & AI Automation Specialist
[LinkedIn](https://www.linkedin.com/in/abdelrahman-bahaa-lotfy-8ba35131b) · [GitHub](https://github.com/abdelrahmanbahaa-lotfy)
