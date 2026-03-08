# Task 7 — Dice Probabilities

# Problem

A fair die is rolled.

Find the probabilities of the following events.

For one roll:

• A₁ — the result is even  
• B₁ — the result is greater than 4  
• C₁ — the result is at most 3  

For two rolls:

• A₂ — the sum is 7  
• B₂ — both results are the same  
• C₂ — the sum is at least 10  

For three rolls:

• A₃ — the sum is 10  
• B₃ — exactly two rolls give the same number  
• C₃ — two twos and one three occur

---

# Step 1 — One die roll

Sample space:

Ω₁ = {1, 2, 3, 4, 5, 6}

Number of outcomes:

|Ω₁| = 6

### Event A₁ — even result

Possible outcomes:

2  
4  
6

P(A₁) = 3/6 = 1/2

### Event B₁ — result greater than 4

Possible outcomes:

5  
6

P(B₁) = 2/6 = 1/3

### Event C₁ — result at most 3

Possible outcomes:

1  
2  
3

P(C₁) = 3/6 = 1/2

---

# Step 2 — Two die rolls

Sample space:

Ω₂ = {(i,j) : i,j ∈ {1,2,3,4,5,6}}

Number of outcomes:

|Ω₂| = 36

### Event A₂ — sum is 7

Possible outcomes:

(1,6)  
(2,5)  
(3,4)  
(4,3)  
(5,2)  
(6,1)

P(A₂) = 6/36 = 1/6

### Event B₂ — same result

Possible outcomes:

(1,1)  
(2,2)  
(3,3)  
(4,4)  
(5,5)  
(6,6)

P(B₂) = 6/36 = 1/6

### Event C₂ — sum at least 10

Possible sums are 10, 11, 12.

Possible outcomes:

(4,6)  
(5,5)  
(6,4)  
(5,6)  
(6,5)  
(6,6)

P(C₂) = 6/36 = 1/6

---

# Step 3 — Three die rolls

Sample space:

Ω₃ = {(i,j,k) : i,j,k ∈ {1,2,3,4,5,6}}

Number of outcomes:

|Ω₃| = 216

### Event A₃ — sum is 10

The number of outcomes with sum 10 is 27.

P(A₃) = 27/216 = 1/8

### Event B₃ — exactly two equal numbers

The number of such outcomes is 90.

P(B₃) = 90/216 = 5/12

### Event C₃ — two twos and one three

Possible outcomes:

(2,2,3)  
(2,3,2)  
(3,2,2)

P(C₃) = 3/216 = 1/72

---

# Final Result

P(A₁) = 1/2  
P(B₁) = 1/3  
P(C₁) = 1/2  

P(A₂) = 1/6  
P(B₂) = 1/6  
P(C₂) = 1/6  

P(A₃) = 1/8  
P(B₃) = 5/12  
P(C₃) = 1/72

---

# Quick intuition

```text
1 roll
2, 4, 6 -> even

2 rolls
sum 7 -> 6 pairs
same result -> 6 pairs

3 rolls
sum 10 -> count all triples
two twos and one three -> 3 orders
```
