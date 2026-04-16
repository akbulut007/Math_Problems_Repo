# 🌦️ Problem 3 — Weather (7 Days × 3 States)

## 🧪 Sample Space

Each day of the week can take one of the following states:

| Symbol | Meaning  |
|--------|----------|
| S      | Sunny ☀️ |
| C      | Cloudy ☁️ |
| R      | Rainy 🌧️ |

The week consists of:

| Day       |
|-----------|
| Monday    |
| Tuesday   |
| Wednesday |
| Thursday  |
| Friday    |
| Saturday  |
| Sunday    |

---

## 📌 Part A — Events

### 1. Monday is sunny

| Condition |
|-----------|
| Monday = S |

---

### 2. The weekend (Saturday and Sunday) is rainy

| Condition |
|-----------|
| Saturday = R |
| Sunday = R   |

---

### 3. It rains on Wednesday or Friday

| Condition |
|-----------|
| Wednesday = R OR Friday = R |

---

### 4. There is no rainy day during the week

| Condition |
|-----------|
| No day has state R |
| All days ∈ {S, C} |

---

### 5. Thursday is not sunny

| Condition |
|-----------|
| Thursday ∈ {C, R} |

---

## 🧠 Part B — Interpretation

### Case 1

| Condition |
|-----------|
| Saturday = S |
| Sunday = S   |

**Interpretation:**  
👉 Saturday and Sunday are sunny.

---

### Case 2

| Condition |
|-----------|
| Rainy (R) is excluded for all days |

**Interpretation:**  
👉 There are no rainy days during the week.

---

## ✅ Final Summary

| Event Description                      | Condition |
|--------------------------------------|----------|
| Monday is sunny                      | Monday = S |
| Weekend is rainy                     | Saturday = R, Sunday = R |
| Rain on Wednesday or Friday          | Wednesday = R OR Friday = R |
| No rainy days                        | All days ∈ {S, C} |
| Thursday is not sunny                | Thursday ∈ {C, R} |

---
