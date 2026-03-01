# Flashcards: A Few Useful Things to Know About Machine Learning
Author: Pedro Domingos (2012)

Use actively. Do not read passively.
Try answering before expanding.

---

## SECTION 1 — Foundations

### Card 1
**Q:** What is the true objective of machine learning?  
**A:** Minimize test error (generalization error), not training error.

---

### Card 2
**Q:** Why is training accuracy meaningless alone?  
**A:** Flexible models can memorize training data. Memorization ≠ generalization.

---

### Card 3
**Q:** What is contamination in ML evaluation?  
**A:** Any leakage of test data into model tuning or design decisions.

---

### Card 4
**Q:** What three components define any ML algorithm?  
**A:** Representation + Evaluation + Optimization.

---

### Card 5
**Q:** If a model performs poorly, which three things must you inspect?  
**A:** Hypothesis space, objective function, optimization process.

---

## SECTION 2 — Inductive Bias & No Free Lunch

### Card 6
**Q:** Why is inductive bias necessary?  
**A:** Without assumptions, generalization from finite data is impossible.

---

### Card 7
**Q:** What does No Free Lunch imply?  
**A:** No learner is universally best across all possible problems.

---

### Card 8
**Q:** What happens if you assume nothing about the world?  
**A:** You cannot predict unseen data better than random guessing.

---

## SECTION 3 — Bias–Variance Tradeoff

### Card 9
**Q:** What is bias?  
**A:** Error from overly strong assumptions.

---

### Card 10
**Q:** What is variance?  
**A:** Error from sensitivity to small changes in training data.

---

### Card 11
**Q:** Can you minimize bias and variance simultaneously?  
**A:** No. Reducing one increases the other.

---

### Card 12
**Q:** When can a simple but wrong model outperform a complex true one?  
**A:** When data is limited and variance dominates.

---

## SECTION 4 — Overfitting

### Card 13
**Q:** Does overfitting require noisy data?  
**A:** No. Even noise-free data can be overfit if model capacity is too high.

---

### Card 14
**Q:** Can cross-validation overfit?  
**A:** Yes. Repeated hyperparameter tuning effectively tests many hypotheses.

---

### Card 15
**Q:** Does regularization eliminate overfitting?  
**A:** No. It shifts the bias–variance balance.

---

## SECTION 5 — Curse of Dimensionality

### Card 16
**Q:** Why is high-dimensional space problematic?  
**A:** Data becomes exponentially sparse.

---

### Card 17
**Q:** Why does nearest neighbor degrade in high dimensions?  
**A:** Distances become similar; irrelevant features dominate.

---

### Card 18
**Q:** What practical phenomenon rescues us from dimensional curse?  
**A:** Real-world data lies on low-dimensional manifolds.

---

## SECTION 6 — Theory vs Practice

### Card 19
**Q:** What do theoretical sample complexity bounds guarantee?  
**A:** Eventual performance with enough data — not practical performance.

---

### Card 20
**Q:** Why are asymptotic guarantees misleading in practice?  
**A:** We never operate in infinite-data regimes.

---

## SECTION 7 — Feature Engineering

### Card 21
**Q:** What dominates ML project time?  
**A:** Feature engineering and representation design.

---

### Card 22
**Q:** Why is feature engineering difficult?  
**A:** It is domain-specific, creative, and iterative.

---

### Card 23
**Q:** What usually matters more: algorithm choice or representation?  
**A:** Representation.

---

## SECTION 8 — Data vs Algorithms

### Card 24
**Q:** Which is usually better: more data or a smarter algorithm?  
**A:** More data.

---

### Card 25
**Q:** Why do simple models often outperform complex ones?  
**A:** They have lower variance and are more stable.

---

## SECTION 9 — Ensembles

### Card 26
**Q:** Why do ensembles work?  
**A:** They reduce variance without heavily increasing bias.

---

### Card 27
**Q:** Name three ensemble methods.  
**A:** Bagging, Boosting, Stacking.

---

## SECTION 10 — Simplicity

### Card 28
**Q:** Does Occam’s Razor guarantee better generalization?  
**A:** No.

---

### Card 29
**Q:** Why can complex models generalize well?  
**A:** Because effective capacity and data interaction matter more than parameter count.

---

## SECTION 11 — Representable vs Learnable

### Card 30
**Q:** Why is representability insufficient?  
**A:** Optimization may fail or data may be insufficient.

---

### Card 31
**Q:** What is the real practical question?  
**A:** Can this function be learned with finite data, time, and compute?

---

## SECTION 12 — Correlation vs Causation

### Card 32
**Q:** What does ML primarily learn?  
**A:** Correlations.

---

### Card 33
**Q:** Why is correlation insufficient for intervention?  
**A:** Because changing variables may alter relationships.

---

## SECTION 13 — Meta-Level Lessons

### Card 34
**Q:** What is machine learning fundamentally?  
**A:** Controlled experimentation under uncertainty.

---

### Card 35
**Q:** What causes most beginner mistakes?  
**A:** Model hopping and evaluation leakage.

---

### Card 36
**Q:** What mindset shift does this paper enforce?  
**A:** Discipline over algorithm obsession.

---

# Ultra-Compact Recall Drill (Answer Rapidly)

1. Learning = ?
2. True objective = ?
3. Bias vs variance tradeoff means?
4. Why does high dimension hurt?
5. What beats cleverness?
6. What causes hidden overfitting?
7. What dominates project time?
8. Why ensembles help?
9. Simplicity guarantee? (Yes/No)
10. Correlation implies causation? (Yes/No)

---

# How To Use This File

- Review daily for 7 days.
- Then every 3 days.
- Then weekly.
- Try explaining each answer out loud.
- If you hesitate >5 seconds → mark weak.

Retention comes from struggle, not rereading.
