# Task 5 — Combinations

1. A committee of 4 people is chosen from 12 students. How many committees are possible?  
2. How many committees contain a particular student?  
3. How many committees contain at least one of two particular students?  
4. How many committees contain exactly two women if the group consists of 7 men and 5 women?

---

# Step 1 — Choosing a committee of 4 people from 12 students

We choose 4 people from 12.

Order does not matter.

So we use combinations.

Number of committees

C(12,4)

= 12! / (4! · 8!)

= 495

---

# Step 2 — Committees that contain a particular student

Fix the particular student in the committee.

Now we need to choose the remaining 3 people from the other 11 students.

Number of committees

C(11,3)

= 11! / (3! · 8!)

= 165

---

# Step 3 — Committees that contain at least one of two particular students

Let the two particular students be A and B.

We count committees that contain at least one of them.

Case 1: Committee contains A but not B

Choose the remaining 3 members from the other 10 students

C(10,3) = 120

Case 2: Committee contains B but not A

Choose the remaining 3 members from the other 10 students

C(10,3) = 120

Case 3: Committee contains both A and B

Choose the remaining 2 members from the other 10 students

C(10,2) = 45

Total number of committees

C(10,3) + C(10,3) + C(10,2)

= 120 + 120 + 45

= 285

---

# Step 4 — Committees with exactly two women

There are

7 men  
5 women

We want exactly 2 women in a committee of 4.

So we choose

- 2 women from 5
- 2 men from 7

Number of such committees

C(5,2) · C(7,2)

= 10 · 21

= 210

---

## Final Result

| Situation | Result |
|-----------|--------|
| Committee of 4 from 12 students | C(12,4) = 495 |
| Committee containing a particular student | C(11,3) = 165 |
| Committee containing at least one of two particular students | C(10,3) + C(10,3) + C(10,2) = 285 |
| Committee containing exactly two women | C(5,2) · C(7,2) = 210 |
