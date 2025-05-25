# 🎲 Chapter 3: Probability, Expected Value & Law of Large Numbers

Welcome to **Chapter 3** of *Statistical Thinking for Humanities Scholars*!  
Now that we’ve explored how to describe data, we shift to the world of **uncertainty and prediction**. In this chapter, we explore:

* The basics of probability
* Expected value (EV)
* Law of Large Numbers (LLN)
* Probability distributions (discrete and continuous)
* Bayes' Theorem (intro level)

<br>

## 🔢 Section 1: Basics of Probability

**Probability** measures the chance or likelihood that something will happen. It always lies between **0** (impossible) and **1** (certain).

### 🎯 Key Concepts

- **Experiment**: A repeatable process (e.g., flipping a coin)
- **Outcome**: A possible result (e.g., heads or tails)
- **Event**: One or more outcomes (e.g., getting a head)
- **Probability of an event**:

  $$
  P(E) = \frac{\text{Number of favorable outcomes}}{\text{Total number of outcomes}}
  $$

<br>

## 🎲 Examples of Simple Probability

### 🪙 Coin Toss Example

- Flip a fair coin → Outcomes: heads (H), tails (T)
- $P(H) = \frac{1}{2}$

### 🎲 Dice Roll Example

- Roll a fair six-sided die → Outcomes = 1, 2, 3, 4, 5, 6
- Probability of getting a 4:


$$
P(4) = \frac{1}{6}
$$



### 🔗 Compound Events

**What's the probability of flipping a head AND rolling a 4?**

- Independent events:  
  $P(H \text{ and } 4) = \frac{1}{2} \times \frac{1}{6} = \frac{1}{12}$

<br>

## ➕ Rules of Probability

### ✅ Addition Rule (Mutually Exclusive Events)

If two events **cannot happen at the same time**, like rolling a 2 or a 5:

$$
P(2 \text{ or } 5) = P(2) + P(5) = \frac{1}{6} + \frac{1}{6} = \frac{1}{3}
$$

### ✖ Multiplication Rule (Independent Events)

For two **independent events**, like rolling a die and flipping a coin:

$$
P(4 \text{ and } H) = P(4) \times P(H) = \frac{1}{6} \times \frac{1}{2} = \frac{1}{12}
$$

<br>

## 📊 Section 2: Probability Distributions

A **probability distribution** tells us how probabilities are distributed over values of a random variable.

---

### 🔹 Discrete Probability Distributions

A **discrete random variable** takes on **specific, countable values**.  
Examples include number of children in a family, number of books read in a month, number of goals scored.

| X (Value) | P(X) (Probability) |
|----------|---------------------|
| 0        | 0.1                 |
| 1        | 0.3                 |
| 2        | 0.4                 |
| 3        | 0.2                 |
| **Total**| **1.0**             |

> ✅ The sum of all probabilities in a distribution is always **1**.

<br>

### 🔸 The Binomial Distribution

Used when:

- There are **fixed number of trials** (n)
- Each trial has **two outcomes** (success/failure)
- Probability of success is the same each time

#### Example:

What is the probability of getting **exactly 2 heads** in 3 flips of a fair coin?

Use the **binomial formula**:

$$
P(X = 2) = \binom{3}{2} \cdot (0.5)^2 \cdot (0.5)^1 = 3 \cdot 0.25 \cdot 0.5 = 0.375
$$

<br>

### 📈 Continuous Probability Distributions

A **continuous random variable** can take **any value in a range**.

Examples: height, weight, temperature, time

Unlike discrete variables, we **don’t assign probabilities to exact values**, but rather to **intervals**:

> Probability of a person being **exactly** 170 cm tall = 0  
> But: Probability of being **between** 169.5 and 170.5 cm ≠ 0

<br>

### 🔔 The Normal Distribution (Bell Curve)

- Symmetric and bell-shaped
- Most values cluster around the **mean**
- Standard deviation controls spread

![Normal Distribution](https://upload.wikimedia.org/wikipedia/commons/thumb/8/8c/Standard_deviation_diagram.svg/500px-Standard_deviation_diagram.svg.png)

Real-world examples:

- Test scores
- Heights of students
- Average rainfall

<br>

## 🔁 Section 3: Law of Large Numbers (LLN)

The **Law of Large Numbers** says that as you repeat an experiment more times, the **average** result approaches the **expected value**.

### 🧪 Coin Toss Example

| Tosses | Heads | Tails | Heads % |
|--------|-------|-------|---------|
| 10     | 6     | 4     | 60%     |
| 100    | 52    | 48    | 52%     |
| 1000   | 498   | 502   | 49.8%   |

> ✅ More trials = closer to theoretical probability (50%)

<br>

## 💰 Section 4: Expected Value (EV)

The **expected value** is the average outcome you'd expect over many repetitions.

### 🔍 Formula:

$$
EV = \sum (\text{Value} \times \text{Probability})
$$

### 🎲 Dice Example

- Roll a fair die:

  $$
  EV = \frac{1+2+3+4+5+6}{6} = 3.5
  $$

<br>

### 💵 Real-Life Example: Lottery

- Win ₹100 with $P = 0.01$
- Lose ₹10 with $P = 0.99$

  $$
  EV = 100 \cdot 0.01 + (-10) \cdot 0.99 = 1 - 9.9 = -₹8.9
  $$

> ❌ Negative EV → not a good long-term decision!

<br>

## 🔄 Section 5: Bayes' Theorem (Intuition Only)

Helps us **revise probability** based on new information.

### 🧪 Medical Testing Example

- Rare disease: 1 in 1000 has it
- Test is 99% accurate
- You test positive. What's the chance you actually have it?

> 🤯 It’s NOT 99%!  
> You must consider the **base rate** (how rare the disease is).

We’ll explore full Bayesian reasoning in a later chapter.

![Bays Theorem](https://github.com/kwankhede/Statistical-Thinking-for-Humanities-Scholars/blob/main/media/3.1.jpeg)

<br>

## 🧠 Think & Reflect

- Why does flipping a coin 1000 times give more accurate results than flipping it 10 times?
- If a lottery has a positive expected value, should you play it?
- What makes a distribution "normal"? Can height or salary ever be "normally distributed"?

<br>

## 💻 Explore More: Interactive Tools

🎮 Try this simulation:  
👉 [Probability Applet – BFW Stats](https://digitalfirst.bfwpub.com/stats_applet/stats_applet_10_prob.html)

> Simulate coin tosses, dice rolls, binomial trials and visualize the **law of large numbers** and **distributions** in action!

<br>

## 📚 Summary Table

| Concept                  | Meaning                                       |
|--------------------------|-----------------------------------------------|
| **Probability**          | Chance of an event happening                  |
| **Expected Value**       | Long-run average outcome                      |
| **Law of Large Numbers** | Results stabilize with repetition             |
| **Discrete Distribution**| Probabilities for countable values            |
| **Normal Distribution**  | Bell-curve distribution in continuous data    |
| **Bayes' Theorem**       | Updating beliefs with new evidence            |

<br>

## 🧭 Coming Up Next:

📉 **Chapter 4: Correlation, Causation, and Scatterplots**  
Explore how variables relate — and when NOT to jump to conclusions!
