# 📅 Section 4: Date & Time Operations

Working with dates and times is a critical part of data analysis, especially for time-series, logs, and transportation datasets.
In this section, you will learn how to convert, manipulate, filter, and analyze time-based data using Pandas.

---

## 🔹 Section Objective

By the end of this section, you will be able to:

✅ Convert non-datetime columns into proper datetime objects

✅ Extract useful components (year, month, hour…)

✅ Filter data using time ranges

✅ Compute time differences and durations

✅ Resample data into different time frequencies

---

## 📚 Subsections Covered

### **4.1 Converting to Datetime**

Learn how to:

* Convert strings into datetime using `pd.to_datetime()`
* Handle invalid and missing values during conversion
* Convert timestamps stored as integers or floats
* Parse different date formats

---

### **4.2 Extracting Time Components**

Learn how to extract useful features from datetime columns:

* Year, Month, Day
* Hour, Minute, Second
* Day of week, Weekday name
* Week number and Quarter

---

### **4.3 Filtering by Time Ranges**

You'll learn how to:

* Filter rows between two dates
* Filter based on specific years, months, or days
* Filter by time of day (e.g., rush hours)
* Use `.between()` for date ranges

---

### **4.4 Time Differences & Durations**

Covers time calculations such as:

* Difference between two datetime columns
* Converting to time deltas using `pd.to_timedelta()`
* Calculating trip durations, delays, or intervals
* Extracting time difference in seconds, minutes, and hours

---

### **4.5 Resampling Time-Series Data**

You’ll learn how to:

* Resample time data by hour, day, week, or month
* Use aggregation functions after resampling
* Handle missing time periods (gaps)
* Compare original vs resampled frequency data

---

## 🧠 Real-World Applications

This section is especially useful for:

✅ Transit arrival/departure analysis

✅ Delay and headway calculations

✅ Daily/weekly performance tracking

✅ Monthly trend analysis

✅ Event log monitoring

