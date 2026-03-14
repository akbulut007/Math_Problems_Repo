# Task 10 — Urn Models

An urn contains

- 5 red balls
- 4 blue balls
- 3 green balls

1. Three balls are drawn without replacement. How many samples are possible if order is ignored?  
2. How many samples contain exactly two red balls?  
3. Three balls are drawn and the order of colors is recorded. How many outcomes are possible?  
4. How many outcomes contain exactly two red balls?

---

# Step 1 — Three balls are drawn without replacement, order is ignored

Since only the colors are recorded and order is ignored, a sample is determined only by the color counts.

We need all possible color combinations of 3 balls using

R = red  
B = blue  
G = green

Possible samples

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

All of these are possible because the urn contains enough balls of each color.

Number of samples

10

---

# Step 2 — Samples containing exactly two red balls

We want samples of size 3 with exactly two red balls.

So the third ball must be either

B or G

Possible samples

{R,R,B}  
{R,R,G}

Number of samples

2

---

# Step 3 — Three balls are drawn and the order of colors is recorded

Now order matters.

We count all color sequences of length 3 that are possible.

Possible outcomes

RRR  
RRB  
RRG  
RBR  
RBB  
RBG  
RGR  
RGB  
RGG  

BRR  
BRB  
BRG  
BBR  
BBB  
BBG  
BGR  
BGB  
BGG  

GRR  
GRB  
GRG  
GBR  
GBB  
GBG  
GGR  
GGB  
GGG

Since the urn has at least 3 red, at least 3 green, and at least 3 blue is not needed except for BBB which is possible because there are 4 blue balls, all these sequences are valid.

Number of outcomes

3^3 = 27

---

# Step 4 — Outcomes containing exactly two red balls

We want sequences of length 3 with exactly two red balls.

First choose the position of the non-red ball.

This can be done in

3 ways

The non-red ball can be

B or G

So it has

2 choices

Number of outcomes

3 · 2 = 6

Possible outcomes

RRB  
RBR  
BRR  
RRG  
RGR  
GRR

---

## Final Result

| Situation | Result |
|-----------|--------|
| 3 balls drawn, order ignored | 10 |
| Samples with exactly 2 red balls | 2 |
| 3 balls drawn, order of colors recorded | 27 |
| Outcomes with exactly 2 red balls | 6 |
