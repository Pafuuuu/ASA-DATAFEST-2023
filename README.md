# ASA-DATAFEST-2023


## Project Overview

This repository contains the presentation for our award-winning project at the 2023 UCLA ASA DATAFEST. The data was provided by the American Bar Association, and our goal was to develop a numerical metric to rate lawyer performance and client satisfaction. The findings from this project aimed to improve the client-lawyer match rate and overall user experience.

## Sentiment Analysis
After cleaning the text data and applying a predictive sentiment model, we assigned positivity scores to client-lawyer interactions. Notable insights include:
   - **State Variations**: Most states showed an increase in positivity after receiving a lawyer's response, with the exception of Kansas.
   - **Response Time vs. Quality**: Faster responses did not necessarily lead to better sentiment; the quality of the content was more important.
   - **Concise Replies Preferred**: Shorter, more concise lawyer replies resulted in higher user response rates and better sentiment levels.

## User Churn Analysis

During the analysis, we identified significant user churn at various stages of the client-lawyer interaction process. We constructed a 5-level funnel model to analyze this churn and propose targeted solutions:

### Registration
- **Problem**: Many users were denied access to an account because they entered "Null" as their income, despite the platform primarily serving low-income households.
- **Solution**: Implement a more detailed income verification process.

### Question Posting
- **Problem**: There was a mismatch between lawyer expertise and client needs. Categories like Family, Children, and Housing were the most popular but had the lowest response rates.
- **Solution**: Recruit and allocate lawyers based on identified client needs.

### Receiving Answers
- **Problem**: Each post automatically closed after 10 days, but the average response time from lawyers often exceeded this period.
- **Solution**: Extend the closing date and introduce a monitoring program to prioritize older posts.

### Follow-up
- **Problem**: Many conversations ended after the legal end date of clients' trials, meaning clients never fully utilized the advice provided.
- **Solution**: Enhance user response rates by implementing a rating system after each consultation and tracking user retention for better future analysis.



By addressing these key issues, our solutions significantly improved the user experience on the platform. Our team was honored with the Award for Best User Experience at the 2023 UCLA ASA DATAFEST.

---

Feel free to explore the repository to see the full analysis and presentation that led to these findings.
