# Task 11 — Modeling Outcomes

In combinatorial and probabilistic problems, the number of possible outcomes depends on how the results of an experiment are recorded.

The same physical experiment may lead to different counting models depending on whether

- objects are treated as distinguishable or indistinguishable
- order is recorded or ignored
- positions are treated as distinct places

---

# Step 1 — Distinguishable vs Indistinguishable Objects

A box contains

- 4 red balls
- 4 blue balls
- 3 green balls

Thus there are 11 balls in total.

## 1. Linear arrangements of all 11 balls if balls of the same color are indistinguishable

We arrange all 11 balls in a line.

Balls of the same color are treated as identical.

So we use permutations with repeated elements.

Number of arrangements

11! / (4! · 4! · 3!)

= 11550

---

## 2. Arrangements if every ball is individually labeled

Now every ball is different, for example

R1, R2, R3, R4, B1, B2, B3, B4, G1, G2, G3

So all 11 objects are distinguishable.

We arrange all 11 objects in a line.

Number of arrangements

11!

= 39916800

---

## 3. Why are the answers different?

In the first case, balls of the same color are identical, so swapping two red balls does not create a new arrangement.

In the second case, every ball is labeled, so swapping R1 and R2 creates a different arrangement.

That is why the second number is much larger.

---

# Step 2 — Recording Order vs Ignoring Order

Three balls are drawn without replacement from the same box.

## 1. Outcomes if only the set of colors is recorded

Now only the colors matter and order is ignored.

Possible outcomes are determined only by color composition.

Possible outcomes

{R,R,R}
{R,R,B}
{R,R,G}
{R,B,B}
{R,B,G}
{R,G,G}
{B,B,B}
{B,B,G}
{B,G,G}
{G,G,G}

All of these are possible because the box contains enough balls of each color.

Number of outcomes

10

---

## 2. Outcomes if the sequence of colors is recorded

Now order matters.

Each of the 3 positions can be

R, B, or G

All color sequences of length 3 are possible here because the box contains at least 3 balls of each needed color whenever a color repeats up to 3 times.

Number of outcomes

3^3

= 27

---

## 3. Why does recording the order change the counting model?

If order is ignored, outcomes like

RBG, BRG, GBR

all represent the same result because only the chosen colors matter.

If order is recorded, these become different outcomes because the sequence is different.

So ignoring order gives an unordered color multiset, while recording order gives a sequence.

---

# Step 3 — PIN Code vs Number

A security system uses 4-digit PIN codes consisting of digits from 0 to 9.

## 1. Number of different PIN codes if repetition is allowed

A PIN code has 4 positions.

Each position can be any digit from 0 to 9.

Repetition is allowed.

Number of PIN codes

10^4

= 10000

---

## 2. Number of 4-digit numbers

A 4-digit number cannot begin with 0.

So

- first digit: 9 choices
- second digit: 10 choices
- third digit: 10 choices
- fourth digit: 10 choices

Number of 4-digit numbers

9 · 10 · 10 · 10

= 9000

---

## 3. Why are a PIN code and a 4-digit number counted differently?

A PIN code is a sequence of symbols, so leading zero is allowed.

Example

0123

is a valid PIN code.

But a 4-digit number cannot start with 0, so

0123

is not a 4-digit number.

That is why PIN codes have 10000 possibilities, while 4-digit numbers have only 9000.

---

## 4. Why must 1234 and 4321 be treated as different outcomes?

A PIN code records digits in positions.

So the first, second, third, and fourth places are distinct.

Even though the same digits appear, the order is different.

Therefore

1234 ≠ 4321

because they are different sequences.

---

## Final Result

| Situation | Result |
|-----------|--------|
| 11 balls arranged, same colors indistinguishable | 11! / (4! · 4! · 3!) = 11550 |
| 11 labeled balls arranged | 11! = 39916800 |
| 3 balls drawn, only set of colors recorded | 10 |
| 3 balls drawn, sequence of colors recorded | 27 |
| 4-digit PIN codes | 10^4 = 10000 |
| 4-digit numbers | 9 · 10^3 = 9000 |
