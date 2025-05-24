# 📊 Chapter 1: Introduction to Statistics

Welcome to **Chapter 1** of the *Statistical Thinking for Humanities Scholars* course!  
This chapter begins your journey into the world of statistics — a vital tool for understanding data, recognizing patterns, and making informed decisions, especially in the context of humanities studies and projects.

<br>

### 🧠 Everyday Statistical Thinking: Priors, Bias & Instinct

Before we even get into technical concepts, it's important to understand:

**You already reason statistically — every day, even without realizing it.**

Here are some everyday examples:

- **“It’s cloudy today — it might rain like yesterday, better carry an umbrella.”**  
  → Based on experience with weather patterns in your area.

- **“That lane usually has stray dogs — I’ll avoid it in the evening.”**  
  → A decision made from repeated observations.

- **“This doctor is always busy — they must be good.”**  
  → You’re associating popularity with quality based on observed trends.

- **“Buses from this stop are always late — I’ll leave 10 minutes earlier.”**  
  → Using prior patterns to plan your action.

These decisions are based on **past experiences**, **observed frequencies**, and **gut feeling** — what statisticians call **priors**.

> **Priors are useful, but they can also lead to biases if we’re not careful.**

<br>

### 🧠 What is Instinct?

**Instinct** is a fast, emotional, or automatic reaction. It often comes from your body’s built-in survival system — and is tied closely to your priors.

- **“That group of people looks suspicious — I’ll avoid them.”**  
  → A decision made instantly, often without conscious reasoning.

Instinct helps us react quickly, but it's not always based on evidence or fairness.

<br>

### 🚨 What is Bias?

**Bias** is when your prior beliefs or instincts consistently lead you to **unfair** or **inaccurate** judgments.

Examples from the Indian context:

- **“People from tribal areas aren’t serious about education.”**  
  → Ignores systemic challenges and generalizes unfairly.

- **“Only English-medium students succeed in exams.”**  
  → Overlooks success stories from rural and vernacular backgrounds.

- **“Boys are naturally better at maths than girls.”**  
  → A stereotype, not supported by actual data.

> Bias is often unconscious — but its effects can be very real.

<br>

### 🖼️ Question: Who Looks Like a Criminal?

![Who looks like a criminal?](https://github.com/kwankhede/Statistical-Thinking-for-Humanities-Scholars/blob/main/media/chapter1.1.png)

> “Which of these two individuals looks more like they have a criminal record?”  
> “Why do you think so?”  
> “Are you judging based on facts or instinct?”

**Important Note**: Neither individual in this image has a criminal record.  
This is a thought experiment to uncover how **bias and instinct** shape judgment.

<br>

### ⚠️ When Priors Might Be Wrong

Sometimes, priors can mislead us:

- **“People from this village always fail exams — why bother teaching them?”**  
  → Based on an outdated or biased sample.

- **“Girls are not good at math.”**  
  → A harmful prior based on stereotypes, not real data.

- **“If I didn’t get sick last time I drank tap water, it must be safe.”**  
  → A risky assumption that ignores invisible dangers.

> **Priors become dangerous when they are based on limited, biased, or outdated information.**

<br>

### 💬 Reflect

- Can you think of a time your assumption or “gut feeling” was wrong?
- What would better data or evidence have shown instead?
- How can we challenge harmful or misleading priors?

<br>

## 🔁 From Priors to False Dichotomies

As we’ve seen, **priors** — beliefs formed through personal experience, observation, or social messaging — help us make quick decisions.

But priors can become problematic when we treat them as **absolutes** — as if they represent the full truth of every situation.  
This leads us to a common mistake in reasoning: the **false dichotomy**.

<br>

### ❗️Understanding False Dichotomies

One common error in both everyday and statistical thinking is assuming **only two possibilities** — this is called a **false dichotomy**.

### 🔍 What is a False Dichotomy?

A **false dichotomy** simplifies a complex situation into two extreme options, ignoring everything in between.

> “Either you're with us, or you're against us.”  
> “This data is either correct or useless.”  
> “A village is either modern or backward.”

In reality, most situations fall on a **spectrum** — not into boxes.


<br>

![False Dichotomy vs. Spectrum](https://ozchen.com/wp-content/uploads/2018/02/binary-spectrum-thinking2.png)

<br>

### 🧪 Real-Life Examples

| Statement | Why It’s a False Dichotomy |
|----------|-----------------------------|
| “This person must either be guilty or innocent.” | Reality involves evidence, trial, and uncertainty. |
| “Students either love math or hate it.” | Many have mixed feelings or change over time. |
| “If data isn’t perfect, it’s useless.” | Imperfect data can still provide meaningful insights. |

<br>

### 🌾 More Examples

| Situation | False Dichotomy | What’s the Reality? |
|----------|------------------|---------------------|
| Crop success in Yavatmal | “The crop either failed or succeeded.” | There can be partial yield, mixed results. |
| Education in Melghat | “A student either drops out or completes school.” | Many students attend irregularly or migrate seasonally. |
| Weather in Buldhana | “It will either rain or not rain.” | There's usually a forecast with percentage likelihood. |

<br>

### 💬  For Studnets 

> “Can you recall a time when you were told to choose between two options, but felt there were more?”  
> - Think of local examples.  
> - Re-frame them into **spectrums**.  
> - Write or draw your version of a “third option.”

<br>

### 🧠 Why It Matters in Statistics

**False dichotomies block good reasoning.**  
They lead to bad survey questions, poor interpretation, and narrow conclusions.

**Statistics helps us:**
- Embrace complexity and nuance
- Think in terms of **range**, **variation**, and **probability**
- Make better decisions based on **evidence**, not assumption

---

<br>
<br>
<br>


# 🔍 What is Statistics?

**Statistics** is the science (and art) of:
- **Collecting** data
- **Organizing** it clearly
- **Analyzing** it to find patterns
- **Interpreting** it to make decisions

It helps us understand the world by turning raw data into useful knowledge.

> “You are bombarded with numbers every day. What do these numbers mean?”  
> - 30% chance of rain tomorrow  
> - NCP polling 32% in elections (±5% margin of error)  
> - COVID-19 fatality rate of 1.5% in India  

---

## 📘 Statistics: A Science and an Art

- **Science**: Uses mathematical tools and models.
- **Art**: Requires judgment — what to keep, what to discard.

> *Example (Vidarbha)*: A farmer in Wardha analyzes rainfall data to decide the best time to sow cotton.

---

## 🗃️ What is Data?

**Data** = collections of facts: numbers, names, categories.

> *Example dataset*:  
> `Sex | Height (cm) | Weight (kg)`  
> `F | 150.2 | 45.3`  
> `M | 160.0 | 60.1`

Data needs **cleaning** before analysis:
- Remove symbols like `@` or `#`
- Handle missing or extreme values
- Record uncertainty (e.g., ± 0.1 cm)

---

## 📘 Branches of Statistics

| Branch               | Description                                           | Example (Vidarbha)                                |
|----------------------|-------------------------------------------------------|---------------------------------------------------|
| **Descriptive**      | Summarizes data using graphs, tables, averages        | Cotton yield in Wardha                            |
| **Inferential**      | Makes predictions from a sample to a population       | Survey 100 farmers in Yavatmal to infer trends    |

---

## 📌 Why Is Statistics Important?

**Real-world uses in Vidarbha**:
- 📈 Farming: Compare fertilizer impacts in Akola
- 🏥 Public Health: Dengue tracking in Nagpur
- 🎓 Education: Literacy rates in tribal schools
- 🌧️ Climate: Rain forecasts in Buldhana
- 🗳️ Elections: Polling analysis in Gram Panchayats

---

## 🧩 Types of Data

### A. **Qualitative (Categorical)**

- Categories or labels (not numbers)  
  e.g. Soil type, favorite food, caste

### B. **Quantitative (Numerical)**

#### Discrete:
- Countable values (e.g. cows, family members)

#### Continuous:
- Measurable values (e.g. weight, rainfall, height)

---

## 🎯 What Is a Statistical Question?

A **statistical question** looks for patterns or variation:

| Example                              | Type                |
|--------------------------------------|---------------------|
| “How tall are you?”                  | Not statistical     |
| “What is the average height in Wardha?” | Statistical         |
| “How do test scores vary across Vidarbha?” | Statistical       |

---

## 💬 Think & Reflect

- Have you ever judged based on a **false binary**?
- What role do your **priors** play in decision-making?
- Where do you see statistics being used (or misused) in daily life?

---

## 📝 Summary Table

| Concept             | Description                                      |
|---------------------|--------------------------------------------------|
| **Priors**          | Assumptions formed by past experience            |
| **False Dichotomy** | Artificial two-option thinking                   |
| **Statistics**      | The science of data                              |
| **Descriptive**     | Describes data (mean, graphs, etc.)              |
| **Inferential**     | Generalizes from sample to population            |
| **Qualitative**     | Categories (e.g. type of land)                   |
| **Quantitative**    | Numbers (discrete or continuous)                 |
| **Data Cleaning**   | Preparing data for analysis                      |
| **Statistical Question** | Involves patterns, not one fixed answer    |

---

## 📚 Homework/Practice

1. Collect 3 examples of **false dichotomies** from media or personal life.  
2. Interview 5 classmates:
   - Age, gender, favorite food.
   - Classify each data type.
3. Write a short paragraph on how one of your **priors** has changed over time due to evidence or experience.

---
