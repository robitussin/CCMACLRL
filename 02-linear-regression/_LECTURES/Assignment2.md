# Linear Regression Activity: Predicting Exam Scores

We want to predict a student’s **Exam Score ($y$)** based on the number of **Hours Studied ($x$)**.

---

## Data

| Student | Hours Studied ($x$) | Exam Score ($y$) |
| ------- | ------------------- | ---------------- |
| 1       | 1                   | 52               |
| 2       | 2                   | 57               |
| 3       | 3                   | 61               |
| 4       | 4                   | 65               |
| 5       | 5                   | 70               |

---

## Task

We want to fit a **linear regression line** of the form:

$$
y = mx + b
$$

A new student studied **6 hours**. We want to predict the **Exam Score** using the regression equation.

---

### 1. Fill in the table (14 points)

- Compute **$x^2$** for each student.
- Compute **$xy$** for each student.
- Find the totals: **$Σx$**, **$Σy$**, **$Σx^2$**, and **$Σxy$**.

| Student | Hours Studied ($x$) | Exam Score ($y$) | $xy$          | $x^2$          |
| ------- | ------------------- | ---------------- | ------------- | -------------- |
| 1       | 1                   | 52               | **?**         | **?**          |
| 2       | 2                   | 57               | **?**         | **?**          |
| 3       | 3                   | 61               | **?**         | **?**          |
| 4       | 4                   | 65               | **?**         | **?**          |
| 5       | 5                   | 70               | **?**         | **?**          |
|         | $Σx$ = **?**        | $Σx$ = **?**     | $Σxy$ = **?** | $Σx^2$ = **?** |

---

## 2. Compute the Slope $m$ (5 points)

$$
m = \frac{n(\sum xy) - (\sum x)(\sum y)}{n(\sum x^2) - (\sum x)^2}
$$

$$
m = ?
$$

---

## 3: Compute the Intercept $b$ (5 points)

$$
b = \frac{\sum y - m \sum x}{n}
$$

$$
b = ?
$$

---

## 4. Regression Equation (5 points)

Write the regression line:

$$
y = mx + b
$$

$$
y = ?
$$

---

## 5. Draw the regression line using a scatter plot (10 points)

- Calculate $y_{predict}$ for each data points
- Draw a regression line using $y_{predict}$
- Use a circle 🔵 for all data points
- Use a red line for the regression line

| Student | Hours Studied ($x$) | Exam Score ($y$) | Predicted Exam Score ($y_{predict}$) |
| ------- | ------------------- | ---------------- | ------------------------------------ |
| 1       | 1                   | 52               | ?                                    |
| 2       | 2                   | 57               | ?                                    |
| 3       | 3                   | 61               | ?                                    |
| 4       | 4                   | 65               | ?                                    |
| 5       | 5                   | 70               | ?                                    |

---

## 6. Calculate the Sum of Squared Errors (20 points)

$$
SSE = \sum (y*i - y*{predict})^2
$$

| Student | Hours Studied ($x$) | Exam Score ($y$) | Predicted Exam Score ($y_{predict}$) | $y_i-y_{predict}$ | $(y_i-y_{predict})^2$ |
| ------- | ------------------- | ---------------- | ------------------------------------ | ----------------- | --------------------- |
| 1       | 1                   | 52               | ?                                    | ?                 | ?                     |
| 2       | 2                   | 57               | ?                                    | ?                 | ?                     |
| 3       | 3                   | 61               | ?                                    | ?                 | ?                     |
| 4       | 4                   | 65               | ?                                    | ?                 | ?                     |
| 5       | 5                   | 70               | ?                                    | ?                 | ?                     |
|         |                     |                  |                                      |                   | $SSE$ = ?             |

---

## 7. Calculate the Sum of Squared Total (20 points)

- Get $\bar{y}$ using this formula :

$$
\bar{y} = \frac{\sum y_i}{n}
$$

- Get $SST$ using this formula :

$$
SST = \sum (y_i - \bar{y})^2
$$

| Student | Hours Studied ($x$) | Exam Score ($y$) | Mean ($\bar{y}$) | $y_i-\bar{y}$ | $(y_i-\bar{y})^2$ |
| ------- | ------------------- | ---------------- | ---------------- | ------------- | ----------------- |
| 1       | 1                   | 52               | ?                | ?             | ?                 |
| 2       | 2                   | 57               | ?                | ?             | ?                 |
| 3       | 3                   | 61               | ?                | ?             | ?                 |
| 4       | 4                   | 65               | ?                | ?             | ?                 |
| 5       | 5                   | 70               | ?                | ?             | ?                 |
|         |                     |                  |                  |               | $SST$ = ?         |

---

## 8. Compute $R^2$ (20 points)

- Get $R^2$ using this formula :

$$
R^2 = 1 - \frac{SSE}{SST}
$$

$$
R^2 = ?
$$

---

## 9. Prediction (1 point)

Use your equation to predict the exam score for a student who studied **6 hours**.

$$
y = m(6) + b
$$

$$
y = ?
$$
