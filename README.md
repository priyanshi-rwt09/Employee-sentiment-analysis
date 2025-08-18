# Employee-sentiment-analysis
Employee Sentiment Analysis Project

#overview 
This project analyzes employee evaluate sentiment trends , employee engagement , flight risk identification using NPL and ML . The project insights into employee communication patterns and predicts potential risks.

Project Workflow
1.) Task 1: Sentiment Labelling
    Classified each email as Positive, Negative, or   Neutral using VADER Sentiment Analysis.  

2.) Task 2: Exploratory Data Analysis (EDA)
   - Analyzed sentiment distribution.  
   - Trends of sentiment over time.  
   - Employee-wise sentiment distribution.  
   - WordClouds for Positive, Negative, and Neutral  messages.  

3.) Task 3: Monthly Sentiment Scores
    - Calculated monthly sentiment score per employee    using:  
     - Positive = +1  
     - Negative = −1  
     - Neutral = 0  

4.) Task 4:  Employee Ranking 
         - Ranked  Top 3 Positive and Top 3 Negative employees each month based on sentiment scores.  

5.) Task 5: Flight Risk Identification  
        - Flagged employees sending  4+ negative emails within 30  days.

6.) Task 6: Predictive Modeling
       - Built a  Linear Regression model to analyze sentiment trends.  
       - Features: Message Frequency, Average Message Length, Word Count.  
       - Evaluated with RMSE & R² score.

# Key findings
  Top 3 Positive Employees   
       Month          Type  Rank                     Employee  \        Monthly_Sentiment_Score  
0    2010-01  Top Positive     1      kayne.coulter@enron.com               14 
1    2010-01  Top Positive     2          eric.bass@enron.com               9
2    2010-01  Top Positive     3      lydia.delgado@enron.com               9
 
  Top 3 Negative Employees   
     Month          Type     Rank                     Employee  \             Monthly_Sentiment_Score  

139  2011-11  Top Negative     2      rhonda.denton@enron.com                        2
140  2011-11  Top Negative     3      lydia.delgado@enron.com                        4
141  2011-12  Top Negative     1      johnny.palmer@enron.com                        1
 
 Employees at Flight Risk  
  eric.bass@enron.com
johnny.palmer@enron.com
 patti.thompson@enron.com
 sally.beck@enron.com

# Insights & Recommendations

-Positive employees are consistent contributors and can be recognized as potential leaders or mentors.  
- Negative sentiment clusters should be investigated for workplace issues (e.g., workload, conflicts, dissatisfaction).  
- Flight risk employees need HR intervention (one-on-one discussions, workload balance, recognition programs).  
- Predictive modeling shows that message frequency and word usage influence employee sentiment trends.  

# Repository Structure

|- employee sentiment analysis
|- README.md
|- Final report
|- Visualizations

#Tech Stack
 -Python(pandas,NLTK,scikit-learn,matplotlib,seaborn,plotly)
 -NLP(vader sentiment analysis)
 -ML(Linear Regression)

