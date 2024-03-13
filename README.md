# AnalyzeABTesting

## Project Description
For this project, I will be working to understand the results of an A/B test run by an e-commerce website. The goal is to utilize practical statistics, regression, and other data analysis tools to help the company determine if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

### Part I - Probability
Load data into dataframe and clean
Obtain basic proportions for statistics such as (but not limited to):
a. conversion rate regardless of treatment or control
b. probability an individual received the treatment page
c. conversion rate of individual who received control page
### Part II - A/B Test
Assume under the null hypothesis, 𝑝𝑛𝑒𝑤 and 𝑝𝑜𝑙𝑑 both have "true" success rates equal to the converted success rate regardless of page - that is 𝑝𝑛𝑒𝑤 and 𝑝𝑜𝑙𝑑 are equal
Use 5% Type I error rate
Create sample to perform sampling distribution to show differences in conversion
Compare results of hypothesis test with statsmodels.api z-test.
