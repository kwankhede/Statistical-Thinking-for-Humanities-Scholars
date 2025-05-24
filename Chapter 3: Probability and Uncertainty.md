# 🎲 Chapter 3: Probability and Uncertainty

Welcome to **Chapter 3** of *Statistical Thinking for Humanities Scholars*!  
In this chapter, we explore how **chance**, **uncertainty**, and **patterns** shape our decisions and data interpretation.

---

Here's a more **detailed and student-friendly explanation** of the two sections — **Basics of Probability** and **Expected Value** — with added depth, clarity, local examples, and visual-friendly formatting in Markdown:

---

## 🔢 Section 1: Basics of Probability

**Probability** is the mathematics of **uncertainty** — a way to quantify how likely something is to happen.

We use probability to make predictions and decisions in real life:

* “Will it rain tomorrow?” → Based on weather models.
* “What’s the chance a student in our class prefers Marathi over Hindi?” → Based on survey data.

---

### 🎯 Key Concepts

| Term             | Meaning                                       | Example                |
| ---------------- | --------------------------------------------- | ---------------------- |
| **Experiment**   | A repeatable action whose result is uncertain | Flipping a coin        |
| **Outcome**      | A single result of an experiment              | Heads (H) or Tails (T) |
| **Event**        | A group of outcomes we're interested in       | Getting a Head         |
| **Sample Space** | All possible outcomes                         | {Heads, Tails}         |
| **Probability**  | Likelihood of an event occurring              | See formula below      |

---

### 📐 Probability Formula

$$
P(E) = \frac{\text{Number of favorable outcomes}}{\text{Total number of possible outcomes}}
$$

Where:

* $E$ = event
* $P(E)$ = probability of event $E$

---

### 🪙 **Coin Toss Example**

* Flip a fair coin:

  * Outcomes: Heads (H), Tails (T)
  * Total outcomes = 2

#### Probability of getting a head:

$$
P(H) = \frac{1}{2} = 0.5 = 50\%
$$

#### Probability of getting tails:

$$
P(T) = \frac{1}{2} = 0.5
$$

---

### 🎲 **Local Real-Life Examples**

| Situation                                                 | Experiment                 | Sample Space     | Probability                          |
| --------------------------------------------------------- | -------------------------- | ---------------- | ------------------------------------ |
| Drawing a chit from a jar with 5 Marathi & 3 Hindi labels | Pull one chit              | {Marathi, Hindi} | $P(\text{Marathi}) = \frac{5}{8}$    |
| Randomly picking a student in uniform                     | Ask: Is it a girl or boy?  | {Girl, Boy}      | Based on class ratio                 |
| Tossing two coins                                         | (H,H), (H,T), (T,H), (T,T) | 4 outcomes       | $P(\text{both heads}) = \frac{1}{4}$ |

---

### ✅ Important Notes

* **Probabilities are always between 0 and 1** (or 0% to 100%)
* The **sum of probabilities of all outcomes** in a sample space is always **1**

---

## 💰 Section 2: Expected Value (EV)

The **Expected Value (EV)** of a random process is its **long-run average** if the process is repeated many times.

Think of it as:

> “What do I expect **on average** after repeating this experiment a lot?”

---

### 📐 Expected Value Formula

$$
EV = \sum (\text{Value} \times \text{Probability})
$$

You multiply each outcome by its probability and add the results.

---

### 🎲 **Example: Rolling a 6-Sided Die**

Outcomes = {1, 2, 3, 4, 5, 6}
Each has equal chance: $\frac{1}{6}$

$$
EV = 1 \times \frac{1}{6} + 2 \times \frac{1}{6} + 3 \times \frac{1}{6} + 4 \times \frac{1}{6} + 5 \times \frac{1}{6} + 6 \times \frac{1}{6}
$$

$$
EV = \frac{1 + 2 + 3 + 4 + 5 + 6}{6} = \frac{21}{6} = 3.5
$$

> ⚠️ You will never actually roll a 3.5, but over hundreds of rolls, **the average** outcome will approach 3.5.

---

### 🧑🏽‍🌾 **Local Example: Crop Yield Lottery**

A cooperative offers the following random bonus to farmers:

| Bonus (₹) | Probability |
| --------- | ----------- |
| 0         | 0.3         |
| 500       | 0.5         |
| 1000      | 0.2         |

$$
EV = 0 \times 0.3 + 500 \times 0.5 + 1000 \times 0.2 = 0 + 250 + 200 = ₹450
$$

> The **expected value** of the bonus is ₹450.

---

### 💡 Why Expected Value Matters

* Helps you decide whether a **game**, **bet**, or **investment** is worth it.
* Gives you a realistic **long-term outcome**, not a one-time result.
* It's used in **insurance**, **finance**, **economics**, and **policy making**.


## 📊 Section 3: Scatterplots & Correlation

### 📌 Scatterplots

A **scatterplot** shows the relationship between two numerical variables.

| Variable X        | Variable Y               |
|-------------------|--------------------------|
| Rainfall in mm    | Crop yield in kg         |
| Study hours       | Exam marks               |
| Daily temperature | Electricity consumption  |

> Plot points (X, Y) to see the trend or pattern.

---

### 📉 Correlation

**Correlation** measures how strongly two variables are related.

- **Positive correlation**: Both increase together
- **Negative correlation**: One increases, other decreases
- **No correlation**: No clear pattern

\[
r = \text{Correlation coefficient} \in [-1, 1]
\]

---

## 🚫 Correlation ≠ Causation

Just because two variables are related doesn’t mean one causes the other.

### ❗️Example:

| Observation | Correlation? | Real Cause?         |
|-------------|--------------|---------------------|
| Ice cream sales and drowning cases | ✅ Yes | 🔥 Summer heat (third factor) |
| Shoe size and reading ability in kids | ✅ Yes | 📈 Age (not shoes)            |

> Be cautious! Always investigate further before assuming cause and effect.

---

## 🧭 Summary Table

| Concept              | Description                                      |
|----------------------|--------------------------------------------------|
| **Probability**       | Chance of an event happening                    |
| **Expected Value**    | Long-run average outcome                        |
| **Law of Large Numbers** | More data = more accurate average           |
| **Scatterplot**       | Graph of two variables to show relationship     |
| **Correlation**       | Measures strength/direction of relationship     |
| **Causation**         | One variable directly affects another           |

---

## 💬 Reflect & Discuss

- Have you ever made a decision based on a *small sample*?
- Can you think of examples where **correlation was misunderstood as causation**?
- How can probability help you make better everyday decisions?

---

## 🚀 Coming Up Next:

📘 **Chapter 4: Distributions and Sampling Theory**  
→ Learn about normal curves, skewness, sampling errors, and more!

