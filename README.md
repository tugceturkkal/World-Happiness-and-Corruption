# World-Happiness-and-Corruption
Interpretation of countries' happiness and corruption scores between 2015-2020

In this project, I examined 4 factors affecting the happiness scores of countries in 2020. 
These are health, freedom, social support and consumer price index score. I tested it first in multiple linear regression.

Then, I applied logistic regression by ranking those with a happiness score below 5 as no (unhappy), and those above 5 as yes (happy).

Finally, I tested my model with some methods.

Meaning of columns in data:
happiness_score = Average of responses to the primary life evaluation question from the Gallup World Poll(GWP) 0-10.
gdp_per_data = The extent to which Gross Domestic Product(GDP) contributes to the calculation of the happiness score.
family = The extent to which family contributes to the calculation of the happiness score.
health = The extent to which life expectancy contributed to the calculation of the happiness score.
freedom = The extent to which freedom contributed to the calculation of the happiness score.
generosity = A numerical value calculated based on poll participants' perceptions of generosity in their country.
government_trust = The extent to which Perception of Corruption contributes to happiness score.
dystopia_residual = A score based on a hypothetical comparison to the world's saddest country.
continent = Region of the country.
year = Year of happiness and corruption.
social_support = Social support is the perception and actuality that one is cared for, has assistance available from other people.
cpi_score = The Corruption Perceptions Index(CPI) ranks of countries around the world, based on how corrupt their public sectors are
perceived to be.
