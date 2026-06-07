📊 Statistical Distribution Analysis on Transaction Dataset

---

📌 Project Overview

This project focuses on performing Statistical Distribution Analysis on a transaction dataset using Python and Data Analysis techniques.

The main objective is to understand transaction behavior, identify patterns, analyze probabilities, and apply different statistical distributions to real-world transaction data.

This project includes both theoretical concepts and practical implementation using Python.

---

🎯 Objectives
Understand different types of statistical distributions
Perform probability-based analysis
Analyze transaction behavior
Visualize data distributions
Detect outliers and unusual transaction patterns
Apply transformations for better statistical interpretation

---

🗂 Dataset Information

Dataset Columns:

- transaction_id
- customer_id
- transaction_amount
- transaction_date
- transaction_count
- region
- transaction_status

---

# 📚 Part A — Exploring Statistical Distributions

Data tells a story — and statistical distributions help us understand that story.

In this project, different statistical concepts were explored to analyze transaction patterns, understand probability behavior, and discover meaningful insights hidden inside the dataset.

---

## 📌 1. Statistical Distribution

Learned how data values are spread and how distributions help represent real-world behavior.

**Goal:** Understand transaction patterns and variability.

---

## 📈 2. Q-Q Plot

Compared actual transaction data with theoretical normal distribution.

**Goal:**

* Check whether data follows normal distribution
* Detect unusual values (outliers)

**Insight:**
- Straight line → Normal Data
- Curved pattern → Non-Normal Data

---

## 🔢 3. Discrete vs Continuous Distribution

Explored the difference between count-based and measurement-based data.

Examples:

* `transaction_count` → Discrete
* `transaction_amount` → Continuous

**Goal:** Choose correct statistical techniques.

---

## 🎯 4. Bernoulli Distribution

Analyzed situations with only two outcomes.

Examples:

* Success
* Failure

**Goal:** Measure transaction success probability.

---

## 📊 5. Binomial Distribution

Extended Bernoulli analysis to multiple transactions.

**Goal:** Predict successful outcomes across repeated attempts.

---

## 📉 6. Log Normal Distribution

Studied transaction amounts where most values remain small while a few become very large.

**Goal:** Understand customer spending behavior.

---

## ⚡ 7. Power Law Distribution

Explored uneven patterns where a small number of transactions contribute significantly.

**Goal:** Identify high-impact transaction behavior.

---

## 🔄 8. Box-Cox Transformation

Applied transformation techniques to improve distribution quality.

**Goal:** Reduce skewness and make data easier to analyze.

---

## ⏱ 9. Poisson Distribution

Modeled transaction occurrence over a fixed period.

**Goal:** Estimate event frequency.

---

## 📍 10. Z-Score Probability

Measured how far transaction values are from the average.

**Goal:** Detect unusual transactions and calculate probability beyond ₹5000.

---

## 📚 11. PDF vs CDF

Compared individual probability with cumulative probability.

**Goal:** Understand how transaction probabilities build over time.

---

## 🏆 Learning Outcome

Through these statistical techniques, the project transformed raw transaction data into meaningful insights and improved understanding of data behavior, probability, and decision-making.



# 🧪 Part B — Statistical Analysis Using Python

This section focuses on implementing statistical concepts using Python to analyze the transaction dataset. Different probability distributions and statistical techniques were applied to understand transaction behavior, identify patterns, and generate meaningful insights.

---

## 1. Data Loading and Preprocessing

The dataset was imported into Python using Pandas.

Data preprocessing steps included:

* Loading dataset into DataFrame
* Checking missing values
* Converting transaction dates into datetime format
* Removing duplicate records
* Exploring dataset structure and summary statistics

Purpose:

* Prepare clean and structured data before analysis.

---

## 2. Bernoulli Distribution

Bernoulli Distribution was applied to analyze transaction outcomes.

Each transaction was categorized into:

* Success → 1
* Failure → 0

Purpose:

* Measure probability of successful transactions.
* Understand transaction success behavior.

Output:

* Success probability calculation
* Distribution visualization

---

## 3. Binomial Distribution

Binomial Distribution was used to analyze the probability of successful transactions across multiple attempts.

Analysis included:

* Number of transaction trials
* Probability of success
* Probability distribution across multiple transactions

Purpose:

* Predict successful transaction occurrence.

Output:

* Probability graph
* Success trend analysis

---

## 4. Poisson Distribution

Poisson Distribution was used to model transaction occurrence over time.

Analysis included:

* Average transaction frequency
* Event occurrence behavior

Purpose:

* Estimate number of transactions within a time interval.

Output:

* Transaction probability distribution

---

## 5. Log Normal Distribution

Log Normal Distribution was applied to analyze transaction amounts.

Purpose:

* Determine whether transaction values are positively skewed.
* Understand spending patterns.

Output:

* Distribution fitting
* Histogram visualization

---

## 6. Power Law Distribution

Power Law Distribution was used to study unequal transaction behavior.

Purpose:

* Identify whether small transaction values occur frequently and large values occur rarely.

Output:

* Power Law distribution curve

---

## 7. Q-Q Plot Analysis

Q-Q Plot was generated to compare actual transaction data with a normal distribution.

Purpose:

* Check data normality
* Detect outliers
* Evaluate distribution shape

Interpretation:

* Straight line → Normal Distribution
* Curved pattern → Non-normal Distribution

Output:

* Q-Q Plot visualization

---

## 8. Box-Cox Transformation

Box-Cox Transformation was applied to normalize skewed transaction values.

Purpose:

* Reduce skewness
* Improve distribution quality
* Prepare data for analysis

Output:

* Transformed distribution

---

## 9. Z-Score Probability Analysis

Z-score analysis was performed on transaction amounts.

Purpose:

* Measure distance from average transaction values
* Detect unusual transactions

Additionally:

Probability of transactions exceeding ₹5000 was calculated.

Output:

* Z-score values
* Probability estimation

---

## 10. PDF and CDF Analysis

PDF and CDF were calculated to understand transaction probability behavior.

### PDF

Shows probability distribution across transaction values.

### CDF

Shows cumulative probability up to a specific value.

Purpose:

* Understand distribution pattern
* Analyze cumulative probabilities

Output:

* PDF Curve
* CDF Curve

---

## 📊 Final Outcome

After applying all statistical methods:

✔ Transaction behavior was analyzed
✔ Probability patterns were identified
✔ Outliers were detected
✔ Distribution comparison was performed
✔ Statistical insights were generated

This analysis provided a better understanding of transaction trends and customer behavior.

---

📊 This project transformed raw transaction data into meaningful insights by applying statistical distributions, probability analysis, and visualization techniques.

🚀 Using Python and statistical methods, the analysis uncovered transaction patterns, detected unusual behavior, and supported smarter data-driven decision making.

----

## 👨‍🎓 Submitted By
Shivani marakana 