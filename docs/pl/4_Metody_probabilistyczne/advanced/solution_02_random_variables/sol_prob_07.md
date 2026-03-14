# Task 7 — k-Permutations (Ordered Selections Without Repetition)

1. In how many ways can the first three places be assigned among 12 runners?  
2. How many 4-digit numbers with distinct digits can be formed from the digits 1–9?  
3. How many of these numbers are divisible by 5?

---

# Step 1 — Assigning the first three places among 12 runners

We assign

- 1st place
- 2nd place
- 3rd place

among 12 runners.

Only 3 runners are chosen, and order matters.

So we use k-permutations.

Number of ways

P(12,3)

= 12 · 11 · 10

= 1320

---

# Step 2 — Forming 4-digit numbers with distinct digits from 1–9

Available digits

1, 2, 3, 4, 5, 6, 7, 8, 9

We form a 4-digit number.

Digits must be distinct, so repetition is not allowed.

Order matters because different orders give different numbers.

For the first digit, we have 9 choices.  
For the second digit, we have 8 choices.  
For the third digit, we have 7 choices.  
For the fourth digit, we have 6 choices.

Number of such numbers

9 · 8 · 7 · 6

= 3024

---

# Step 3 — 4-digit numbers with distinct digits that are divisible by 5

A number is divisible by 5 if its last digit is 5.

Since the allowed digits are 1–9, the last digit must be

5

So we fix the last digit as 5.

Now we choose the first three digits from the remaining 8 digits

1, 2, 3, 4, 6, 7, 8, 9

For the first digit, we have 8 choices.  
For the second digit, we have 7 choices.  
For the third digit, we have 6 choices.

Number of such numbers

8 · 7 · 6

= 336

---

## Final Result

| Situation | Result |
|-----------|--------|
| First three places among 12 runners | P(12,3) = 1320 |
| 4-digit numbers with distinct digits from 1–9 | 9 · 8 · 7 · 6 = 3024 |
| Such numbers divisible by 5 | 8 · 7 · 6 = 336 |
