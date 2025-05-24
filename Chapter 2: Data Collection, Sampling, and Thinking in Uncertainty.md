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

In this section, we focus on how to **summarize data numerically** using measures of **central tendency** and **spread**, and how to be cautious of **outliers** and **misleading graphs**.


### 🧠 Measures of Center

Measures of center help us identify a “typical” or “representative” value in a dataset — something that gives us a sense of what is *usual*.

#### 🔹 1. **Mean** — The Arithmetic Average

This is the most common measure. It adds up all values and divides by how many there are:

$$
\text{Mean} = \frac{\text{Sum of all values}}{\text{Number of values}}
$$

**Local Example:**
Farmer land sizes in acres: 2, 2, 3, 2, 30

$$
\text{Mean} = \frac{2 + 2 + 3 + 2 + 30}{5} = \frac{39}{5} = 7.8 \text{ acres}
$$

➡️ This is misleading because the mean is pulled up by a single large value (30 acres).

<br>

#### 🔹 2. **Median** — The Middle Value

The **median** is the central value when data is sorted. It's more **robust to outliers** than the mean.

**Example:**
Sorted land sizes: 2, 2, 2, 3, 30

$$
\text{Median} = 2
$$

➡️ Median reflects the *typical* landholding better than the mean here.

<br>

#### 🔹 3. **Mode** — Most Frequent Value

The **mode** is the value that appears **most often** in the data.

**Example:**
Cattle owned by villagers: 2, 2, 3, 3, 3, 4

$$
\text{Mode} = 3
$$

➡️ Useful in situations like identifying most common crop type, favorite festival food, etc.

<br>

### 🚨 Outliers and Their Effects

An **outlier** is a value that’s **very different** from the others. It can distort analysis.

* Outliers **inflate/deflate the mean**
* Outliers **do not impact the median or mode as much**
* May result from errors, rare events, or genuine extremes

**Example:**
Land sizes: 2, 2, 3, 2, 30

* **Mean** = 7.8
* **Median** = 2
* **Outlier** = 30

📌 *Conclusion:* Use **median** or **IQR** instead of mean when outliers are present.

<br>

### 📊 Measures of Spread

While center tells us what is typical, **spread** tells us how **consistent or varied** the data is.

<br>

#### ✅ 1. **Range**

$$
\text{Range} = \text{Max} - \text{Min}
$$

**Example:**
Test scores: 35, 40, 45, 60, 85

$$
\text{Range} = 85 - 35 = 50
$$

➡️ Easy to calculate, but can be affected by outliers.

<br>

#### ✅ 2. **Interquartile Range (IQR)**

$$
\text{IQR} = Q_3 - Q_1
$$

* **Q1 (25th percentile)**: Lower quartile
* **Q3 (75th percentile)**: Upper quartile

IQR represents the **middle 50%** of the data.

> **Example:** Marks of 20 students.
> If Q1 = 42 and Q3 = 66, then:
>
> $$
> \text{IQR} = 66 - 42 = 24
> $$
>
> This shows the central tendency without getting distorted by extremes.

<br>

Here's the **improved section** with your requested addition on **Standard Deviation (SD)** and its **formula**, along with the **explanation of Sample Variance** — formatted clearly and aligned with your Chapter 2 content.

---

### ✅ 3. **Standard Deviation (SD) and Sample Variance**

These are **precise numerical measures** of how spread out the data is.

<br>

#### 📏 **Sample Variance**

Sample Variance measures the **average of the squared differences** from the mean. It’s used as a step to calculate standard deviation.

$$
\text{Variance (}s^2\text{)} = \frac{1}{n - 1} \sum_{i=1}^{n} (x_i - \bar{x})^2
$$

Where:

* $x_i$ = each data point
* $\bar{x}$ = sample mean
* $n$ = number of observations

<br>

#### 📊 **Standard Deviation (SD)**

This is the **square root** of the sample variance. It gives us a value **in the same unit as the original data**, making it easier to interpret.

$$
\text{SD} = \sqrt{ \frac{1}{n - 1} \sum_{i=1}^{n} (x_i - \bar{x})^2 }
$$

* **Low SD** → Values are close to the mean
* **High SD** → Values are spread far from the mean

<br>

#### 📌 *Wardha Example: Daily Temperature Over 7 Days*

| Day       | Temp (°C) |
| --------- | --------- |
| Monday    | 32        |
| Tuesday   | 33        |
| Wednesday | 34        |
| Thursday  | 33        |
| Friday    | 32        |
| Saturday  | 33        |
| Sunday    | 34        |

If SD = **2°C** → Temperatures are **stable and consistent**

If SD = **8°C** → Temperatures vary **widely** (e.g., **hot days, cool nights**)

<br>

> **Why it matters:**
>
> * In **climate studies**, a high SD may signal erratic weather patterns.
> * In **education**, high SD in test scores shows large learning differences among students.



<br>

### 🚫 Misleading Graphs and Visual Tricks

Some charts are **manipulated** to mislead the audience.

| Trick                    | Why It’s Misleading         |
| ------------------------ | --------------------------- |
| **Truncated y-axis**     | Small differences look big  |
| **3D/tilted pie charts** | Misrepresents proportions   |
| **Cherry-picked data**   | Omits important information |

> 📌 *Example:* A sugar company's graph only shows prices for 2023–2024, **hiding** the fact that prices have been steadily increasing since 2020.

---

### 🧾 Summary Table: Measures of Center and Spread

| Measure                | What It Tells Us             | Best Used When…                                |
| ---------------------- | ---------------------------- | ---------------------------------------------- |
| **Mean**               | Average of values            | Data is symmetric and clean (no outliers)      |
| **Median**             | Middle value                 | Data is skewed or has outliers                 |
| **Mode**               | Most frequent value          | Categorical data or frequency-focused analysis |
| **Range**              | Simple spread                | Quick comparison of extremes                   |
| **IQR**                | Spread of middle 50%         | Reliable when ignoring outliers                |
| **Standard Deviation** | Precise spread from the mean | When detail and accuracy are needed            |


<br> 

### 🎲 Coin Toss and Relative Frequency

Imagine flipping a fair coin:

* Head or Tail → each has a 50% chance in theory
* But in a short experiment (e.g., 10 flips), you may get 7 heads and 3 tails

| Number of Tosses | Heads Count | Frequency of Heads |
| ---------------- | ----------- | ------------------ |
| 10               | 7           | 0.7                |
| 50               | 27          | 0.54               |
| 100              | 49          | 0.49               |
| 1000             | 503         | 0.503              |

As the number of tosses increases, the relative frequency approaches the **expected value** (0.5 for heads).

<br> 

## 📜 Law of Large Numbers (LLN)

The **Law of Large Numbers** states:

> As the number of trials increases, the **observed average** (relative frequency) will **converge** to the **expected average**.

<br> 

### 📌 Why Law of Large Numbers (LLN) Matters

* **Small samples** may be misleading.
* **Larger samples** give more stable, reliable results.
* It **justifies sampling** in surveys, elections, crop studies, etc.

<br> 

### 🧪 Coin Toss LLN Example

Flipping a coin 10 times → Heads = 7 (70%)
Not close to the true probability (50%)

Flipping it 1000 times → Heads ≈ 500 (50%)
Much closer!

➡️ The larger the sample, the more **trustworthy** the estimate.

<br> 

## 🎮 Probability Simulation: Try It Yourself!

Want to simulate coin flips, dice rolls, and more?

👉 **Open this web app:**
🔗 [BFW Probability Simulation Applet](https://digitalfirst.bfwpub.com/stats_applet/stats_applet_10_prob.html)

![Simulation Preview](https://github.com/kwankhede/Statistical-Thinking-for-Humanities-Scholars/blob/main/media/chapter2.1.png)

<br> 

### 🔍 How to Use It

1. Go to the link above
2. Select a simulation (e.g., coin toss, dice roll, sampling)
3. Try different numbers of trials (e.g., 10, 50, 100, 1000)
4. Observe how results change and **stabilize** over time
5. Discuss what this means for **real-life predictions**

> A powerful way to explore the **Law of Large Numbers** in action!


<br> 

### 🧾 Summary Table: Measures of Center and Spread

| Measure                  | What It Tells Us              | Best Used When…                             |
| ------------------------ | ----------------------------- | ------------------------------------------- |
| **Mean**                 | Arithmetic average            | Data is symmetric and clean                 |
| **Median**               | Middle value                  | Data has outliers or is skewed              |
| **Mode**                 | Most common value             | Frequency matters (e.g., favorite festival) |
| **Range**                | Max-Min                       | Quick view of extremes                      |
| **IQR**                  | Spread of middle 50%          | More stable than range when outliers exist  |
| **Standard Deviation**   | Spread around the mean        | Detailed variability tracking               |
| **Frequency**            | Repetition of values          | Foundational for probability and summaries  |
| **Law of Large Numbers** | Big samples are more accurate | Crucial for reliable generalizations        |




