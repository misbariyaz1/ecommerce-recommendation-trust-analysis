# How Algorithmic Recommendation Systems Influence Consumer Purchase Decisions

MSc Business Analytics dissertation, University of Exeter (2026).
A mixed-methods study of how trust and perceived manipulation relate to purchase intention in e-commerce.

## What I did
- Analysed 2.76M clickstream events (RetailRocket dataset) to map the view → add-to-cart → purchase funnel
- Designed and ran a consumer survey (197 valid responses) measuring trust, perceived manipulation, transparency and purchase intention
- Tested a moderated regression: trust × perceived manipulation → purchase intention
- Coded open-text responses thematically (retargeting and artificial urgency emerged as the main triggers of perceived manipulation)

## Key findings
- Only 2.6% of product views led to add-to-cart, but 32.4% of carts led to purchase, so the biggest drop-off is at first engagement
- Trust and perceived manipulation both significantly predicted purchase intention (R² = 0.17)
- The moderation effect was not significant. Reliability and sample size limited this test, and I report that openly.

## Tools
Python (pandas, matplotlib, statsmodels), Microsoft Forms

## Files
- `Phase1-Retail-Analysis.ipynb`: clickstream funnel analysis and survey analysis
- `FINAL REPORT.pdf`: full dissertation

## Data
- Clickstream data: RetailRocket e-commerce dataset (public, on Kaggle, not included here due to size). The notebook expects it as `events.csv` in the same folder.
- Survey responses (197 valid) are not shared, to protect participant anonymity, so the survey section of the notebook cannot be re-run without the original file.

## Author
Misba Riyaz | MSc Business Analytics, University of Exeter | [LinkedIn](https://www.linkedin.com/in/misbariyaz)
