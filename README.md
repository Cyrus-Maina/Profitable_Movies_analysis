# Profitable_Movies_analysis
This analysis assumes we have an investor for a customer who seeks our guidance on deciding in which genre should he venture to considering its profitability and low capital costs.
We as a data science compay research across for datasets to extract insights.
The analysis primarily concentrates on highest profit margins possible and low capital costs.
The datasets were sourced from https://github.com/czarina-ds , cleaned,organized and analyzed.
They consist of Movies from as early as 1930s to 2023 making the datasets as up-to-date as possiblle.
The  clean dataset has 12 fields and 5747 records or movies.

The dataset has the following fields:

  1. release_date-day mpovie was released
 
  2. movie
 
  3. production_budget-capital used to produce movie
 
  4. domestic_gross-revenue from mother country
 
  5. worldwide_gross-global revenue
 
  6. runtime_minutes-length of movie
 
  7. genres
 
  8. production_company
 
  9. production_country
 
  10. Profits
  
  11. ROI-return on investment from capital
  
  12. Category-whether a movie was profitable or not

**STATISTICAL OPERATIONS CARRIED OUT**
1. Mean and median were frequently used to analyse ROI, runtime_minutes and production_budget. The measures provided insights such as which genre is most expensive to make, which genre has the highest yields and for how long does each genre run for.

2. Correlations- used to deduce relationships amongst fields like Profits & production_budget which then guides us on effort distribution.

3. Time-series analysis- shows us growth of a genre over time. Exposes any hidden patterns and trends.

4. Conversion of fields' datatypes- helps analyse values without getting errors e.g.,runtime_minutes converted to float from strings

5. Visualizations- all insights are plotted to enhance clarity of findings.

**FINDINGS**

 Horror movies genre was by the far the most profitable and:

1. They have an ROI mean and median of *1.9 and *10 respectively.

2. They run for 96-98 minutes

3. Run on an estimated budget of $10 -10.6 M, the second cheapest genre to produce

4. United States has the biggest apetite for Horror movies making it the best bet for a profitable production_country choice

5. October has the highest count of profitable horror movies release

6. It's very advisable to produce in the US as we've seen domestic success assures more than 90% of global success.

7. Regency Enterprises,Twisted Pictures, Burg-Knoules, Hoffman,Mandate Pictures and Blumhouse, Solana Films have the highest
   profitable movie count making them your go-to production companies.

8. Profitable Horror movies have been growing over the years reaching record heights in 2019 and did rise again in 2021 after
   a sharp fall in 2020

9. 63.9 % of all produced horror movies across the years were profitable. A positive indicator of audience appreciation of the genre

With these insights our customer will have an upperhand due to the clarity these insights provide.
Neverthless, it's fair to mention other factors play a huge part on the success of a film e.g., Plot, Directors, Cast, Seasons, Trending Movements/Trends e.g., Black Lives Matter helped Black Struggle movies do very well e.g.,The Hate U Give.
