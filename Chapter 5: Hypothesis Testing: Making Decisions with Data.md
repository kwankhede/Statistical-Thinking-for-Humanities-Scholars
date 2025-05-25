![banner](https://github.com/kwankhede/Statistical-Thinking-for-Humanities-Scholars/blob/main/media/banner.png)


# 📊 Chapter 5: Hypothesis Testing: Making Decisions with Data

Welcome to **Chapter 5**! 🎉
In this chapter, we will learn how to use **hypothesis testing** to make decisions or draw conclusions about a population based on sample data. Hypothesis testing helps us answer questions like:
*Is the average study time really different from 5 hours?* or *Does a new teaching method improve test scores?*

<br>


## 🧠 What is Hypothesis Testing?

Hypothesis testing is a **statistical method** to evaluate a claim or assumption about a population using data from a sample.

* Think of it as a way to **test an idea** with numbers.
* You start with a question or claim (called a hypothesis), then use your sample data to decide if there’s enough evidence to support or reject it.

### Example:

*Is the average study time of students different from 5 hours per week?*

We want to check if the true average study time, $\mu$, is 5 hours or something else.

<br>

## 📝 Steps of Hypothesis Testing

### 1. State Hypotheses

* **Null Hypothesis ($H_0$)**: The claim we test directly. Usually states “no effect” or “no difference.”

  * Example: $H_0: \mu = 5$ hours (average study time is 5 hours).

* **Alternative Hypothesis ($H_1$ or $H_a$)**: What we want to find evidence for. It states there *is* an effect or difference.

  * Example: $H_1: \mu \neq 5$ hours (average study time is not 5 hours).

> Note:
>
> * $H_1$ can be two-sided ($\neq$) or one-sided ($<$ or $>$) depending on the question.

<br>

### 2. Set Significance Level ($\alpha$)

* This is the **threshold probability** for deciding if results are “unlikely enough” to reject $H_0$.
* Commonly used value: $\alpha = 0.05$ (5% risk of rejecting a true null hypothesis).

<br>

### 3. Collect Data and Calculate Test Statistic

* For means when population standard deviation ($\sigma$) is known, use the **z-test** formula:

$$
z = \frac{\bar{x} - \mu}{\sigma / \sqrt{n}}
$$

* Where:

  * $\bar{x}$ = sample mean
  * $\mu$ = hypothesized population mean under $H_0$
  * $\sigma$ = population standard deviation
  * $n$ = sample size

### Example Calculation:

Suppose:

* Sample mean study time $\bar{x} = 5.5$ hours
* Population standard deviation $\sigma = 1.2$ hours
* Sample size $n = 36$
* Hypothesized mean $\mu = 5$ hours

Calculate:

$$
z = \frac{5.5 - 5}{1.2 / \sqrt{36}} = \frac{0.5}{1.2 / 6} = \frac{0.5}{0.2} = 2.5
$$

<br>

### 4. Calculate P-value

* The **p-value** tells us the probability of getting a test statistic as extreme as ours *if the null hypothesis is true*.
* Use z-tables or software to find p-value from $z$.

For $z = 2.5$:

* For a two-tailed test:

  $$
  p = 2 \times P(Z > 2.5) \approx 2 \times 0.0062 = 0.0124
  $$

<br>

### 5. Make a Conclusion

* If $p < \alpha$, **reject the null hypothesis** $H_0$. There is sufficient evidence to support the alternative $H_1$.
* If $p \geq \alpha$, **fail to reject $H_0$**. Not enough evidence to say the claim is false.

**In our example:**

* $p = 0.0124 < 0.05$ → Reject $H_0$
* Conclusion: The average study time is statistically significantly different from 5 hours.

<br>

## ⚠️ Types of Errors in Hypothesis Testing

| Error Type  | Description                        | Example                                                |
| ----------- | ---------------------------------- | ------------------------------------------------------ |
| **Type I**  | Rejecting $H_0$ when it is true    | Saying study time differs when it really doesn’t       |
| **Type II** | Failing to reject $H_0$ when false | Saying study time doesn’t differ when it actually does |

* $\alpha$ controls the probability of a **Type I error**.
* Reducing Type I errors can increase Type II errors, so balance is important.

<br>

## 🔍 One-Sample Z-Test Summary

Use this test when:

* Population standard deviation $\sigma$ is known.
* Sample size $n \geq 30$ (or population is normal).

**Example:**

Test if the average student sleep time differs from 7 hours:

* $H_0: \mu = 7$ hours
* $H_1: \mu \neq 7$ hours
* Collect sample data, calculate z-score, find p-value, then conclude.

<br>

## 📈 Useful Resources for Z-Tables and Calculations

### Z-Score Tables (Standard Normal Distribution Tables)

* [Z-Table (Standard Normal Table) — Wikipedia](https://en.wikipedia.org/wiki/Standard_normal_table)
* [Interactive Z-Table — StatTrek](https://stattrek.com/statistics/tables/z-table.aspx)
* [Z-Score Table PDF — MathIsFun](https://www.mathsisfun.com/data/images/normal-distribution-table.svg)

### Online Calculators and Software

* **Online p-value calculator for Z-test:**
  [GraphPad QuickCalcs](https://www.graphpad.com/quickcalcs/pvalue1/)
* **Statistical software:**

  * [R Project](https://www.r-project.org/) — use `pnorm()` for z-distribution
  * [Python (SciPy)](https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.norm.html) — use `scipy.stats.norm.cdf()`
* **General online hypothesis test calculator:**
  [Social Science Statistics Z-Test Calculator](https://www.socscistatistics.com/tests/ztest/Default2.aspx)



<br>

## 📚 Summary Table

| Step                         | Description                                         |
| ---------------------------- | --------------------------------------------------- |
| **State Hypotheses**         | Write $H_0$ and $H_1$ based on your question        |
| **Set Significance Level**   | Choose $\alpha$, usually 0.05                       |
| **Calculate Test Statistic** | Use formula for z or t based on data                |
| **Find P-value**             | Probability of observing test statistic under $H_0$ |
| **Make Conclusion**          | Reject or fail to reject $H_0$ based on p-value     |
| **Recognize Errors**         | Know Type I and Type II error risks                 |

<br>


