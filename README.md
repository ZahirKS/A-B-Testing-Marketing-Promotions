# Case Study: A/B Testing of Marketing Promotions

Which promotion was the most effective?

## Scenario:

A fast food chain plans to add a new item to its menu. However, they are still undecided between three possible marketing campaigns for promoting the new product. In order to determine which promotion has the greatest effect on sales, the new item is introduced at locations in several randomly selected markets. A different promotion is used at each location, and the weekly sales of the new item are recorded for the first four weeks

**The description of the data set:**
Our data set consists of 548 entries including:
- MarketId: an inhouse tag used to describe market types, we won't be using it
- AgeOfStores: Age of store in years (1–28). The mean age of a store is 8.5 years.
- LocationID: Unique identifier for store location. Each location is identified by a number. The total number of stores is 137.
- Promotion: One of three promotions that were tested (1, 2, 3). We don’t really know the specifics of each promotion.
- Sales in Thousands: Sales amount for a specific LocationID, Promotion and week. The mean amount of sales are 53.5 thousand dollars.
- Market size: there are three types of market size: small, medium and large.
- Week: One of four weeks when the promotions were run (1–4).

## Conclusion

### Analysis of P and T-values of the promotions
Our **P-Value is close to 0** which suggests that there is good evidence to **REJECT the Null Hypothesis**. Meaning the there is a statistical difference between the two groups. Our threshold rejectings the Null is usually less than 0.05.

Our **T-test** shows that the marketing performances for these two groups are significantly different and that promotion group 1 outperforms promotion group 2. 

For Promotion 1 vs Promotion 2 t-value is greater than threshold t-value and p-value is less than threshold p-value. Therefore we can accept that there is statistically significant change in sales amount due to promotion 1 over promotion 2 i.e Promotion 1 performs better to drive up sales amount as against Promotion 2

However we cannot say the same for Promotion 1 over Promotion 3 as it doesn't satisfy both our conditions p-value is greater than the threshold p-value. So we coclude that Promotions 1 and 3 outperform the Promotion 2 but difference in average sales amount due to Promotions 1 and Promotions 3 is not statistically significant.
