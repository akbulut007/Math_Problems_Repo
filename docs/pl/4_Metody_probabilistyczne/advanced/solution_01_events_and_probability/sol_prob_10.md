# Task 10 — Buffon's Needle

# Problem

In Buffon’s needle experiment:

• the needle length is L  
• the distance between two parallel lines is d  
• L ≤ d  

Let:

• X — distance from the center of the needle to the nearest line  
• θ — angle between the needle and the lines  

Assume:

• X is uniform on [0, d/2]  
• θ is uniform on [0, π/2]

Find the probabilities of the following events:

• A — the needle intersects a line  
• B — the needle does not intersect a line  
• C — θ < π/6  
• D — X < d/4  
• E — the needle intersects a line and θ > π/4

---

# Step 1 — Condition for intersection

The needle intersects a line when the vertical reach of half of the needle is at least X.

So the condition is:

X ≤ (L/2) sin θ

This is the main condition in Buffon’s needle experiment.

---

# Step 2 — Event A

A = the needle intersects a line.

The known probability formula is:

P(A) = 2L / (dπ)

---

# Step 3 — Event B

B = the needle does not intersect a line.

This is the complement of A.

So:

P(B) = 1 - P(A)

P(B) = 1 - 2L / (dπ)

---

# Step 4 — Event C

C = θ < π/6

Since θ is uniform on [0, π/2], we compare lengths of intervals:

P(C) = (π/6) / (π/2) = 1/3

---

# Step 5 — Event D

D = X < d/4

Since X is uniform on [0, d/2], we compare lengths of intervals:

P(D) = (d/4) / (d/2) = 1/2

---

# Step 6 — Event E

E = the needle intersects a line and θ > π/4

The result is:

P(E) = L√2 / (dπ)

---

# Final Result

P(A) = 2L / (dπ)  
P(B) = 1 - 2L / (dπ)  
P(C) = 1/3  
P(D) = 1/2  
P(E) = L√2 / (dπ)

---

# Quick intuition

```text
parallel lines
-------------------------
-------------------------
-------------------------

the needle crosses a line
when half of its height
is large enough to reach the line

condition:

X <= (L/2) sin(theta)
```
