# 📋 Chapter 2: Data Collection, Sampling, and Thinking in Uncertainty

Welcome to **Chapter 2** of the *Statistical Thinking for Humanities Scholars* course!  
In this chapter, we explore how to **collect data properly**, understand **samples and populations**, avoid **bias**, and start thinking about **uncertainty and probability**.

<br>

## 🧪 Section 1: Data Collection and Sampling

### 🧠 Key Ideas

- **Population**: The entire group you want to study (e.g., all farmers in Wardha).
- **Sample**: A smaller group selected from the population (e.g., 100 farmers).
- **Goal**: Use the sample to say something meaningful about the population.

<br>

### 📦 Types of Sampling Methods

| Sampling Method        | Description                                             | Local Example                              |
|------------------------|---------------------------------------------------------|--------------------------------------------|
| **Simple Random**      | Every member has an equal chance                        | Randomly pick 50 students from 10th class. |
| **Stratified Sampling**| Divide into groups, then sample from each group         | Select farmers by taluka (Wardha, Hinganghat, etc.) |
| **Systematic**         | Every 10th name on a school attendance list             | Sample every 5th voter on a list           |
| **Convenience Sampling**| Easy-to-access people (⚠️ often biased)               | Asking only students nearby or online      |

<br>

### 🚨 What Is Bias?

**Bias** happens when your sample is not representative of the population.

#### 🔍 Examples of Bias in Vidarbha:
- Asking only male farmers, but not female farm laborers.
- Surveying students only from English-medium schools.
- Ignoring remote tribal villages in Melghat in health data.


<br>

## Frequency Tables and Types of Graphs

### 📊 Overview

This module introduces how to organize data using **frequency tables** and how to represent that data visually using **bar graphs**, **pie charts**, and **histograms**.

<br>

## 📋 1. Frequency Tables

A **frequency table** summarizes data by showing the number of times each item occurs.

### 🔹 Example:

| Data (Number of Books Read) | Frequency |
|-----------------------------|-----------|
| 0–2                         | 5         |
| 3–5                         | 12        |
| 6–8                         | 7         |
| 9–11                        | 3         |

**Key terms:**
- **Class intervals**: Grouped ranges (e.g., 0–2, 3–5)
- **Frequency**: How often each class occurs

<br>

## 📊 2. Bar Graphs

**Bar graphs** use rectangular bars to represent data values. The length/height of the bar shows the frequency.

### 🔹 Features:
- Categories on the x-axis
- Frequencies on the y-axis
- Bars **do not touch**

### 🔹 Example:

![Insert bar chart image here](https://i.pinimg.com/564x/30/bd/4b/30bd4bd9e3af57b6d3982b802bf33c95.jpg)
<br>


## 🥧 3. Pie Charts

**Pie charts** display data as slices of a circle, with each slice representing a proportion of the whole.

### 🔹 Features:
- Best for **categorical data**
- Each slice represents a percentage
<br>


![Insert pie chart image here](https://www.blog.matchub.net/wp-content/uploads/2019/07/export-India.png)

<br>

## 📉 4. Histograms

**Histograms** look like bar graphs but are used for **continuous data**.

### 🔹 Features:
- Bars **touch each other**
- Represents **intervals** on x-axis
- Useful for **grouped frequency data**
<br>



![Insert histogram image here](https://www.w3schools.com/statistics/img_histogram.svg)

<br>

## ✅ Summary

| Type of Graph | Best For              | Notes                      |
|---------------|-----------------------|----------------------------|
| Bar Graph     | Categorical data      | Bars don't touch           |
| Pie Chart     | Categorical data      | Good for part-whole view   |
| Histogram     | Continuous/grouped data | Bars touch; shows intervals |

<br>

## 📚 Further Reading & Tools

- [Khan Academy – Bar graphs and histograms](https://www.khanacademy.org/math/statistics-probability/displaying-describing-data)
- [Desmos Graphing Calculator](https://www.desmos.com/)
- [ChartGo Graph Maker](https://www.chartgo.com/)



<br>
<br>
<br>

## 📐 Measures of Center and Spread

In this section, we focus on how to **summarize data numerically** using measures of central tendency and spread, and how to watch out for **outliers** and **misleading graphs**.

### 🧠 Measures of Center

These describe a “typical” or “central” value in a dataset:

- **Mean**: The arithmetic average  
  \[
  \text{Mean} = \frac{\text{Sum of all values}}{\text{Number of values}}
  \]
- **Median**: The middle value when data is sorted
- **Mode**: The most frequently occurring value

> 📌 *Local Example:* In a group of farmers, if most own 2 acres, a few own 20+ acres, the **mean** might be high, but **median** shows the typical farmer.

---

### 🚨 Outliers and Their Effects

An **outlier** is a data point that is far from others.

- Outliers **increase the mean** but may not affect the **median**.
- They can **mislead conclusions**, especially in small datasets.

> **Example:** Farmer land sizes: 2, 2, 3, 2, 30 acres  
> - Mean = 7.8 (seems high)  
> - Median = 2 (more accurate reflection of most farmers)

---

### 📊 Measures of Spread

These tell us how much variation or "spread" exists in the data.

- **Range**: Difference between max and min values  
- **IQR (Interquartile Range)**: Middle 50% spread (Q3 - Q1)  
- **Standard Deviation**: Average distance from the mean (see formula below)

> 📌 *Wardha Example:*  
> Measuring daily temperature across 7 days – small SD means consistent weather; large SD means fluctuation.

---

### 🚫 Misleading Graphs and Visual Tricks

Not all graphs are trustworthy! Be alert to:

- **Axes manipulation**: Starting y-axis at a high number to exaggerate small differences
- **Pie chart distortion**: Using 3D or tilt to mislead proportion
- **Cherry-picking data**: Showing only certain years or values

> **Example:** A sugar company graph only shows 2023–2024 prices to hide long-term increase.

---



# 📘 Core Statistical Concepts

This document introduces three important concepts in introductory statistics:

- Frequentist View of Probability  
- Estimators and Bias  
- Sample Variance

---

## 🎲 Frequentist View of Probability

The **Frequentist** interpretation of probability defines probability as the **long-run relative frequency** of an event occurring, based on repeated trials.

### 🔹 Key Ideas:
- Probability is the limit of relative frequency as the number of trials goes to infinity.
- It does **not** involve personal belief or prior knowledge.
- Example: If you flip a fair coin many times, the proportion of heads approaches 0.5.

> **Example:**  
> If you roll a die 600 times and the number 3 appears 100 times,  
> the frequentist probability of rolling a 3 is:  
>  
> \[
> P(3) = \frac{100}{600} = 0.1667
> \]

---

## 📐 Estimators and Bias

An **estimator** is a rule or formula used to estimate an unknown population parameter from a sample.

### 🔹 Example:
- Sample mean \(\bar{x}\) estimates population mean \(\mu\).
- Sample proportion \(\hat{p}\) estimates population proportion \(p\).

### 🧭 Bias of an Estimator:
- **Bias** is the **difference between the expected value of the estimator and the true population parameter**.

\[
\text{Bias}(\hat{\theta}) = \mathbb{E}[\hat{\theta}] - \theta
\]

- An estimator is **unbiased** if:  
  \[
  \mathbb{E}[\hat{\theta}] = \theta
  \]

> **Example:**  
> The sample mean is an **unbiased** estimator of the population mean.



## 📊 Sample Variance

The **sample variance** measures the spread of data points around the sample mean.

### 🔹 Formula:

\[
s^2 = \frac{1}{n - 1} \sum_{i=1}^{n} (x_i - \bar{x})^2
\]

### 🔍 Why divide by \(n - 1\)?
- This correction is called **Bessel's correction**.
- It makes the sample variance an **unbiased estimator** of the population variance.

### 🔹 Example:

Data: 3, 7, 7, 19  
Sample Mean: \(\bar{x} = 9\)

\[
s^2 = \frac{(3 - 9)^2 + (7 - 9)^2 + (7 - 9)^2 + (19 - 9)^2}{4 - 1}
= \frac{36 + 4 + 4 + 100}{3} = \frac{144}{3} = 48
\]



## ✅ Summary Table

| Concept                  | Key Idea                                                                 |
|--------------------------|--------------------------------------------------------------------------|
| Frequentist Probability  | Probability as long-run frequency                                        |
| Estimator                | A rule/formula to estimate a population parameter                        |
| Bias                     | Difference between expected estimator value and true parameter           |
| Sample Variance          | Average squared deviation from mean (with correction for unbiasedness)  |


## 🎲 Section 2: Estimation and Thinking in Uncertainty

### 🎯 Key Terms

- **Estimator**: A method to guess a number (e.g., average height).
- **Bias (statistical)**: When your guess consistently misses in one direction.
- **Variance**: How spread out your data is.
- **Standard Deviation**: Average distance from the mean.

---

### 🧪 Real-Life Examples

| Concept           | Local Example                                                    |
|------------------|------------------------------------------------------------------|
| Estimation        | Estimate average rainfall in Buldhana from past 5 years          |
| Variance          | Variation in marks of 10th students in Amravati schools          |
| Standard Deviation| Compare weight of 20 cabbages grown in a Wardha farm             |

---

### 🧠 Frequentist View of Probability

> Probability is defined as the **long-run frequency** of an outcome.

#### ⚖️ Example:
Flip a coin 100 times:
- Get 47 heads, 53 tails → Probability ≈ 0.47 and 0.53

More flips → closer to 0.5

---

### 🧪 Classroom Activity: Coin Toss Simulation

1. Flip a coin 10, 50, and 100 times.
2. Record number of heads and tails.
3. Plot the results on a bar chart.
4. Discuss:
   - How stable is the outcome?
   - Does more data give a clearer picture?
   - 

## 🎮 Try It Yourself: Probability Simulation Web App

Want to visualize coin flips, dice rolls, or probability distributions?

👉 **Open this interactive app:**  
🔗 [Probability Applet – BFW Stats](https://digitalfirst.bfwpub.com/stats_applet/stats_applet_10_prob.html)

![Preview of the Applet](https://github.com/kwankhede/Statistical-Thinking-for-Humanities-Scholars/blob/main/media/chapter2.1.png)

### 📌 Instructions
1. Click the link above to open the app.
2. Choose a simulation (e.g., coin flips, dice rolls).
3. Run it with different sample sizes (10, 50, 100).
4. Observe the shape of the distribution and how it stabilizes.
5. Discuss what the outcome means for real-life events like weather prediction or exam results.

> This is a great way to explore **Frequentist probability** and understand **random variation** through simulations!

---

## 📉 Section 3: Sample Mean and Standard Deviation

### 🧠 Definitions

- **Mean (average)**: Add all values, divide by number.
- **Sample Variance**: Average of squared deviations from the mean.
- **Standard Deviation**: Square root of variance.

### 📊 Example:
Marks of 5 students: 45, 55, 60, 40, 50  
- Mean = 50  
- Variance = average of (x - 50)²  
- SD = √variance

---

## 📈 Section 4: Local Applications

### 🌧️ Rainfall in Vidarbha

- Collect rainfall data from 5 villages in Chandrapur.
- Calculate average and SD.
- Compare year to year: Is rainfall stable?

### 🧑🏽‍🌾 Agricultural Yields

- Estimate average soybean yield in Akola per acre.
- Sample 10 farms.
- Calculate mean and discuss variation.

---

## 💬 Think & Reflect

- Why can’t we study every person in Wardha? Why do we sample?
- How can bad sampling lead to bad decisions?
- What does it mean if your SD is high?

---

## 📚 Summary Table

| Term                  | Meaning                                                    |
|------------------------|------------------------------------------------------------|
| **Population**         | Entire group (e.g., all households in a village)           |
| **Sample**             | A subset used for analysis                                 |
| **Sampling Bias**      | Sample doesn't reflect the full population                 |
| **Estimator**          | Rule to estimate a population value                        |
| **Mean**               | Average                                                    |
| **Variance**           | Measure of spread                                          |
| **Standard Deviation** | Typical distance from the mean                             |
| **Frequentist Probability** | Chance as a long-run frequency                      |

---





## 🚀 **Next Chapter: Probability Distributions & Inference!**  
- Learn to model randomness and draw conclusions from data.  

