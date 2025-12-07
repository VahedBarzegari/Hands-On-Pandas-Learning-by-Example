# 📘 **8️⃣ Window & Rolling Functions**

Window functions are extremely useful when analyzing **time-series** or **sequential data**.
They allow you to calculate statistics — such as moving averages, rolling sums, cumulative totals, and ranks — over a defined window or expanding range of rows.

In this section, you’ll learn how to use pandas’ **rolling**, **expanding**, and **ranking** capabilities to uncover trends, smooth data, and perform time-dependent analysis.

---

## 🟦 **What You Will Learn in This Section**

---

### **8.1 Rolling Windows (Moving Statistics)**

You will learn how to:

* Apply rolling mean, median, and custom functions
* Define window sizes using number of rows or time intervals
* Use options like `min_periods` and `center`
* Apply multiple aggregations with `.agg()`

---

### **8.2 Expanding Windows (Cumulative Analysis)**

You will learn how to:

* Use expanding windows to include **all prior rows** in calculations
* Compute cumulative averages and trends
* Combine rolling and expanding functions for dynamic metrics

---

### **8.3 Ranking & Cumulative Functions**

You will learn how to:

* Apply ranking methods (`rank`, `dense`, `min`, etc.)
* Compute **cumulative sum**, **cumulative mean**, and **cumulative product**
* Compare group-based vs overall cumulative calculations

---

### **8.4 Applying Custom Functions with Rolling/Expanding**

You will learn how to:

* Apply custom functions using `.apply()`
* Create z-score or volatility calculations
* Use window functions in real-world time-series problems (e.g., ridership, demand smoothing, temperature trend detection)

---

## 🟦 **What You’ll Be Able to Do After This Section**

✔ Smooth noisy data with rolling averages
✔ Analyze cumulative totals and long-term growth
✔ Rank and compare rows efficiently
✔ Build custom analytics pipelines for time-series datasets
✔ Apply rolling/expanding functions to grouped data

