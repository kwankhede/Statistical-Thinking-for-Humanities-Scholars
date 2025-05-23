# 📊 Chapter 3.1: Probability Distributions

Welcome to **Chapter 3.1** of *Statistical Thinking for Humanities Scholars*!  
This chapter, inspired by the Nalanda Academy Workshop (17-19 May 2025) by Subodh Patil and Kapil Wankhede, introduces **probability distributions**, with a special focus on the **Normal Distribution**. Designed for humanities scholars, we use intuitive explanations, local Indian examples, and minimal mathematics (Std. X level) to explore how distributions help us understand data in fields like history, sociology, and cultural studies. Let’s dive into the world of probabilities!

---

## 🎲 Understanding Probability Distributions

A **probability distribution** describes how likely different outcomes are for a random process. Think of it as a map assigning probabilities to possible results, like the chance of rain in Mumbai or the number of voters supporting a candidate in a local election.

### 📌 Key Distributions Every Researcher Should Know

Below are four key probability distributions, with a focus on the **Normal Distribution**. Each includes a formula and a local Indian example to make them relatable:

| **Distribution**       | **When to Use**                          | **Formula (PMF/PDF)**                     | **Local Example**                          |
|-----------------------|------------------------------------------|------------------------------------------|-------------------------------------------|
| **Binomial**          | Counts successes in a fixed number of yes/no trials | `P(X=k) = C(n,k) p^k (1-p)^(n-k)` | Surveying 100 farmers in Nashik: what % adopted organic farming? |
| **Poisson**           | Counts rare events in a fixed time/space | `P(X=k) = (λ^k e^-λ)/k!` | Number of traffic accidents per week in Pune’s Shivaji Nagar |
| **Normal (Gaussian)** | Continuous data, especially averages | `f(x) = (1/σ√2π) e^[-(x-μ)²/2σ²]` | Heights of Class X students in Delhi schools |
| **Uniform**           | All outcomes equally likely | `f(x) = 1/(b-a)` for x in [a,b] | Picking a random bus departure time between 8 AM and 9 AM |

**Key Terms (Highlighted in Red at First Mention):**
- **Probability Distribution Function (PDF)**: Assigns probabilities to outcomes of a **random variable**. For discrete variables (e.g., coin flips), it’s a probability mass function (PMF). For continuous variables (e.g., heights), it’s a probability density function (Page 19 of PDF).
- **Random Variable**: A variable representing outcomes of a random process (e.g., number of heads in 10 coin flips) (Page 19).
- **Sample Variance**: Measures the spread of data in finite samples, calculated as Σ(x_i - x̄)² / (N-1) to be unbiased (Pages 11, 34).

**PDF Connection**: The document defines a PDF as assigning probabilities to each outcome of a random variable, ensuring the total probability sums to 1 (Page 22). For example, a fair coin has P(H) = P(T) = 1/2, and a fair die has P(1) = P(2) = ... = P(6) = 1/6 (Page 19).

---

## 📉 The Normal Distribution in Depth

The **Normal Distribution** (also called Gaussian) is a bell-shaped curve that describes many real-world measurements, like heights, exam scores, or crop yields. It’s especially important because averages of large samples tend to follow this distribution.

### 🌟 Why It Matters
- **Central Limit Theorem** (Page 16): The average of many independent observations (e.g., average income of 100 farmers) approaches a normal distribution as the sample size grows, regardless of the underlying data’s shape.
- **Empirical Rule**: For a normal distribution with **mean (μ)** and **standard deviation (σ)**:
  - 68% of data lies within 1σ of μ.
  - 95% within 2σ.
  - 99.7% within 3σ.
- **PDF Connection**: The document notes that outcomes of repeated trials (e.g., coin flips) tend toward a normal distribution as the number of trials increases (Page 16). For example, the average proportion of heads in 1,000 coin flips clusters around 0.5 with a standard deviation of **1/(2√N) = 0.0158** for N=1,000 (Page 30).

### 🧮 Local Calculation Example
**Scenario**: Monthly incomes of farmers in Wardha district are normally distributed with **μ = ₹15,000** and **σ = ₹3,000**.

1. **What % earn between ₹12,000 and ₹18,000?**
   - This range is μ ± 1σ (15,000 ± 3,000).
   - By the empirical rule, **68%** of farmers earn between ₹12,000 and ₹18,000.

2. **What income is at the 95th percentile?**
   - The 95th percentile corresponds to μ + 1.96σ (from standard normal tables).
   - Calculation: 15,000 + 1.96 × 3,000 = **₹20,880**.
   - So, 95% of farmers earn less than ₹20,880 per month.

### 📊 Visualizing the Normal Distribution
Below is a visualization of the normal distribution for Wardha farmer incomes, created using Chart.js:

```chartjs
{
  "type": "line",
  "data": {
    "labels": [9000, 10000, 11000, 12000, 13000, 14000, 15000, 16000, 17000, 18000, 19000, 20000, 21000],
    "datasets": [{
      "label": "Normal Distribution (μ=15000, σ=3000)",
      "data": [
        0.000035, 0.000133, 0.000399, 0.000977, 0.001946, 0.003156, 0.004162, 0.004466, 0.003905, 0.002781, 0.001611, 0.000759, 0.000291
      ],
      "borderColor": "#1E90FF",
      "backgroundColor": "rgba(30, 144, 255, 0.2)",
      "fill": true,
      "tension": 0.4
    }]
  },
  "options": {
    "scales": {
      "x": {
        "title": {
          "display": true,
          "text": "Monthly Income (₹)"
        }
      },
      "y": {
        "title": {
          "display": true,
          "text": "Probability Density"
        }
      }
    },
    "plugins": {
      "title": {
        "display": true,
        "text": "Normal Distribution of Farmer Incomes in Wardha"
      }
    }
  }
}
```

**Explanation**: This chart shows the **probability density function (PDF)** of a normal distribution with μ = ₹15,000 and σ = ₹3,000. The peak at ₹15,000 indicates the highest probability density, with the curve tapering symmetrically. The shaded area between ₹12,000 and ₹18,000 represents the 68% probability.

### 🧑🏽‍🏫 Classroom Activity: Normal Distribution Exploration
1. **Collect Data**: Measure a continuous variable, like the heights of 20 students in your local school (in cm) or daily rainfall in your city for 30 days.
2. **Calculate**: Find the sample mean (x̄) and standard deviation (s) using a calculator or free software like Jamovi.
3. **Visualize**: Plot a histogram and overlay a normal curve. Does the data resemble a bell shape? Why or why not?
4. **Discuss**: How could the normal distribution help analyze historical data, like average lifespans in ancient Indian texts or trade volumes in Mughal-era records?

**PDF Connection**: The document emphasizes that finite samples introduce **sample variance** (Page 11), calculated as Σ(x_i - x̄)² / (N-1) to be unbiased (Page 34). For coin flips, the proportion of heads fluctuates around 0.5 with a standard deviation of 1/(2√N) (Page 15), and large samples converge to a normal distribution (Page 16).

---

## 📋 Summary Cheat Sheet

| **Concept**                 | **Key Formula**                          | **Remember**                          |
|----------------------------|-----------------------------------------|--------------------------------------|
| **Normal Distribution**    | `f(x) = (1/σ√2π) e^[-(x-μ)²/2σ²]`      | 68-95-99.7 rule for data spread      |
| **Sample Variance**        | `s² = Σ(x_i - x̄)² / (N-1)`             | Use N-1 for unbiased estimator       |
| **Binomial**               | `P(X=k) = C(n,k) p^k (1-p)^(n-k)`      | Counts successes in fixed trials     |
| **Poisson**                | `P(X=k) = (λ^k e^-λ)/k!`               | Counts rare events                   |
| **Uniform**                | `f(x) = 1/(b-a)`                       | Equal probability for all outcomes   |

**PDF Notes**:
- **Frequentist View**: Probability reflects long-term frequency of outcomes (Page 5). For example, a fair coin yields heads 50% of the time over many flips (Page 6).
- **Random Variables**: Can be discrete (e.g., coin flips: {H, T}) or continuous (e.g., heights: {1.32m, 1.50m, ...}) (Page 20).
- **Moments**: The nth moment of a distribution (e.g., mean, variance) describes its properties. Variance is the 2nd moment: ⟨(x-⟨x⟩)²⟩ = ⟨x²⟩ - ⟨x⟩² (Page 27).

---

## 📚 Homework & Field Exercises

1. **Distribution Hunt**:
   - **Task**: Collect data on a continuous variable (e.g., daily rainfall in Mumbai for 30 days, Class X exam scores, or vegetable prices in a local market).
   - **Analysis**: Calculate the mean and standard deviation. Create a histogram and check if it fits a normal distribution.
   - **Deliverable**: Present your findings with a chart (use Google Sheets or Jamovi) and explain why the normal distribution does or doesn’t apply.

2. **Historical Application**:
   - **Task**: Analyze a historical dataset, like average grain prices in 18th-century Indian markets (from archival records) or word frequencies in the Mahabharata.
   - **Analysis**: Plot the data and assess if it follows a normal distribution. Discuss how this could inform historical research (e.g., economic stability).

3. **Poisson Exploration**:
   - **Task**: Count rare events, like the number of power outages in your town over a month or temple visitors on a festival day.
   - **Analysis**: Check if the data fits a Poisson distribution by plotting a histogram. Compare to the normal distribution for large counts.

---

## 🚀 What’s Next?

**Chapter 3.2: Hypothesis Testing**  
- **Learn**: Test claims about populations, like whether a new teaching method improves exam scores.  
- **Explore**: Apply hypothesis testing to social science data, such as voting patterns or literacy rates in Indian states.  
- **Apply**: Use statistical tools to validate historical or cultural hypotheses.

---

### Local Context Enhancement
- **Historical Analysis**: Use the normal distribution to study average lifespans or trade volumes in Mughal-era records, assuming large samples approximate normality.
- **Social Science**: Analyze literacy rates or income distributions across Indian states, leveraging the normal distribution for averages.
- **Cultural Studies**: Examine word frequencies in ancient texts (e.g., Rigveda) to see if they follow a normal or Poisson distribution, revealing patterns in language use.

This chapter equips humanities scholars with the tools to understand and apply probability distributions, particularly the normal distribution, to real-world and historical data. Upload this Markdown file to your GitHub repository for easy sharing and collaboration!