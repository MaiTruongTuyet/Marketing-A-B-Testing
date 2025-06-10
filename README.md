# 📊 A/B Marketing Campaign Analysis
# 🧠 Introduction
This project explores the effectiveness of two marketing strategies: advertisement (ad) and public service announcement (psa). Using Python and SQLite, we analyze user behavior to uncover insights on conversion rates and ad performance.

# 🎯 Objective
Compare the conversion rates between the "ad" and "psa" groups

Understand the impact of time (day/hour) and ad frequency on conversion

Identify optimal timeframes and patterns that lead to higher user conversions

# 📂 Dataset
The dataset marketing_AB.csv contains 588,101 records with the following fields:

test group: ad / psa

converted: whether the user made a purchase

total ads: number of ads shown

most ads day: day with the most ad impressions

most ads hour: hour with the most ad impressions

# 🔍 Key Findings
Conversion rate is very low overall (~2.5%)

The ad group has a slightly higher conversion rate (2.55%) compared to the psa group (1.79%)

Monday had the highest conversion rate among days

16:00, 20:00, and 15:00 are the top performing hours for conversion

Higher number of ad impressions tends to slightly correlate with increased conversion, but outliers exist

# ✅ Conclusion & Recommendations
While the overall conversion rate remains low (~2.5%), strategic use of advertisements shows a measurable uplift in performance, particularly when focused on:

Ad content over PSA: Users in the Ad group consistently converted more than those in the PSA group.

### Timing:

Best Day: Mondays yield the highest conversion rates.

Best Hours: Peak performance occurs around 3 PM, 4 PM, and 8 PM.

Ad Frequency: Users who saw more ads were more likely to convert, suggesting positive correlation with ad exposure — but this needs to be balanced to avoid ad fatigue.

# 🔧 Actionable Recommendations:
Prioritize Ads: Use promotional ads instead of PSA for conversion-oriented campaigns.

### Time Targeting:

Schedule campaigns primarily on Mondays.

Target afternoon to evening hours (3 PM–8 PM) for higher engagement.

### Frequency Capping Strategy:

Set a minimum number of ad exposures (e.g., ≥ 5 ads) to improve conversion likelihood.

Monitor diminishing returns and user drop-off to avoid oversaturation.

These findings provide a data-driven foundation to optimize ad scheduling, targeting, and budget allocation, thereby improving marketing ROI.
