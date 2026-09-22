# A/B Testing Experiment: E-Commerce Push Button

## 📌 Project Overview
This project demonstrates an end-to-end A/B testing experiment designed to evaluate the impact of a new push button on an e-commerce platform's conversion rate. The experiment involves analyzing user behavior split across Control and Treatment groups to make a data-driven product decision.

---

## 🔄 Workflow
```
Problem ➔ Hypothesis ➔ Treatment/Control ➔ OEC & Guardrail ➔ Analysis ➔ Decision
```

---

## 🔍 Experiment Details

### 1. Problem
Evaluating whether replacing the existing button with a new push button improves user interaction and sales performance on an e-commerce site.

### 2. Hypothesis
> **$H_0$ (Null Hypothesis):** The new push button has no effect on the conversion rate ($CR_{treatment} = CR_{control}$).  
> **$H_1$ (Alternative Hypothesis):** The new push button increases the conversion rate compared to the current button ($CR_{treatment} > CR_{control}$).

### 3. Treatment & Control Groups
- **Control Group:** 5,000 users (exposed to the current button design).
- **Treatment Group:** 5,000 users (exposed to the new push button design).
- **Total Sample Size:** 10,000 users.

### 4. Metrics
* **OEC (Overall Evaluation Criterion):** Conversion Rate (CR).
* **Guardrail Metrics:** Monitored to prevent secondary negative impacts (e.g., checkout error rate, page loading performance/latency).

### 5. Analysis Plan
* Compare the conversion rates between the Control and Treatment groups.
* Calculate the absolute and relative lift in conversion rate.
* Evaluate statistical significance using appropriate hypothesis testing (p-value evaluation and confidence intervals).

### 6. Decision Matrix
* **Rollout:** If the Treatment shows a statistically significant improvement ($p < 0.05$) without degrading guardrail metrics.
* **Maintain/Iterate:** If there is no statistically significant difference or if guardrail metrics degrade negatively.

---

## 🛠️ Tools & Technologies Used
* **Google Sheets / Excel:** Initial data organization and basic conversion rate calculations.
* **Python:** Statistical analysis, confidence interval calculation, and hypothesis testing.
* **Statsmodels:** Statistical hypothesis testing and p-value computation.
* **A/B Testing Simulator:** Simulating experiment scenarios and user group comparisons.
* **Power Analysis:** Calculating required sample size and Minimum Detectable Effect (MDE).

---

## 👥 Collaborators
* **Shaykhaa Mujri Alshwaifeen** — [GitHub Profile](https://github.com/ShaykhaaMujriAlshwaifeen)
* **Sarah** — [GitHub Profile](https://github.com/sarahdi1418)

---

## 🔗 Repository
* **GitHub Repository:** [SDAIA Academy](https://github.com/SDAIAAcademy)
