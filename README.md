# ⚽ Comparing Goal Scoring Patterns in Men's and Women's FIFA World Cup Matches

This project investigates whether more goals are scored in **women's international soccer matches** compared to **men's**, focusing on official **FIFA World Cup** games (excluding qualifiers) from **January 1, 2002** onward. The selected timeframe ensures the analysis reflects the modern era of the sport.

---

## 🧠 Objective

To test the hypothesis that women’s matches have higher scoring rates than men’s using a data-driven, statistical approach.

---

## 📊 Data

- Datasets: `women_results.csv` and `men_results.csv`
- Source: Public online archive of international match results
- Filtered for **FIFA World Cup** matches only (excluding qualifiers)
- Timeframe: **2002 to present**

---

## 🔬 Methodology

- Total goals per match were calculated as `home_score + away_score`
- Compared distributions using the **Mann-Whitney U test** (non-parametric)
- Significance level: **α = 0.10**

**Hypotheses:**
- **Null (H₀):** Mean goals per match are the same in men’s and women’s games
- **Alternative (H₁):** Women’s matches have a higher mean number of goals

---

## 📈 Results

- **p-value:** ~0.0051
- **Conclusion:** At the 10% significance level, the null hypothesis is **rejected**

✅ **Statistical evidence suggests that more goals are scored on average in women’s FIFA World Cup matches** than in men’s.

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- Matplotlib
- SciPy (`mannwhitneyu` test)

---

## 📌 Key Takeaway

This analysis highlights differences in scoring dynamics between men’s and women’s World Cup matches and illustrates how statistical methods can uncover meaningful insights in sports data. The findings could be valuable for analysts, commentators, and soccer enthusiasts alike.

![Preview](https://github.com/sam-asemi/Soccer-Matches-Analysis/blob/main/soccer-pitch.jpg)
