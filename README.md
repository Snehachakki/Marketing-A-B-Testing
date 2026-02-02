📊 Project Overview
This project analyzes an A/B test comparing the effectiveness of advertising campaigns versus public service announcements (PSAs) on user conversion rates. The dataset contains 3,465 users randomly assigned to either a test group (shown ads) or control group (shown PSAs).

📁 Dataset
File: Marketing.csv
Records: 3,465
Columns:

user id: Unique identifier for each user

test group: Group assignment ('ad' or 'psa')

converted: Boolean indicating if user converted (TRUE/FALSE)

total ads: Total number of ads shown

most ads day: Day when most ads were shown

most ads hour: Hour when most ads were shown

🎯 Business Question
Do advertising campaigns result in significantly higher conversion rates compared to public service announcements?

📈 Key Findings
Metric	Test Group (Ad)	Control Group (PSA)	Difference
Conversion Rate	3.35%	1.91%	+1.44%
Sample Size	3,256 users	209 users	-
Relative Improvement	-	-	+75.24%
📊 Statistical Results
Chi-square p-value: 0.1691

Z-test p-value: 0.1687

95% Confidence Interval: [-0.62%, +3.49%]

Statistical Conclusion: No significant difference at α=0.05

🧪 Hypothesis Testing
H₀ (Null): No difference in conversion rates between groups

H₁ (Alternative): Ads have different conversion rates than PSAs

α (Significance level): 0.05

Decision: Fail to reject H₀ - No statistically significant evidence that ads perform differently from PSAs.
