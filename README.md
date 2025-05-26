# 📊 A/B Test Simulation: Ad vs PSA Impact on Conversion

This project simulates a real-world A/B test to determine whether showing product advertisements leads to higher user conversion compared to public service announcements (PSAs).

---

## 🧠 Objective

Evaluate the effectiveness of a product feature (ads) by measuring its impact on conversion rates through a controlled A/B test.

---

## 📁 Dataset Overview

Each row represents a user with the following fields:

- `user_id`: Unique identifier
- `test_group`: "ad" (saw advertisement) or "psa" (saw public service message)
- `converted`: Whether the user converted (True/False)
- `total_ads`: Number of ads shown
- `most_ads_day`: Day of week with most ads shown
- `most_ads_hour`: Hour of day with most ads shown

---

## 📊 Key Analyses

- ✅ Group-wise conversion rate comparison
- 📈 Conversion rate by day and hour
- 🧪 Two-proportion Z-Test to test statistical significance
- 🔼 Lift calculation to quantify business impact

---

## 🧪 A/B Test Results

- **Ad Group Conversion Rate**: 2.55%
- **PSA Group Conversion Rate**: 1.79%
- **Z-statistic**: 7.37  
- **P-value**: < 0.0001  
- **Lift**: +43.09%

---

## ✅ Conclusion

The ad group converted **43% better** than the PSA group, and this difference is **statistically significant**.

### 📌 Recommendation:
> Deploy the ad feature more broadly to improve conversion, and explore further optimization through ad frequency and timing.

---

## 🛠️ Tools Used

- Python (Pandas, SciPy, Seaborn, Matplotlib)
- Jupyter Notebook

---

## 📂 Project Structure

- `notebook.ipynb` – Full analysis
- `README.md` – Project summary

---

## 📬 Contact

Feel free to reach out via [LinkedIn](https://linkedin.com/in/ibrahim-naoun) 
