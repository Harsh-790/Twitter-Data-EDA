# Twitter Data — EDA, Visualization & Statistical Analysis

> *"Social media is not just a spoke in the wheel of marketing. It's becoming the way entire bicycles are built." — Ryan Lilly*

This repository contains a comprehensive **Exploratory Data Analysis (EDA)**, data visualization, and statistical analysis performed on a real-world Twitter dataset containing **100,000 tweets** related to AWS, Cloud Computing, and DevOps topics.

##  Dataset Overview
- **Total Records:** 100,001 rows
- **Features:** 14 columns (including `TweetID`, `Reach`, `RetweetCount`, `Likes`, `Klout`, `Sentiment`, `text`, etc.)
- **Core Topics:** AWS, Cloud Technology, DevOps

---

##  Table of Contents
1. **Setup & Data Loading** - Environment configuration and library loading (Pandas, NumPy, Seaborn, etc.)
2. **Dataset Overview & Quality ** - Checking data shape, types, missing values, and duplicates.
3. **Univariate Analysis** - Distribution analysis of individual features (Reach, Likes, Sentiment, etc.)
4. **Engagement Analysis** - In-depth look into reach, retweets, and likes.
5. **Temporal Analysis** - Analyzing tweet patterns based on hours, days, and weekdays.
6. **Language & Geographic Analysis** - Distribution of tweets across different languages.
7. **Sentiment Analysis** - Classifying and understanding the tone of cloud-related tweets.
8. **Influencer & Klout Analysis** - Measuring user authority and impact.
9. **Correlation & Bivariate Analysis** - Finding relationships between multiple continuous variables.
10. **Statistical Hypothesis Testing** - Validating assumptions with statistical proofs.
11. **Key Insights & Summary** - Final business and technical takeaways.

---

## 🔧 Prerequisites & Libraries Used
To run this notebook, you will need the following Python libraries installed:
- `numpy` (v2.0.2)
- `pandas` (v2.3.3)
- `matplotlib`
- `seaborn`
- `scipy`

You can install the dependencies using:
```bash
pip install numpy pandas matplotlib seaborn scipy
