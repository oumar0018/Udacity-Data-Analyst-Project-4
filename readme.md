# House prices Data Exploration

## Dataset

The data consists of information regarding 6028 houses from 3 different neighborhoods, including
house id,price, number of bedrooms, number of bathrooms and style of the house. The dataset can be found in the udacity page https://video.udacity-data.com/topher/2019/March/5c9559fa_data-3/data-3.zip

## Summary of Findings

In the exploration, I found that there was a strong relationship between the
price of the area (size) of a house, style and number of bedrooms. I found a
somewhat surprising result initially when the marginal trend for the cut, color,
and clarity variables indicated that higher diamond quality was associated with
lower price. However, higher diamond quality was also associated with smaller
diamonds. When I isolated diamonds of a single carat weight, there was a clear
positive relationship between higher diamond quality and higher diamond price.

Outside of the main variables of interest, I verified the relationship between
house style and neighborhood. For the dataset given, there was an interestingly strong relationship between the style and neighborhodde of hosues. houses of the same size differ in price from one neighborood to another, but houses of victorian style have highest price in all the neighborhoods, and those with lodge style have always the lowes price.


## Key Insights for Presentation

For the presentation, I focus on just the influence of the area, neighborhood and style on the price of the houses. I start by introducing the price variable, followed by the pattern in area distribution, then plot the correlation between price and area by neighborhood, and then price and area by style.

I use the facetGrid plots of price and and area across neighborhood. I'm only looking at
the influence of neighborhood on the price and area of the house. Then I looked at the FacetGrid plots of price and area across style. I've made sure to use different color palettes for each quality variable to make sure it is clear that they're different between plots.
