## Part 1: My Initial Attempt

### Claim 1

**My Claim:**

The prices of everyday grocery items are increasing over time.

**My Testable Question:**

Did the prices of the four items in the dataset increase over the recorded dates?

**Variables Needed:**

- `date` – To identify when the prices were recorded.
- `item` – To identify the different products.
- `price` – To compare prices over time.
- `city` – To make sure prices are compared within the same city.

**Why I Chose This Question:**

I chose this question because people often say that everyday items are becoming more expensive. I want to investigate whether the recorded prices support this statement.

---

### Claim 2

**My Claim:**

The same grocery products can have different prices in different cities.

**My Testable Question:**

Are the prices of the same products higher in City 2 than in City 1 on the recorded dates?

**Variables Needed:**

- `city` – To identify the two cities.
- `item` – To compare the same products.
- `price` – To identify price differences.
- `date` – To compare prices recorded on the same date.

**Why I Chose This Question:**

I chose this question because the same product may have different prices in different locations. I want to compare the prices in City 1 and City 2 to investigate whether there is a consistent difference.

---

## Part 2: Dataset Predictions

### Dataset Size and Structure

**Number of Rows:** 96

**Number of Columns:** 6

**Number of Distinct Items:** 4

**Number of Distinct Dates:** 12

### Reasoning Behind My Predictions

The dataset contains price records for different products, cities, and dates. I expected the dataset to contain repeated observations because the same products can be recorded on different dates and in different cities.

### Information I Already Knew

The numbers above are the actual dataset counts shared during AI-assisted preparation, not independent predictions made before inspecting the data. ChatGPT helped me understand the meanings of rows, columns, distinct items, and distinct dates. I will verify these numbers using Python in my notebook.

---

## Part 3: Git Commit Record

**Required Commit Message:** `attempt-before-AI`

**Commit Hash:** 0073905
---
