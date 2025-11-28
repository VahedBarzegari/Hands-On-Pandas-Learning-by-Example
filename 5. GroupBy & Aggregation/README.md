## 📘 Section 5: GroupBy & Aggregation

In this section, you’ll learn how to summarize and analyze large datasets using pandas’ powerful `groupby()` functionality.
Grouping allows you to split your data into meaningful categories and compute statistics like totals, averages, and counts for each group.

This is one of the most important sections for real-world data analysis, especially for transit, operations, performance metrics, and reporting.

---

## 🔷 Learning Objectives

By the end of this section, you’ll be able to:

* Use `groupby()` to organize data by one or more categories
* Apply common aggregation functions like `sum()`, `mean()`, `count()`, etc.
* Perform multiple aggregations at once
* Use custom aggregation functions
* Handle grouped results for further analysis and visualization

---

## 📂 Subsections Overview

### **5.1 Basic GroupBy Operations**

Learn how to:

* Group data by a single column
* Apply basic aggregations like `sum`, `mean`, `count`, `min`, `max`
* Understand the difference between `groupby().agg()` and direct operations
* Reset index after grouping



### **5.2 Multiple Aggregations**

Learn how to:

* Apply multiple aggregation functions to the same column
* Aggregate different columns using different functions
* Rename output columns for clarity



### **5.3 Grouping by Multiple Columns**

Learn how to:

* Group by more than one column
* Create hierarchical (MultiIndex) results
* Use `reset_index()` to flatten grouped results
* Compare nested groups



### **5.4 Custom Aggregation Functions**

Learn how to:

* Define and apply your own aggregation functions
* Use lambda functions with `.agg()`
* Combine built-in and custom functions together


### **5.5 Advanced GroupBy Techniques**

Learn how to:

* Use `transform()` to return grouped results back to original DataFrame shape
* Use `filter()` to remove groups based on conditions
* Use `.apply()` for complex group-wise logic
* Compare `agg()`, `transform()`, and `apply()`


---

## 📌 Why GroupBy Matters

GroupBy is the backbone of:

* Performance reporting
* Operational analysis
* KPI dashboards
* Temporal and spatial aggregation
* Machine-learning feature engineering

---

