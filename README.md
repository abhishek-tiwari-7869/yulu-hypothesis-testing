# Yulu Hypothesis Testing

This project performs hypothesis testing on Yulu bike usage data to understand user behavior.

---

##  Objective
To compare average trip durations on **weekdays vs weekends** using statistical hypothesis testing.

---

##  Hypothesis

- **Null Hypothesis (H₀):** There is no difference in the mean trip duration between weekdays and weekends.
- **Alternative Hypothesis (H₁):** There is a significant difference in the mean trip duration between weekdays and weekends.

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- Matplotlib
- Seaborn
- SciPy (for t-test)

---

##  Methodology

1. Data cleaning and preprocessing
2. Grouping data by weekdays and weekends
3. Performing independent two-sample **t-test**
4. Interpreting p-values and test statistics

---

##  Result & Conclusion

- **p-value < 0.05**, hence we **reject the null hypothesis**.
- There is a statistically significant difference in Yulu ride durations between weekdays and weekends.
- Useful for optimizing fleet distribution and pricing strategy.

---

##  Files

- `yulu_abhi.ipynb`: Jupyter notebook containing full analysis and visualization.

---

##  Future Scope

- Perform similar analysis on distance covered, user categories (student vs working), or time of day.
- Use non-parametric tests if data is not normally distributed.

