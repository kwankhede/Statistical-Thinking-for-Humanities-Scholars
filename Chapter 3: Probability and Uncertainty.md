# 🎲 Chapter 3: Probability, Expected Value & Law of Large Numbers

Welcome to **Chapter 3** of *Statistical Thinking for Humanities Scholars*!
Now that we’ve explored how to describe data, we shift to the world of **uncertainty and prediction**. In this chapter, we explore:

* The basics of probability
* Expected value (EV)
* Law of Large Numbers (LLN)
* Bayes' Theorem (intro level)

---

## 🔢 Section 1: Basics of Probability

**Probability** is the branch of mathematics that deals with measuring uncertainty — what *might* happen.

### 🎯 Key Concepts

* **Experiment**: A repeatable process (e.g., flipping a coin)
* **Outcome**: A possible result (e.g., heads or tails)
* **Event**: One or more outcomes (e.g., getting a head)
* **Probability of an event**:

  $$
  P(E) = \frac{\text{Number of favorable outcomes}}{\text{Total number of outcomes}}
  $$

### 🪙 Coin Toss Example

* Flip a fair coin → Outcomes: heads (H), tails (T)
* $P(H) = \frac{1}{2}$

### 🎲 Dice Roll Example

* Roll a fair six-sided die: Outcomes = 1, 2, 3, 4, 5, 6
* Probability of getting a 4:

  $$
  P(4) = \frac{1}{6}
  $$

---

## 🧠 Section 2: The Law of Large Numbers (LLN)

The **Law of Large Numbers** says that as an experiment is repeated many times, the average result gets closer to the **expected probability**.

### 🔁 Coin Toss Simulation

| Tosses | Heads | Tails | Ratio (H\:T) |
| ------ | ----- | ----- | ------------ |
| 10     | 6     | 4     | 1.5          |
| 100    | 52    | 48    | 1.08         |
| 1000   | 498   | 502   | 0.99         |

> 🔍 As the number of tosses increases, the outcomes stabilize around 50:50 — this is the **LLN** in action!

### 📘 Real-Life Applications

* Political polling: more people = more accurate results
* Weather forecasting: repeated patterns guide future estimates
* Agriculture: estimating long-term yield from past averages

---

## 💰 Section 3: Expected Value (EV)

**Expected Value** is the average result you'd expect **in the long run**.

### 🔍 Formula:

$$
EV = \sum (\text{Value} \times \text{Probability})
$$

### 🎲 Dice Example:

* Roll a fair die:

  $$
  EV = \frac{1+2+3+4+5+6}{6} = 3.5
  $$

> ⚠️ You’ll never roll a 3.5, but it’s the **average outcome over time**.

### 💵 Lottery Example:

* Win Rs. 100 with $P = 0.01$; lose Rs. 10 with $P = 0.99$

  $$
  EV = (100 \times 0.01) + (-10 \times 0.99) = 1 - 9.9 = -8.9
  $$

> 📌 This shows the **expected loss** — helps you decide whether a bet is worth it.

---

## 🔄 Section 4: Bayes' Theorem (Intuitive Intro)

**Bayes' Theorem** helps update probabilities **after seeing new evidence**.

### 🧪 Medical Testing Example:

* Disease is rare (1 in 1000)
* Test is 99% accurate
* You test positive. What are the chances you really have the disease?

> ❗ Intuition says: “99%!” but real probability is much lower — because the disease is rare.

This is where **Bayes’ Rule** helps combine:

* Prior probability (before the test)
* Likelihood of the test being right

We’ll explore full calculations in later chapters. For now, remember:

> **Bayes’ Theorem helps update beliefs when new data appears.**

---

## 🧩 Think & Reflect

* Why does flipping a coin many times give more reliable results?
* How does EV help in making financial decisions?
* Can two events be highly correlated but not causally related?

---

## 📚 Summary Table

| Concept                  | Meaning                                       |
| ------------------------ | --------------------------------------------- |
| **Probability**          | Chance of an event happening                  |
| **Expected Value**       | Long-run average outcome                      |
| **Law of Large Numbers** | Probabilities stabilize with many repetitions |
| **Bayes' Theorem**       | Updates probability using new evidence        |

---

## 🧭 Coming Up Next:

📈 **Correlation, Causation, and Scatterplots**
Explore how variables relate and what we can (and can’t) conclude from patterns!
