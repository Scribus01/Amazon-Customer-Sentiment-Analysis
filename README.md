# Amazon-Customer-Sentiment-Analysis
An end-to-end customer sentiment analysis project using Python, NLP, and Power BI to analyze Amazon customer reviews and uncover actionable business insights.
Amazon Customer Sentiment Analysis

Project Overview

Customer reviews provide valuable insights into product quality, customer satisfaction, and overall shopping experience. This project analyzes Amazon customer reviews using Natural Language Processing (NLP) techniques to classify customer sentiment, identify recurring feedback patterns, and present actionable business insights through an interactive Power BI dashboard.

---

Objectives

- Analyze Amazon customer reviews.
- Clean and preprocess review text data.
- Classify customer reviews into Positive, Neutral, and Negative sentiments.
- Identify common themes in customer feedback.
- Visualize sentiment distribution and review trends.
- Develop an interactive Power BI dashboard for business decision-making.

---

Dataset

The dataset contains Amazon customer reviews with the following fields:

- Reviewer Name
- Profile Link
- Country
- Review Count
- Review Date
- Rating
- Review Title
- Review Text
- Date of Experience

---

Tools & Technologies

- Python
- Pandas
- NumPy
- NLTK
- Regular Expressions (Regex)
- Matplotlib
- WordCloud
- Jupyter Notebook
- Power BI

---

Project Workflow

1. Data Cleaning

- Removed duplicate records.
- Handled missing values.
- Converted ratings into numeric values.
- Converted review dates into date format.

2. Text Preprocessing

- Converted text to lowercase.
- Removed punctuation and special characters.
- Removed stop words.
- Applied lemmatization.
- Generated cleaned review text for analysis.

3. Sentiment Classification

Reviews were categorized based on customer ratings:

- Positive: Rating ≥ 4
- Neutral: Rating = 3
- Negative: Rating ≤ 2

4. Exploratory Data Analysis

The project explores:

- Sentiment distribution
- Rating distribution
- Reviews by country
- Review trends over time
- Most common positive words
- Most common negative words
- Positive and negative word clouds

---

Power BI Dashboard

The dashboard includes:

- Total Reviews
- Average Rating
- Positive Reviews
- Neutral Reviews
- Negative Reviews
- Sentiment Distribution
- Rating Distribution
- Reviews by Country
- Review Trend Analysis
- Interactive filters for Country, Rating, Sentiment, and Review Date

---

Key Insights

- Negative reviews account for the largest share of customer feedback, indicating customers are more likely to leave reviews after unsatisfactory experiences.
- Positive reviews highlight product quality and successful purchases.
- Customer feedback reveals recurring concerns that can help improve products and services.
- Review trends provide insights into changes in customer satisfaction over time.
- Geographic analysis identifies countries with the highest review activity.

---

Business Recommendations

- Prioritize investigation of recurring issues identified in negative reviews.
- Improve customer support for regions with consistently low ratings.
- Promote frequently praised product features in marketing campaigns.
- Monitor customer sentiment regularly to identify emerging issues early.
- Use customer feedback to drive product and service improvements.

---

Future Improvements

- Implement machine learning models for sentiment prediction.
- Compare multiple sentiment classification techniques.
- Deploy the solution as an interactive web application.
- Automate data updates for real-time customer sentiment monitoring.

---

Author

Ekpadi Richard Babatunde

Aspiring Data Analyst skilled in Python, SQL, Power BI, Excel, and data visualization, with a passion for transforming raw data into actionable business insights.
