# 🔴 DAY 3 — A/B Testing + Final Notebook

## 🎯 Goal:

Think like a Data Scientist

---

## 🔥 Learn (2 hours)

Concept only:

- A/B testing = hypothesis testing in real life
- Null hypothesis (H0)
- Alternative hypothesis (H1)

---

## 💻 Build Mini A/B Framework

---

## ✔ Example Scenario

“Does new UI increase conversion rate?”

---

## ✔ Structure

```python
# Step 1: Define hypothesis
# H0: No difference
# H1: New version better

# Step 2: Collect data
A = [conversion rates]
B = [conversion rates]

# Step 3: Run test
ttest_ind(A, B)

# Step 4: Decision
if p < 0.05:
    print("New version wins")
else:
    print("No significant improvement")
```

---

## 🧠 Final Deliverables (CRITICAL)

### 📓 Notebook 1 — Descriptive Stats

- 3 datasets (Titanic, Iris, Housing)
- visualizations
- insights

### 📓 Notebook 2 — Hypothesis Testing

- t-test
- chi-square
- confidence interval
- A/B simulation
