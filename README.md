📊 A/B Marketing Campaign Analysis
🧠 Introduction
This project explores the effectiveness of two marketing strategies: advertisement (ad) and public service announcement (psa). Using Python and SQLite, we analyze user behavior to uncover insights on conversion rates and ad performance.

🎯 Objective
Compare the conversion rates between the "ad" and "psa" groups

Understand the impact of time (day/hour) and ad frequency on conversion

Identify optimal timeframes and patterns that lead to higher user conversions

📂 Dataset
The dataset marketing_AB.csv contains 588,101 records with the following fields:

test group: ad / psa

converted: whether the user made a purchase

total ads: number of ads shown

most ads day: day with the most ad impressions

most ads hour: hour with the most ad impressions

🔍 Key Findings
Conversion rate is very low overall (~2.5%)

The ad group has a slightly higher conversion rate (2.55%) compared to the psa group (1.79%)

Monday had the highest conversion rate among days

16:00, 20:00, and 15:00 are the top performing hours for conversion

Higher number of ad impressions tends to slightly correlate with increased conversion, but outliers exist

✅ Conclusion
While overall conversion remains low, strategic use of advertisements (especially during specific time slots and on Mondays) shows a measurable uplift. These insights can guide better scheduling and targeting of marketing campaigns.
