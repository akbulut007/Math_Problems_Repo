# 🔢 Task 4 — Circular Permutations

## 1️⃣ 7 people around a round table

In circular permutations, rotations are considered identical.  
So we fix one position and arrange the remaining people.

\[
(7 - 1)! = 6! = 720
\]

✅ **Result:** `720`

---

## 2️⃣ Two particular people sit next to each other

Let the two people be **A** and **B**.

Treat them as a single block:
- (A,B) or (B,A)

Now we have:
- 1 block + 5 people = 6 objects

Circular arrangements:
\[
(6 - 1)! = 5! = 120
\]

Internal arrangements of A and B:
\[
2 \text{ ways}
\]

Total:
\[
5! \cdot 2 = 120 \cdot 2 = 240
\]

✅ **Result:** `240`

---

## 3️⃣ Two particular people sit opposite each other

Fix one person to remove rotational symmetry.

The second person must sit in the **exact opposite seat** (only 1 option).

Remaining 5 people:
\[
5! = 120
\]

✅ **Result:** `120`

---

## 📊 Final Summary

| Situation                                         | Formula        | Result |
|--------------------------------------------------|---------------|--------|
| 7 people around a round table                    | (7−1)! = 6!   | 720    |
| Two people sit next to each other                | 5! × 2        | 240    |
| Two people sit opposite each other               | 5!            | 120    |

