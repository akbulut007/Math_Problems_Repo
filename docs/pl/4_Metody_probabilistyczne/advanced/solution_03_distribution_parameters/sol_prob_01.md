# 🔢 Task 1 — Binomial Model (Quality Control)

## ✅ Solution

STEP 1 — Describe the random experiment
We check 3 screws one by one.
Each screw can be:
- Good (G)
- Defective (D)

STEP 2 — Determine the sample space (Ω)
All possible outcomes of 3 checks:

Ω = {GGG, GGD, GDG, GDD, DGG, DGD, DDG, DDD}

STEP 3 — Assign probabilities
Let p = probability of defective (D)
Then (1 - p) = probability of good (G)

Now calculate each:

P(GGG) = (1-p)^3  
P(GGD) = (1-p)^2 * p  
P(GDG) = (1-p)^2 * p  
P(GDD) = (1-p) * p^2  
P(DGG) = (1-p)^2 * p  
P(DGD) = (1-p) * p^2  
P(DDG) = (1-p) * p^2  
P(DDD) = p^3  

STEP 4 — Define success
Success = finding a defective screw

## 📊 Final Summary

- Each "D" = success
- Each "G" = failure
