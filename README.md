# Mock Creator Payout Eligibility Tracker

This project explores how payout eligibility rules might impact creators on a platform like Twitch. I created a mock dataset with user metrics such as monthly views, revenue, account age, and country. Then, I used Python and pandas to simulate payout eligibility based on configurable thresholds (e.g. 1,000 views and $50 monthly revenue).

The goal was to practice SQL-style logic, data cleaning, and exploratory analysis while analyzing the potential effects of monetization policies across different creator segments.

---

## Project Objectives

- Apply SQL-style filtering using pandas to determine eligibility logic
- Visualize payout trends and creator patterns using matplotlib
- Explore how changes in thresholds affect different user groups
- Practice data storytelling through clear summary outputs and charts

---

## Dataset Overview

- 200 synthetic creator profiles
- Fields include: creator ID, country, monthly views, monthly revenue, account age (months), and payouts received
- Simulated for flexibility in testing eligibility rules

---

## Key Questions

- How many creators qualify under a 1,000 views / $50 revenue policy?
- Which countries have the most or fewest eligible creators?
- What trade-offs exist when raising or lowering payout thresholds?

---

## Tools and Skills Used

- Python (pandas, numpy)
- Matplotlib (visualizations)
- Jupyter Notebooks
- Data filtering and rule-based logic
- Exploratory Data Analysis (EDA)
- Basic scenario testing for policy impact
- Version control and GitHub documentation

---

## Why I Chose This Project

As someone transitioning into data science from financial operations, I wanted to simulate a use case that blends product policy, user behavior, and payout mechanics. This project helped me practice core technical skills—like data wrangling and visualization—while thinking critically about real-world creator platforms.

---

## Files

- `mock_creator_payout_data.csv` – the full synthetic dataset
- `mock_creator_payout_tracker.ipynb` – notebook with code and analysis
- `eligibility_by_country.png` – chart of eligible creators by country

---

Thanks for checking this out! More improvements coming soon as I expand on this idea.
You can explore more of my learning journey in the [main portfolio](https://github.com/sbellande).
