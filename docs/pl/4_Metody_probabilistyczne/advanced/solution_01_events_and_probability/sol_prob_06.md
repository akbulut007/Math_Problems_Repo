# Task 6 — Coin Toss Probabilities

# Problem

A fair coin is tossed.

Find the probabilities of the following events.

For one toss:

• A₁ — the result is heads  
• B₁ — the result is tails  

For two tosses:

• A₂ — exactly one head occurs  
• B₂ — at least one head occurs  
• C₂ — both tosses give the same result  

For three tosses:

• A₃ — exactly two heads occur  
• B₃ — at least one tail occurs  
• C₃ — all three tosses give the same result

---

# Step 1 — One coin toss

Sample space:

Ω₁ = {H, T}

Number of outcomes:

|Ω₁| = 2

### Event A₁ — heads

A₁ = {H}

P(A₁) = 1/2

### Event B₁ — tails

B₁ = {T}

P(B₁) = 1/2

---

# Step 2 — Two coin tosses

Sample space:

Ω₂ = {(H,H), (H,T), (T,H), (T,T)}

Number of outcomes:

|Ω₂| = 4

### Event A₂ — exactly one head

Possible outcomes:

(H,T)  
(T,H)

P(A₂) = 2/4 = 1/2

### Event B₂ — at least one head

Possible outcomes:

(H,H)  
(H,T)  
(T,H)

P(B₂) = 3/4

### Event C₂ — same result

Possible outcomes:

(H,H)  
(T,T)

P(C₂) = 2/4 = 1/2

---

# Step 3 — Three coin tosses

Sample space:

Ω₃ = {HHH, HHT, HTH, HTT, THH, THT, TTH, TTT}

Number of outcomes:

|Ω₃| = 8

### Event A₃ — exactly two heads

Possible outcomes:

HHT  
HTH  
THH

P(A₃) = 3/8

### Event B₃ — at least one tail

All outcomes except HHH.

P(B₃) = 7/8

### Event C₃ — all tosses equal

Possible outcomes:

HHH  
TTT

P(C₃) = 2/8 = 1/4

---

# Final Result

P(A₁) = 1/2  
P(B₁) = 1/2  

P(A₂) = 1/2  
P(B₂) = 3/4  
P(C₂) = 1/2  

P(A₃) = 3/8  
P(B₃) = 7/8  
P(C₃) = 1/4

---

# Quick intuition

```text
2 tosses

HH
HT
TH
TT

exactly one head -> HT, TH

same result -> HH, TT
```
