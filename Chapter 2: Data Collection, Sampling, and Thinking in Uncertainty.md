# 📋 Chapter 2: Data Collection, Sampling, and Thinking in Uncertainty

Welcome to **Chapter 2** of the *Statistical Thinking for Humanities Scholars* course!  
In this chapter, we explore how to **collect data properly**, understand **samples and populations**, avoid **bias**, and start thinking about **uncertainty and probability**.

---

## 🧪 Section 1: Data Collection and Sampling

### 🧠 Key Ideas

- **Population**: The entire group you want to study (e.g., all farmers in Wardha).
- **Sample**: A smaller group selected from the population (e.g., 100 farmers).
- **Goal**: Use the sample to say something meaningful about the population.

---

### 📦 Types of Sampling Methods

| Sampling Method        | Description                                             | Local Example                              |
|------------------------|---------------------------------------------------------|--------------------------------------------|
| **Simple Random**      | Every member has an equal chance                        | Randomly pick 50 students from 10th class. |
| **Stratified Sampling**| Divide into groups, then sample from each group         | Select farmers by taluka (Wardha, Hinganghat, etc.) |
| **Systematic**         | Every 10th name on a school attendance list             | Sample every 5th voter on a list           |
| **Convenience Sampling**| Easy-to-access people (⚠️ often biased)               | Asking only students nearby or online      |

---

### 🚨 What Is Bias?

**Bias** happens when your sample is not representative of the population.

#### 🔍 Examples of Bias in Vidarbha:
- Asking only male farmers, but not female farm laborers.
- Surveying students only from English-medium schools.
- Ignoring remote tribal villages in Melghat in health data.

---

### 🧑‍🏫 Activity: Conduct a Class Survey

1. Ask every student about:
   - Hours of sleep
   - Favorite local food
2. Compare results across gender or locality.
3. Discuss:
   - What population does your sample represent?
   - What kind of sampling method did you use?
   - Is there bias?

---

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

![Preview of the Applet](https://github.com/kwankhede/Statistical-Thinking-for-Humanities-Scholars/blob/main/chapter2.1.png)

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

## 📚 Homework / Practice

1. Sample rainfall data for the past 5 days in your town.
   - Calculate the average.
   - Discuss how much it varies.
2. Survey 10 people on:
   - Daily commute time to school
   - Calculate mean and standard deviation
3. Identify bias in a local newspaper survey.  
   - Who was surveyed?  
   - Who was excluded?

---

## 🧭 Coming Up Next Chapter:

📘 **Chapter 3: Probability Distributions and Inference**  
→ Learn how to model random events and draw conclusions from data!

---

### 🎯 Additional Key Concepts from the PDF

#### 📊 Probability Distribution Functions (PDFs)
- **Discrete PDF**: Assigns probabilities to each outcome in a finite set (e.g., coin toss: \( p(H) = 0.5 \), \( p(T) = 0.5 \)).
- **Continuous PDF**: Used for continuous variables (requires calculus, not covered here).

#### 🔄 Independent vs. Conditional Probabilities
- **Independent Events**: \( p(x, y) = p(x)p(y) \) (e.g., rolling two dice).
- **Conditional Probabilities**: \( p(x, y) = p(x|y)p(y) \) (e.g., drawing cards without replacement).

#### 📉 Central Limit Theorem
- For a large number of trials, the distribution of sample means tends to a **Normal (Gaussian) distribution**, regardless of the original distribution.

#### 🔍 Statistical Inference
- **Maximum Likelihood Estimation**: Finding the parameter value (e.g., \( \theta \)) that maximizes the likelihood of observed data.
- **Bayes Theorem**: \( p(x|y) = \frac{p(y|x)p(x)}{p(y)} \). Used to update probabilities based on new evidence.

---

### 🧩 Example: Maximum Likelihood Estimation
- **Scenario**: Flip a coin 8 times, get 6 heads and 2 tails.
- **Likelihood Function**: \( \mathcal{L}(\theta) = \theta^6 (1-\theta)^2 \).
- **Maximizing \( \mathcal{L}(\theta) \)**: Gives \( \theta_{\text{max}} = 0.75 \), suggesting the coin might be biased.

---

### 📝 Exercise
1. **Coin Flips**: Perform 10 coin flips, record heads/tails, and compute \( \theta_{\text{max}} \).
2. **Dice Rolls**: Roll a die 20 times, calculate the empirical probabilities for each outcome, and compare to the theoretical \( \frac{1}{6} \).

---

This chapter integrates foundational statistical concepts with practical applications, ensuring a deep understanding of data collection, probability, and inference. The next chapter will build on these ideas to explore probability distributions and advanced inference techniques.
