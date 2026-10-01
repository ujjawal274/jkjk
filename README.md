# 🧠 SQL Practice — Q1 to Q5 Revision

> 🎯 SQL Query Logic & Analytical Thinking Practice

![Score](https://img.shields.io/badge/Score-44%2F50-00C853?style=for-the-badge)
![Accuracy](https://img.shields.io/badge/Accuracy-88%25-2962FF?style=for-the-badge)
![Questions](https://img.shields.io/badge/Questions-5-7C4DFF?style=for-the-badge)
![Difficulty](https://img.shields.io/badge/Difficulty-Extreme-FF1744?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-00BFA5?style=for-the-badge)

---

## 📊 Overall Result

| Metric | Result |
|--------|--------|
| Total Questions | 5 |
| Total Marks | 50 |
| Score | 44/50 |
| Accuracy | 88% |
| Difficulty | Extreme |
| Overall Performance | Strong |

---

## 🏆 Skill Badges

![WHERE](https://img.shields.io/badge/WHERE-Strong-00897B?style=for-the-badge)
![GROUP BY](https://img.shields.io/badge/GROUP%20BY-Strong-5E35B1?style=for-the-badge)
![HAVING](https://img.shields.io/badge/HAVING-Strong-D81B60?style=for-the-badge)
![AGGREGATE](https://img.shields.io/badge/Aggregate%20Functions-Strong-3949AB?style=for-the-badge)
![OUTPUT](https://img.shields.io/badge/Output%20Prediction-Excellent-43A047?style=for-the-badge)
![QUERY](https://img.shields.io/badge/Query%20Building-Strong-8E24AA?style=for-the-badge)
![INTERVIEW](https://img.shields.io/badge/Interview%20Logic-In%20Progress-F9A825?style=for-the-badge)

---

## 📚 Topics Covered

- SELECT
- WHERE
- AND
- OR
- NOT
- BETWEEN
- GROUP BY
- HAVING
- COUNT()
- SUM()
- AVG()
- MIN()
- MAX()
- ORDER BY

> 🚫 JOIN was intentionally excluded from this practice set.

---

## 🎯 Question Types

- 🔍 Error Finding
- 🎯 Output Prediction
- 📝 Exam-Level SQL
- 💼 Interview-Level SQL
- 📈 Real Data Analyst Tasks

---

## 🧠 Core Concepts Revised

GROUP BY
Creates groups based on a column.
GROUP BY department
Aggregate Functions
Calculate values from rows/groups.
COUNT(*)
SUM(salary)
AVG(salary)
MIN(salary)
MAX(salary)
HAVING
Filters groups after grouping.
HAVING COUNT(*) >= 2
or
HAVING AVG(salary) > 55000
ORDER BY
Sorts the final result.
ORDER BY average_salary DESC
🔄 SQL Logical Flow
FROM
  ↓
WHERE
  ↓
GROUP BY
  ↓
AGGREGATE CALCULATION
  ↓
HAVING
  ↓
SELECT
  ↓
ORDER BY
  ↓
FINAL OUTPUT
⚠️ Important Mistakes to Avoid
1. At least vs maximum
At least 2 → >= 2
At most 2  → <= 2
2. WHERE vs HAVING
WHERE  → Row-level filtering
HAVING → Group-level filtering
3. Aggregate with HAVING
Prefer:
HAVING AVG(salary) > 55000
instead of relying on a SELECT alias:
HAVING average_salary > 55000
4. COUNT() with GROUP BY
After:
GROUP BY department
this:
COUNT(*)
counts rows inside each department group, not automatically the entire table.
📈 Performance Summary
Concept Understanding     █████████░  Strong
Query Building            █████████░  Strong
Output Prediction         ██████████  Excellent
Aggregate Functions       █████████░  Strong
WHERE / HAVING Logic      █████████░  Strong
Accuracy                   ████████░░  88%
💪 Strong Areas
WHERE vs HAVING
GROUP BY + Aggregate Functions
COUNT(), SUM(), AVG()
MIN(), MAX()
Complex filtering conditions
Group-level conditions
Query construction
Output prediction
🔧 Improvement Areas
>= vs <= logical traps
Aggregate alias usage
Final output calculation
Small SQL syntax errors
Alias spelling/accuracy
🏅 Final Achievement
� � �
🏆 FINAL SCORE
44 / 50 — 88%
🧠 Goal: Understand the logic behind SQL queries, not just memorize syntax.
🚀 Revision Rule
READ THE QUESTION
       ↓
IDENTIFY ROW CONDITIONS
       ↓
APPLY WHERE
       ↓
CREATE GROUPS
       ↓
CALCULATE AGGREGATES
       ↓
APPLY HAVING
       ↓
SORT WITH ORDER BY
       ↓
PREDICT FINAL OUTPUT
📌 Practice Status
Q1–Q5 Revision: ✅ COMPLETED
Score: 44/50
Accuracy: 88%
Difficulty: Extreme
Overall Level: Strong SQL Foundation

### WHERE

Filters individual rows.

`sql
WHERE salary > 50000
----
