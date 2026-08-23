# Session 2 - Task 3: Data Insights Summary

## Dataset: Zomato Restaurant Dataset (`zomato_restaurants.csv`)

---

### **1. Structural Insight (`info()`)**
* **Data Completeness & Types:** The dataset contains 15 entries across 5 columns (`restaurant_id`, `restaurant_name`, `cuisine`, `rating`, `votes`, `avg_cost_for_two`).
* **Zero Null Values:** All columns report 15 non-null values, meaning there is no missing data that requires imputation. Text fields are cleanly parsed as `object` and numeric metrics as `int64`/`float64`.

---

### **2. Statistical Insight (`describe()`)**
* **Customer Rating Consistency:** The mean rating across listings is **4.13 / 5.0** with a tight spread (min: 3.7, max: 4.6), showing consistently positive customer reception.
* **Pricing Distribution:** The average dining cost for two people centers around **₹747**, ranging from budget quick-bites (₹250 at chai points) up to fine-dining venues (₹1,600 at barbecue/continental outlets).
