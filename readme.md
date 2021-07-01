# Boost&Co Enters New Zealand

## Background
This is a data analysis project for the following hypothetical scenario:

*Boost&Co, is a UK-based firm that provides funding for high-growth startups. It has decided to expand its focus to New Zealand, and requires information pertaining to the attractiveness of the country's industries, in order to determine where to focus its marketing efforts.*

## Method
New Zealand's 2019 Annual Enterprise Survey (a CSV file) was used as the data for this project. It contains industry performance information for the New Zealand's businesses over the 2013-2019 financial years. The 2019 Annual Enterprise Survey can be found [here](https://www.stats.govt.nz/information-releases/annual-enterprise-survey-2019-financial-year-provisional).

The data was cleaned and formatted using Pandas in a Jupyter Notebook. Some columns were reformatted and redundant columns were removed. After parsing and analysing the data, some industries exhibited abnormally high growth rates, and were subsequently removed.

Filtered data was exported as CSV files, which were then used for visualisations in Tableau, which can be accessed [here](https://public.tableau.com/app/profile/jared7852/viz/BoostCoEntersNewZealand/SalesRevenueofAttractiveNewZealandIndustries). The Tableau Viz contains line charts of the growth rates of the five most attractive startup industries in New Zealand. The data manipulations behind these charts can be found in the Jupyter Notebook.

The most attractive industries for Boost&Co's marketing efforts were determined through a two-stage process:

 1. Using Pandas, the top 10 industries with the highest 6-year growth rates and the highest growth rates between 2018 and 2019 were determined
 2. These industries were compared with lists of commendable New Zealand startups, provided by [Matchstiq](https://matchstiq.io/the-top50-startups-list/) and [Failory](https://www.failory.com/blog/new-zealand-startups).

## Conclusion
The 5 industries in New Zealand for Boost&Co to consider marketing to and financing are:
 1. Advertising, Market Research and Management Services
 2. Agriculture, Forestry and Fishing
 3. Computer System Design and Related Services
 4. Construction Services
 5. Financial Asset Investing

Barring Agriculture, Forestry and Fishing, all of the above industries were in the top 10 fastest-growing industries, and were mentioned frequently in the above lists of startups.

While Agriculture, Forestry and Fishing did not appear in the top 10 fastest-growing industries list, its frequency in the lists of startups (New Zealand is home to many startups focusing on improving the agricultural sector through digital technology), combined with New Zealand's high-end-agriculture-based economy, resulted in it earning a spot in the top 5 most attractive industries.
