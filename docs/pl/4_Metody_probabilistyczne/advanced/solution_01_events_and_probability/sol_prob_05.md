# Task 5 — Weather Observation

# Problem

The weather is observed for 7 days.

Each day can be:

• S — sunny  
• C — cloudy  
• R — rainy

Describe the sample space and determine the number of possible outcomes.

---

# Step 1 — One day

For one day, there are 3 possible weather types:

Ω₁ = {S, C, R}

So the number of outcomes for one day is:

|Ω₁| = 3

---

# Step 2 — Seven days

For 7 days, each day can be:

• S  
• C  
• R

So we multiply 3 by itself 7 times:

|Ω₇| = 3 × 3 × 3 × 3 × 3 × 3 × 3 = 3⁷

---

# Step 3 — Meaning of one outcome

One outcome is one full 7-day weather sequence.

Example:

(S, C, R, S, S, C, R)

This means:

day 1 — sunny  
day 2 — cloudy  
day 3 — rainy  
day 4 — sunny  
day 5 — sunny  
day 6 — cloudy  
day 7 — rainy

---

# Final Result

Sample space:

Ω₇ = {all 7-day sequences made from S, C, R}

Number of outcomes:

|Ω₇| = 3⁷

---

# Quick intuition

```text
1 day  -> 3 possibilities
2 days -> 3 × 3
3 days -> 3 × 3 × 3
...
7 days -> 3^7
```
