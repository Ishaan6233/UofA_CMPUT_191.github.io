# Why Nike Air Jordan 1s?
The Air Jordan 1 was the first release in what became the most coveted series in sneaker history. Appealing to basketball fans and sneaker aficionados alike, the combination of athlete endorsement, heritage, and wearability have resulted in the sneaker’s timeless status.

They are one of the most famous pieces of clothing in the whole world, known for their iconic look and high-quality material. Moreover, having plenty of data on the sales of this particular sneaker made our choice clear to choose this as our product for this project.

## Project Objective
The objective of this project is to analyze the price variations of Nike Air Jordan 1s across different countries, considering factors such as currency exchange rates, sales tax, and median income. This analysis helps us understand the global market dynamics for this iconic sneaker.

## Data Collection
We collected data from various sources to build our analysis:

Shoe Prices: The prices of Nike Air Jordan 1s in different countries.
Sales Tax Rates: The sales tax rates applicable in each country.
Currency Exchange Rates: The exchange rates of different currencies against CAD.
Median Income: The median income of different countries to analyze the affordability.
Data Preparation and Cleaning

### Shoe Prices Table
Removed rows with missing values.
Stripped the dollar symbol from the price column (e.g., $127.85 to 127.85).
### Sales Tax Table
Removed rows with missing values.
Converted sales tax values from percentages to floats (e.g., 27.00% to 27.00).
### Currency Table
Removed repeated elements from each column.
### Data Joining and Processing
The data from different sources was joined using the country column as the foreign key. This resulted in a comprehensive table that includes shoe prices in CAD, adjusted for local sales tax.

## Data Transformation
Currency Conversion: Converted the shoe prices from USD to CAD.
Tax Adjustment: Adjusted the shoe prices based on local sales tax rates.

## Visualization
### Price Comparison
From the bar graph produced, it can be seen that the shoe prices are the lowest in the United States of America and highest in Argentina.

### Affordability Analysis
We chose Median Income as our external factor to analyze the affordability of the shoes in each country. The Median Income provides the best estimate of the affordability of the shoe in each country.

As the Median Income of a country increases, the demand increases, which should result in the increase of the Shoe Price in each Country. However, from the scatterplot and the correlation coefficient, it can be inferred that there is a weak negative correlation between the Shoes Prices and the Median Income. Since the correlation coefficient is negligible, we can conclude that our assumption is not consistent with our data.

## Possible Extraneous Factors
Several extraneous factors could influence the shoe prices across different countries, including:

## Transport Costs
Government Intervention
Non-Traded Services
Market Competition
Labour Costs

## Conclusion
From the above scatterplot, it can be inferred that there is no apparent correlation between shoe prices and median income. The correlation coefficient indicates a weak negative correlation, suggesting that factors other than median income might be influencing the prices.

## Citations
Shoe Price Table: vividmaps.com
Sales Tax Table: worldpopulationreview.com
Currency Table: countries-ofthe-world.com
Median Income Table: worldpopulationreview.com
