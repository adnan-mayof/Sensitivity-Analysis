# Step 19 — Conduct Sensitivity Analysis

## Maya’s Evidence Synthesis Journey

### The Story

Maya has completed the meta-analysis and examined heterogeneity and moderators.

She now has 22 studies contributing to her quantitative synthesis.

Her main random-effects meta-analysis produced:

> **Pooled Hedges’ g = 0.64, 95% CI [0.52, 0.76]**

She also found moderate heterogeneity:

> **I² = 58%**

Then, in her moderator and meta-regression analyses, she explored whether characteristics such as intervention duration, AI function, and learner level were associated with differences in effect sizes.

Maya feels ready to report the findings.

But her mentor stops her.

**Mentor:** “Before you finalize the results, there is one more important question.”

**Maya:** “What question?”

**Mentor:** “How stable are your findings?”

Maya looks confused.

**Maya:** “I already calculated the pooled effect. Why would I need to analyze it again?”

**Mentor:** “Because your conclusion should not depend entirely on one particular study or one analytical decision. We need to see whether reasonable changes to the analysis lead to substantially different conclusions.”

**Maya:** “So we're checking how sensitive the findings are?”

**Mentor:** “Exactly. This is called a **sensitivity analysis**.”

---

# 1. What Is Sensitivity Analysis?

Sensitivity analysis examines whether the main findings change when reasonable alternative decisions, assumptions, or subsets of studies are used.

The basic question is:

> **Would I reach a similar conclusion if I changed an important analytical decision or removed studies that may have a strong influence on the result?**

For Maya's review, sensitivity analysis can help determine whether the pooled effect of AI-powered learning technologies is reasonably robust.

### Simple mental model

Think of the primary meta-analysis as your **main answer**.

Sensitivity analysis asks:

> **“Does the answer remain similar when I stress-test it?”**

```text
                    PRIMARY ANALYSIS
                          │
                          ▼
                 Pooled effect = 0.64
                          │
             ┌────────────┼────────────┐
             ▼            ▼            ▼
       Remove           Change       Alternative
      influential       analytical      reasonable
        studies          decision       assumption
             │            │            │
             └────────────┼────────────┘
                          ▼
                 Compare the results
                          │
              ┌───────────┴───────────┐
              ▼                       ▼
         Similar results          Substantial
                                  differences
              │                       │
              ▼                       ▼
       Greater confidence       Investigate why
       in robustness           conclusions differ
```

---

# 2. Why Does Sensitivity Analysis Matter?

A pooled effect can sometimes be strongly influenced by:

* one or a few studies
* studies with very large effects
* studies with very small samples
* studies with high risk of bias
* different assumptions about effect-size calculation
* different ways of handling multiple outcomes
* different analysis models
* particular eligibility decisions

Sensitivity analysis does **not** mean changing the analysis until the desired result appears.

Instead, the purpose is to examine whether reasonable alternative approaches materially affect the findings.

---

# 3. Sensitivity Analysis Is Different From the Primary Analysis

Maya's primary analysis uses the prespecified approach from her protocol.

For example:

> Random-effects meta-analysis of the 22 quantitatively eligible studies using Hedges' g.

Sensitivity analyses are additional analyses used to examine robustness.

### Think of it this way

| Analysis             | Purpose                                                                      |
| -------------------- | ---------------------------------------------------------------------------- |
| Primary analysis     | Main planned answer to the research question                                 |
| Sensitivity analysis | Tests how stable that answer is                                              |
| Moderator analysis   | Examines whether study characteristics are associated with different effects |
| Meta-regression      | Models study-level relationships between moderators and effect sizes         |

These analyses answer different questions.

---

# 4. First Sensitivity Analysis: Remove Influential Studies

Maya examines whether particular studies have a strong influence on the pooled estimate.

Suppose her primary analysis is:

| Analysis         | Studies | Hedges' g |       95% CI |
| ---------------- | ------: | --------: | -----------: |
| Primary analysis |      22 |      0.64 | [0.52, 0.76] |

She identifies two studies that appear particularly influential.

She performs the analysis again after removing them.

| Analysis                     | Studies | Hedges' g |       95% CI |
| ---------------------------- | ------: | --------: | -----------: |
| Primary analysis             |      22 |      0.64 | [0.52, 0.76] |
| Remove influential Study 008 |      21 |      0.61 | [0.50, 0.73] |
| Remove influential Study 016 |      21 |      0.62 | [0.51, 0.74] |
| Remove both                  |      20 |      0.59 | [0.47, 0.71] |

Maya notices that the pooled effect decreases somewhat.

But the overall conclusion remains similar.

**Mentor:** “What do you think?”

**Maya:** “The estimate changes, but it remains positive and reasonably similar to the primary result.”

**Mentor:** “Good. That suggests the overall conclusion is not entirely dependent on those studies.”

---

# 5. Leave-One-Out Sensitivity Analysis

Another useful approach is **leave-one-out analysis**.

Maya removes one study at a time and recalculates the pooled effect.

For 22 studies, she performs 22 analyses:

```text
Remove Study 1  → pooled effect
Remove Study 2  → pooled effect
Remove Study 3  → pooled effect
        ...
Remove Study 22 → pooled effect
```

She can then examine the range of estimates.

For example:

| Analysis                       | Pooled Hedges' g |
| ------------------------------ | ---------------: |
| Primary                        |             0.64 |
| Lowest leave-one-out estimate  |             0.58 |
| Highest leave-one-out estimate |             0.69 |

This tells Maya that no single study appears to completely determine the pooled estimate.

### Important point

Leave-one-out analysis does **not** mean that every study should be removed permanently.

The studies remain part of the evidence base unless there is a methodological reason to exclude them.

The purpose is to understand their influence.

---

# 6. Sensitivity Analysis Based on Risk of Bias

Maya also considers risk of bias.

Recall that her review initially had:

| Risk-of-bias judgment | Number of studies |
| --------------------- | ----------------: |
| Low                   |                82 |
| Some concerns         |                29 |
| High                  |                15 |

Her protocol specified that studies at high risk of bias would not contribute to the **primary synthesis**.

Therefore, those studies were already handled according to the protocol.

But suppose some studies with **some concerns** remain in the quantitative synthesis.

Maya can conduct a sensitivity analysis that excludes those studies and compares the result with the primary analysis.

For example:

| Analysis                           | Studies | Hedges' g |
| ---------------------------------- | ------: | --------: |
| Primary analysis                   |      22 |      0.64 |
| Exclude studies with some concerns |      17 |      0.67 |

The estimate is similar.

Maya can report that the main conclusion was reasonably stable when the analysis was restricted to studies with lower risk-of-bias concerns.

---

# 7. Sensitivity Analysis Based on Analytical Decisions

Sensitivity analysis does not have to involve removing studies.

Maya may also examine reasonable alternative analytical decisions.

For example:

### Primary analysis

> Random-effects model using Hedges' g.

### Sensitivity analysis

> Alternative reasonable model or effect-size handling specified in the analysis plan.

The purpose is to determine whether the substantive conclusion changes.

However, Maya must have a methodological reason for conducting the alternative analysis.

She should not simply try many different methods and report whichever produces the most favorable result.

---

# 8. What About Multiple Outcomes?

Suppose one study reports:

* achievement
* motivation
* engagement
* knowledge
* skill performance

Maya cannot automatically treat every effect size as an independent study.

That could give that study disproportionate influence.

She therefore needs to follow her prespecified approach for handling dependent or multiple effect sizes.

A sensitivity analysis might examine whether the main conclusion changes under a reasonable alternative handling strategy.

For example:

| Analysis                              | Hedges' g |
| ------------------------------------- | --------: |
| Primary handling of multiple outcomes |      0.64 |
| Alternative prespecified handling     |      0.62 |

Again, Maya compares the results rather than selecting the one she prefers.

---

# 9. Sensitivity Analysis Does Not Mean “Find the Best Result”

Maya asks an important question.

**Maya:** “What if one analysis gives me a larger effect and another gives me a smaller effect? Which one should I report?”

**Mentor:** “You don't choose the result because it looks better.”

**Maya:** “Then what do I do?”

**Mentor:** “Report the primary analysis and explain the sensitivity analyses. The purpose is to understand robustness, not to search for a preferred result.”

This is an important principle.

> **Sensitivity analysis should test reasonable analytical alternatives, not be used to manufacture a preferred conclusion.**

---

# 10. What If the Results Change Substantially?

Suppose Maya obtains:

| Analysis                           | Hedges' g |
| ---------------------------------- | --------: |
| Primary analysis                   |      0.64 |
| Remove influential studies         |      0.31 |
| Exclude studies with some concerns |      0.28 |
| Alternative outcome handling       |      0.25 |

Now the story is different.

The conclusion may be sensitive to particular studies or methodological decisions.

Maya should investigate.

Possible questions include:

* Which studies are driving the difference?
* Why are those studies influential?
* Do they have unusual samples?
* Do they use different interventions?
* Do they have different outcome measures?
* Are they at greater risk of bias?
* Is there an issue with the effect-size calculation?
* Is there substantial methodological diversity?
* Was the primary model appropriate?

A large change does not automatically mean the primary analysis is invalid.

It means Maya needs to understand **why the results change**.

---

# 11. Sensitivity Analysis and Influential Studies

Influence and sensitivity are related but not identical.

### Influence analysis

Asks:

> **Which studies have a strong influence on the model?**

### Sensitivity analysis

Asks:

> **Does the conclusion change when those studies or analytical assumptions are changed?**

Influence diagnostics can therefore help Maya decide which sensitivity analyses are informative.

---

# 12. Sensitivity Analysis and Heterogeneity

Maya also compares heterogeneity.

Suppose:

| Analysis                   | Hedges' g |  I² |
| -------------------------- | --------: | --: |
| Primary                    |      0.64 | 58% |
| Remove influential studies |      0.59 | 44% |

Now Maya sees that the influential studies contributed not only to the pooled effect but also to some of the observed heterogeneity.

This can be useful for interpretation.

However, she should not simply remove studies because they increase heterogeneity.

A study does not become ineligible merely because it produces a different result.

---

# 13. What Should Maya Record?

Every sensitivity analysis should be documented.

A useful table is:

| Analysis      | Change made                    | Studies | Hedges' g | 95% CI       |  I² | Interpretation                                   |
| ------------- | ------------------------------ | ------: | --------: | ------------ | --: | ------------------------------------------------ |
| Primary       | Prespecified model             |      22 |      0.64 | [0.52, 0.76] | 58% | Main analysis                                    |
| Leave-one-out | Remove each study sequentially | 21 each | 0.58–0.69 | —            |   — | No single study changes conclusion substantially |
| Influence     | Remove Study 008               |      21 |      0.61 | [0.50, 0.73] | 52% | Similar conclusion                               |
| Influence     | Remove Study 016               |      21 |      0.62 | [0.51, 0.74] | 54% | Similar conclusion                               |
| Risk of bias  | Restrict to lower-risk studies |      17 |      0.67 | [0.54, 0.80] | 46% | Similar conclusion                               |

This makes the analytical process transparent.

---

# 14. How Maya Interprets the Results

Maya's sensitivity analyses show that:

* the pooled effect remains positive
* the estimate changes somewhat under alternative analyses
* no individual study completely determines the conclusion
* restricting the analysis to lower-risk studies produces a similar estimate
* heterogeneity decreases somewhat after removing influential studies

Therefore, Maya can describe the finding as **reasonably robust to the examined sensitivity analyses**.

She should not say:

> “The results are proven to be robust.”

Instead, she should describe exactly what she tested and what happened.

---

# 15. Sensitivity Analysis Does Not Replace the Primary Analysis

Maya keeps her primary analysis.

The sensitivity analyses provide additional evidence about its stability.

```text
Primary analysis
      │
      ▼
Main conclusion
      │
      ▼
Sensitivity analyses
      │
      ├── Similar conclusion
      │       ↓
      │   Greater confidence
      │   in robustness
      │
      └── Substantial change
              ↓
        Investigate sources
        of instability
```

The primary analysis remains the central analysis unless there is a methodological reason to change it.

---

# 16. Prespecified vs Exploratory Sensitivity Analyses

Maya should distinguish between analyses planned before seeing the results and analyses developed afterward.

### Prespecified

The protocol states:

> “We will conduct a leave-one-out sensitivity analysis and a sensitivity analysis excluding studies with elevated risk-of-bias concerns.”

This is a **prespecified sensitivity analysis**.

### Exploratory

After seeing the results, Maya notices that one study has an unusually large effect and decides to investigate its influence.

That can still be useful.

But she should clearly identify it as an **exploratory analysis** rather than presenting it as if it had been planned from the beginning.

Transparency matters.

---

# 17. A Practical Sensitivity-Analysis Workflow

Maya now has a repeatable process.

```text
Step 1
Run the primary meta-analysis
        ↓
Step 2
Identify potentially influential studies
        ↓
Step 3
Review prespecified sensitivity analyses
        ↓
Step 4
Run each reasonable sensitivity analysis
        ↓
Step 5
Compare pooled effects and uncertainty
        ↓
Step 6
Compare heterogeneity when relevant
        ↓
Step 7
Investigate substantial differences
        ↓
Step 8
Document every analysis
        ↓
Step 9
Report primary + sensitivity results
```

---

# 18. Maya's Final Results Table

After completing her analyses, Maya creates a summary:

| Analysis                        |  k | Hedges' g | 95% CI       |  I² |
| ------------------------------- | -: | --------: | ------------ | --: |
| Primary random-effects model    | 22 |      0.64 | [0.52, 0.76] | 58% |
| Remove Study 008                | 21 |      0.61 | [0.50, 0.73] | 52% |
| Remove Study 016                | 21 |      0.62 | [0.51, 0.74] | 54% |
| Remove both influential studies | 20 |      0.59 | [0.47, 0.71] | 44% |
| Lower-risk studies              | 17 |      0.67 | [0.54, 0.80] | 46% |

Maya looks at the table.

**Maya:** “The estimates move around, but they don't completely change the overall conclusion.”

**Mentor:** “Exactly. Now you have more information about how stable your findings are.”

**Maya:** “So now I can interpret the results?”

**Mentor:** “Almost. First, you need to make sure you understand what all of these findings actually mean.”

Maya opens a new document.

She writes:

> **Step 20 — Interpret the Findings**

---

# 19. Key Takeaways

1. **Sensitivity analysis tests the robustness of findings.**
2. The primary meta-analysis remains the main analysis.
3. Leave-one-out analysis examines the influence of individual studies.
4. Influential-study analyses can show whether particular studies substantially affect the pooled estimate.
5. Risk-of-bias-based sensitivity analyses can examine whether conclusions change when analyses are restricted to studies with fewer methodological concerns.
6. Sensitivity analyses can also examine reasonable alternative analytical decisions.
7. A study should not be removed simply because it produces an unfavorable or different result.
8. Substantial changes between analyses should be investigated and transparently reported.
9. Prespecified and exploratory sensitivity analyses should be distinguished.
10. Sensitivity analysis does not establish that a result is universally robust; it shows how the result behaves under the specific alternative analyses examined.

---

# Assessment

## Question 1

What is the primary purpose of sensitivity analysis?

A. To increase the number of included studies
B. To test how stable the main findings are under reasonable alternative analyses
C. To replace the primary meta-analysis
D. To identify the research gap

## Question 2

Maya's primary analysis produces a pooled Hedges' g of 0.64. What should she do in a sensitivity analysis?

A. Change the model until the effect becomes larger
B. Examine whether reasonable analytical changes materially affect the result
C. Delete studies with small effects
D. Report only the largest effect

## Question 3

What does leave-one-out analysis involve?

A. Removing all studies with high heterogeneity
B. Removing one study at a time and recalculating the analysis
C. Removing all studies with small samples
D. Repeating the literature search

## Question 4

If removing one study changes the pooled effect from 0.64 to 0.20, what should Maya do?

A. Automatically delete the study permanently
B. Ignore the difference
C. Investigate why the study has such a strong influence
D. Report only the 0.20 estimate

## Question 5

Which statement best describes the relationship between influence analysis and sensitivity analysis?

A. They are exactly the same procedure
B. Influence analysis can identify studies whose removal may be useful to examine in sensitivity analyses
C. Sensitivity analysis is only used before the meta-analysis
D. Influence analysis determines study eligibility

## Question 6

Maya removes studies with elevated risk-of-bias concerns as a sensitivity analysis. What is she examining?

A. Whether the conclusion changes when the analysis is restricted to studies with fewer methodological concerns
B. Whether those studies should automatically be deleted from the review
C. Whether risk of bias can be ignored
D. Whether the literature search was comprehensive

## Question 7

What should Maya do if a sensitivity analysis produces a substantially different conclusion?

A. Select whichever result she prefers
B. Hide the sensitivity analysis
C. Investigate the source of the difference and report it transparently
D. Automatically remove all studies involved

## Question 8

Which statement about sensitivity analysis is most appropriate?

A. It should be used to obtain the most favorable result
B. It should test reasonable alternatives with a methodological rationale
C. It should always produce exactly the same result
D. It replaces the primary analysis

## Question 9

Why should Maya distinguish prespecified from exploratory sensitivity analyses?

A. To make clear which analyses were planned before examining the results
B. To increase the pooled effect
C. To reduce the number of studies
D. To eliminate heterogeneity

## Question 10

Maya's primary analysis gives g = 0.64 and a sensitivity analysis gives g = 0.59. What is the most appropriate interpretation?

A. The primary analysis must be discarded
B. The sensitivity analysis proves the original result was invalid
C. The estimate changed, and Maya should consider whether the substantive conclusion remains similar
D. Both results must be averaged

## Question 11

What should Maya do with studies removed temporarily during a leave-one-out analysis?

A. Automatically exclude them from the systematic review
B. Keep them in the evidence base unless there is a separate methodological reason for exclusion
C. Remove them from the protocol
D. Replace them with new studies

## Question 12

Why might Maya compare I² across sensitivity analyses?

A. To determine which study is eligible
B. To see whether the amount of observed heterogeneity changes under the alternative analysis
C. To calculate the sample size
D. To determine the publication year

## Question 13

Which statement best describes a robust finding in the context of sensitivity analysis?

A. A finding that remains reasonably similar across the specific alternative analyses examined
B. A finding that never changes under any possible analysis
C. A finding with the largest effect size
D. A finding based on only one study

## Question 14

Maya notices that a study has a very large effect size. What should she do?

A. Automatically exclude it
B. Investigate its influence and, if appropriate, conduct a justified sensitivity analysis
C. Change its effect size
D. Replace it with the average effect

## Question 15

What should be documented for each sensitivity analysis?

A. Only whether the result was statistically significant
B. The analytical change, studies included, results, and interpretation
C. Only the largest effect size
D. Only the study names

---

# Answer Key

| Question | Answer |
| -------- | ------ |
| 1        | **B**  |
| 2        | **B**  |
| 3        | **B**  |
| 4        | **C**  |
| 5        | **B**  |
| 6        | **A**  |
| 7        | **C**  |
| 8        | **B**  |
| 9        | **A**  |
| 10       | **C**  |
| 11       | **B**  |
| 12       | **B**  |
| 13       | **A**  |
| 14       | **B**  |
| 15       | **B**  |
