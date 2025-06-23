# AB-Test-Analysis
This project performs a realistic A/B test analysis using simulated user-level data to evaluate whether a new product version (Group B) improves conversion and revenue over the existing version (Group A).
---

## 📄 Dataset Description

Each row represents one user, assigned to either Group A or B.

| Column     | Description                                |
|------------|--------------------------------------------|
| `user_id`  | Unique identifier for the user             |
| `group`    | A (control) or B (test)                    |
| `converted`| 1 if user converted, 0 otherwise           |
| `revenue`  | Revenue generated (only if converted)      |

---

## 🔬 Analysis Performed

- Conversion rate comparison between A and B
- Revenue per user comparison between A and B
- Two-sample t-tests (independent, unequal variance)
- Visualization of conversion and revenue distributions

---

## 📈 Results Preview

- ✅ Conversion rate was higher in Group B
- ✅ Revenue per user was also higher in Group B
- Statistical tests confirmed significant differences

---

## 🧰 Tools Used

- Python (pandas, scipy, matplotlib, seaborn)
- T-test, p-value interpretation
- Simulated dataset to mimic real product behavior

---

## 📎 Files

- `ab_test.csv` — user-level A/B test data
- `ab_test_analysis.ipynb` — full Jupyter analysis
- `ab_test_summary_report.pdf` — PDF-report

---

## License

This project is licensed under the [MIT License](LICENSE).

