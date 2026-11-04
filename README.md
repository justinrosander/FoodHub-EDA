# FoodHub EDA

Exploratory analysis of FoodHub order data to understand demand, restaurant performance, delivery efficiency, and customer ratings.

**Notebook:** [`FDS_Project_LearnerNotebook_FullCode.ipynb`](FDS_Project_LearnerNotebook_FullCode.ipynb)

## Project highlights

- **1,898 orders** across **178 restaurants** and **14 cuisines**, with no missing values (736 ratings are `"Not given"`).
- Demand is concentrated: **American, Japanese, Italian, and Chinese** dominate cuisine volume; **Shake Shack, The Meatball Shop, Blue Ribbon Sushi, Blue Ribbon Fried Chicken, and Parm** lead restaurant order counts.
- **Weekends drive more orders** than weekdays, while average total service time stays fairly similar across both periods.
- Average **prep time ≈ 27.4 min** and **delivery time ≈ 24.2 min**; about **10.5%** of orders take more than 60 minutes end to end.
- Order cost shows only a weak relationship with fulfillment time; cuisine mix matters more for revenue opportunity.
- Among restaurants with >50 ratings and average rating >4: **The Meatball Shop, Blue Ribbon Fried Chicken, Shake Shack, and Blue Ribbon Sushi**.



## Project layout

- `data/raw/` — original order data
- `data/processed/` — cleaned / featured datasets
- `reports/figures/` — exported charts
- `src/` — reusable Python helpers
