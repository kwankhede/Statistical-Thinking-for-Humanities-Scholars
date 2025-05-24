# 📋 Chapter 2: Data Collection, Sampling, and Thinking in Uncertainty

Welcome to **Chapter 2** of the *Statistical Thinking for Humanities Scholars* course!  
In this chapter, we explore how to **collect data properly**, understand **samples and populations**, avoid **bias**, and start thinking about **uncertainty and probability**.

<br>

## 🧪 Section 1: Data Collection and Sampling

### 🧠 Key Ideas

- **Population**: The entire group you want to study (e.g., all farmers in Wardha).
- **Sample**: A smaller group selected from the population (e.g., 100 farmers).
- **Goal**: Use the sample to say something meaningful about the population.
- 

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

Here's your **revised and enriched version** of the 📐 *Measures of Center and Spread* section — with **nothing removed**, all your original content intact, and now better formatted, more structured, and even clearer for student understanding:

---

## 📐 Measures of Center and Spread

In this section, we focus on how to **summarize data numerically** using measures of **central tendency** and **spread**, and how to be cautious of **outliers** and **misleading graphs**.

---

### 🧠 Measures of Center

These describe a “typical” or “central” value in a dataset:

* **Mean**: The arithmetic average

  $$
  \text{Mean} = \frac{\text{Sum of all values}}{\text{Number of values}}
  $$

* **Median**: The middle value when data is sorted

* **Mode**: The most frequently occurring value

> 📌 *Local Example:* In a group of farmers, if most own 2 acres, a few own 20+ acres, the **mean** might be high, but **median** shows the typical farmer.

#### ✅ Detailed Examples

* **Mean Example:**
  Land sizes: 2, 2, 3, 2, 30

  $$
  \text{Mean} = \frac{2+2+3+2+30}{5} = \frac{39}{5} = 7.8
  $$

* **Median Example:**
  Sorted values: 2, 2, 2, 3, 30

  $$
  \text{Median} = 2
  $$

* **Mode Example:**
  Values: 2, 2, 3, 3, 3, 4

  $$
  \text{Mode} = 3
  $$

---

### 🚨 Outliers and Their Effects

An **outlier** is a data point that is far removed from others.

* Outliers can **inflate or deflate the mean**
* Outliers **rarely affect the median**
* Can **mislead conclusions**, especially in small datasets

> **Example:** Land sizes in a village:
> 2, 2, 3, 2, 30 acres
>
> * **Mean** = 7.8 (skewed by the outlier)
> * **Median** = 2 (more reliable for typical case)

---

### 📊 Measures of Spread

These tell us how **varied or consistent** the values in a dataset are.

#### ✅ 1. **Range**

$$
\text{Range} = \text{Max} - \text{Min}
$$

**Example:**
Marks: 35, 40, 45, 60, 85

$$
\text{Range} = 85 - 35 = 50
$$

---

#### ✅ 2. **Interquartile Range (IQR)**

$$
\text{IQR} = Q_3 - Q_1
$$

* **Q1** = 25th percentile
* **Q3** = 75th percentile
  IQR shows the range of the **middle 50%** of the data and **reduces the influence of outliers**.

> Example: Marks of 20 students — IQR helps detect how consistent the middle students are.

---

#### ✅ 3. **Standard Deviation (SD)**

$$
\text{SD} = \sqrt{\frac{1}{n - 1} \sum_{i=1}^{n} (x_i - \bar{x})^2}
$$

* **Low SD** = values close to mean → more consistent
* **High SD** = values spread out → more variability

> 📌 *Wardha Example:*
> Daily temperatures across 7 days:
>
> * If SD is low: temperature is stable
> * If SD is high: weather is fluctuating

---

### 🚫 Misleading Graphs and Visual Tricks

Some graphs are designed to **confuse** or **manipulate** viewers.

| Trick                    | Why It’s Misleading           |
| ------------------------ | ----------------------------- |
| **Truncated y-axis**     | Exaggerates small differences |
| **3D/tilted pie charts** | Distorts proportions          |
| **Cherry-picking data**  | Hides or exaggerates trends   |

> 📌 *Example:* A sugar company shows only 2023–2024 prices to **hide a 5-year price rise** trend.

---

### 🧾 Summary Table: Measures of Center and Spread

| Measure                | What It Tells Us                | When It’s Most Useful                           |
| ---------------------- | ------------------------------- | ----------------------------------------------- |
| **Mean**               | Average of all data values      | Data is symmetric, no extreme values            |
| **Median**             | Middle value in sorted data     | Skewed data or when outliers are present        |
| **Mode**               | Most frequently occurring value | Categorical or modal analysis (e.g., vote mode) |
| **Range**              | Total spread in data            | Quick check for variation                       |
| **IQR**                | Spread of middle 50% of data    | More reliable than range when outliers exist    |
| **Standard Deviation** | Average distance from the mean  | Need for precision and detecting consistency    |

---
