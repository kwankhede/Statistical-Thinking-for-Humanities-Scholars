# 📊 Chapter 3: Probability Distributions and Statistical Inference

Welcome to **Chapter 3** of *Statistical Thinking for Humanities Scholars*!  
This chapter dives into **probability distributions**, **hypothesis testing**, and **real-world applications** of statistical inference.

---

## 🎲 Section 1: Common Probability Distributions

### 📌 Key Distributions Every Researcher Should Know

| Distribution       | When to Use                          | Formula (PMF/PDF)                     | Local Example                          |
|--------------------|--------------------------------------|----------------------------------------|----------------------------------------|
| **Binomial**       | Yes/No outcomes (n trials)           | `P(X=k) = C(n,k) p^k (1-p)^(n-k)`     | % of farmers adopting new crop (survey 100) |
| **Poisson**        | Rare event counts                    | `P(X=k) = (λ^k e^-λ)/k!`              | Number of power outages per month in Nagpur |
| **Normal**         | Continuous data, averages            | `f(x) = (1/σ√2π) e^[-(x-μ)²/2σ²]`     | Student heights in Mumbai schools      |
| **Uniform**        | Equal probability outcomes           | `f(x) = 1/(b-a)`                      | Lottery number selection               |

---

### 🧑🏽‍🏫 Classroom Activity: Distribution Detective
1. Collect real-world data from your community:
   - **Binomial**: Survey 20 neighbors "Do you use public transport daily?" (Yes=1, No=0)
   - **Poisson**: Count potholes per km on 5 local roads
2. Plot histograms and match to distributions
3. Discuss: Which distribution fits best? Why?


---

## 📉 Section 2: The Normal Distribution in Depth

### 🌟 Why It Matters
- **Central Limit Theorem**: Sample means → Normal distribution
- **Empirical Rule**:
  - 68% within 1σ of μ
  - 95% within 2σ
  - 99.7% within 3σ

### 🧮 Local Calculation Example
**Farmer incomes in Wardha district (monthly, in ₹):**  
μ = 15,000, σ = 3,000  
- What % earn between 12,000-18,000?  
  `(Answer: 68%)`  
- What income is at the 95th percentile?  
  `(Answer: μ + 1.96σ ≈ 20,880)`

![Normal Curve](https://www.simplypsychology.org/wp-content/uploads/normal-distribution.jpg)

---

## 🔍 Section 3: Hypothesis Testing Step-by-Step

### 🧪 The Tea Experiment (Inspired by Fisher)
**Scenario**: A Kolhapur woman claims she can identify if milk was added before or after tea brewing. Test her with 8 trials.

1. **Null Hypothesis (H₀)**: She's guessing (p=0.5)
2. **Alternative (H₁)**: She can tell (p>0.5)
3. **Test**: If she gets ≥7 right, reject H₀
4. **Calculation**:
   - P(7 right) = C(8,7)(0.5)^8 = 0.03125
   - P(8 right) = 0.0039
   - Total p-value = 0.035 < 0.05 → Significant!

---

### 🏥 Public Health Application
**Malaria Testing in Gadchiroli**:
- Old test: 70% accurate
- New test: Claims 85% accuracy (n=100 patients)
- **Z-test**:
  ```python
  z = (0.85 - 0.70)/sqrt(0.7*0.3/100) ≈ 3.27
  ```
  p-value < 0.001 → New test is better!

---

## 📈 Section 4: Bayesian Thinking

### ⚖️ Bayes' Theorem in Action
`P(A|B) = [P(B|A)*P(A)] / P(B)`

**Real Case**:  
- **Prior**: 2% COVID prevalence in Pune
- **Test**: 95% true positive rate, 3% false positives
- **Positive test result**: What's the actual probability?
  
**Calculation**:
```
P(COVID|+) = (0.95*0.02)/[(0.95*0.02)+(0.03*0.98)] ≈ 39.2%
```
→ Even with positive test, ~60% chance it's wrong!

---

## � Section 5: Common Statistical Tests

### 🔎 Test Selection Guide
| Situation                          | Test               | Example Use Case                      |
|------------------------------------|--------------------|---------------------------------------|
| Compare 2 means                    | t-test             | Exam scores: urban vs rural schools   |
| Compare >2 means                   | ANOVA              | Crop yields: 3 fertilizer types       |
| Categorical association            | Chi-square         | Voting preference by gender           |
| Before-after measurement           | Paired t-test      | Student performance pre/post coaching |

---

### 🧮 DIY Statistical Analysis
**Project**: Analyze local water quality data  
1. **Data**: Collect pH levels from 10 wells (morning/evening)
2. **Tests**:
   - One-sample t-test (compare to pH=7 neutral)
   - Paired t-test (morning vs evening)
3. **Tools**: Use free software like Jamovi or PSPP

---

## 📋 Summary Cheat Sheet

| Concept                 | Key Formula                          | Remember                          |
|-------------------------|--------------------------------------|-----------------------------------|
| **Normal Distribution** | `Z = (X - μ)/σ`                      | 68-95-99.7 rule                   |
| **Binomial**            | `P(X=k) = nCk p^k (1-p)^(n-k)`       | Count successes                   |
| **Type I Error**        | False positive (α)                   | 5% default threshold              |
| **Type II Error**       | False negative (β)                   | Power = 1 - β                     |
| **Bayes' Rule**         | `P(A|B) = P(B|A)P(A)/P(B)`           | Update beliefs                    |

---

## 📚 Homework & Field Exercises

1. **Distribution Hunt**:
   - Find 3 real-world datasets (e.g., cricket scores, rainfall, shop sales)
   - Identify which distribution each follows
   - Present evidence (histograms + reasoning)

2. **Hypothesis Test**:
   - Claim: "Local buses are late >30% of time"
   - Collect data (sample 20 bus arrivals)
   - Perform binomial test at α=0.05

3. **Bayesian Puzzle**:
   - Prior: 10% of village has diabetes
   - Test is 90% accurate with 5% false positives
   - Calculate P(Diabetes | Positive)

---

## 🚀 What's Next?

📘 **Chapter 4: Regression and Relationships**  
→ Learn how to predict crop yields from rainfall data!  
→ Discover correlations in social science data.

---

