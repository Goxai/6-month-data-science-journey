# Day 41

# started and completed a mini project
# title: Understanding the January Customer Churn Increase

## problem statement
## Customer churn increased significantly in January compared to previous months (November and December). The goal of this
## analysis was to identify the main drivers of this increase and recommend actions to reduce churn.

## Data Overview

A simulated dataset of 200 customers was analyzed with the following key variables:
Month (Nov, Dec, Jan)
ProductAvailable (Yes/No)
ServiceRating (1–5 scale)
Price
Churn (1 = left, 0 = stayed)

## Key Findings
Finding 1 — Churn Trend Over Time
Churn rates by month:
January: ~73%
November: ~67%
December: ~59%
## Conclusion:
Customer churn clearly increased in January, confirming the business concern.

## Finding 2 — Impact of Product Availability
Churn rate by product availability:
Product NOT available → 100% churn
Product available → ~51% churn
## Conclusion:
Product unavailability is the strongest predictor of churn. If customers cannot get what they want, they leave.

## Finding 3 — Impact of Service Quality
Churn by service rating:
Ratings 1–2 → 100% churn
Ratings 3–5 → ~40–50% churn
## Conclusion:
Very poor service (ratings 1–2) drives extreme churn, but average-to-good service still has moderate churn.

## Finding 4 — Why January Was Worse
Compared to December, January showed:
Lower average service rating
Worse product availability
Similar pricing

## Final Insight:
The January churn spike was driven primarily by worse product availability, with declining service quality as a secondary factor. Price had minimal effect.


## 4. Recommendations
Fix inventory issues first
Track stock levels weekly
Restock before items run out
Improve customer service second
Train staff
Reduce response time
Improve problem resolution
Consider price adjustments last
Only if churn remains high after fixing availability and service.




