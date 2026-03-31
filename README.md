# 📊 Proof of Sampling Accuracy

### Population vs Sample-Based Decision Making using Census Data

---

## 📌 About this Project

In this project, I explored how well sample data can represent real population data.

In real-world situations, working with full population data is often difficult because of its size. So instead, we use samples. But an important question is:

👉 *How accurate are these samples?*

To answer this, I worked with India Census 2011 data and applied different sampling techniques to compare sample results with actual population values.

---

## 🎯 What I Wanted to Achieve

* Understand how sampling works in practice
* Compare sample results with real population data
* Check accuracy using statistical methods
* Build visual insights to make the results easy to understand

---

## 🧠 What I Did

### 🔹 Data Preparation

* Cleaned the dataset (handled missing values and duplicates)
* Standardized column names
* Created new features like:

  * Literacy Rate
  * Sex Ratio

---

### 🔹 Sampling Techniques Used

I applied three types of sampling:

* **Simple Random Sampling** → randomly selected data
* **Systematic Sampling** → selected data at fixed intervals
* **Stratified Sampling** → took samples from each state proportionally

---

### 🔹 Analysis

* Compared sample means with population mean
* Calculated error percentage
* Checked how close each method is to real data

---

### 🔹 Statistical Validation

To make the results more reliable, I used:

* **Confidence Interval (95%)**
  → to check if population values fall within sample range

* **Central Limit Theorem (CLT)**
  → generated 1000 samples (size = 100)
  → showed that sample means follow normal distribution

---

## 📊 What the Visualizations Show

* Population distribution across states
* Literacy trends and distribution
* Relationship between literacy and workforce
* Gender balance using sex ratio
* Comparison of sampling techniques

---

## 📈 Key Observations

* Simple random sampling gave results closest to population
* All sampling methods performed reasonably well
* Sample means were very close to population mean
* CLT was clearly observed through normal distribution of sample means

---

## 🛠 Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 💡 What I Learned

This project helped me understand that:

* Sampling is very powerful when done correctly
* You don’t always need full data to make decisions
* Statistical validation is important to trust results

---

## 🚀 Final Thought

This project shows that with proper techniques, sample data can give insights very close to actual population data, which is very useful in real-world decision making.

---

## 👨‍💻 Author

Navin Bohara

---
