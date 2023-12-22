# data1030project
**public repo for data1030 course project**


In the last thirty years, the housing crisis in San Francisco has exploded. With the tech industry infusing wealth into the region, the demand for housing has far outpaced the supply. This in turn has led to an increase in housing prices throughout the region, displacing original residents of the Bay Area who cannot keep up with a skyrocketing cost of living. But in conjunction with the acceleration in costs, the city of San Francisco has adopted some of the country’s strictest zoning regulations. This dangerous combination of amplified demand and bureaucratically-induced supply issues has left San Francisco, and the Bay Area, in real limbo.


I became curious to find any quantitative explanations for the effects of bureaucracy on development in the area. I found a dataset created and maintained by the City of San Francisco’s Open Data Portal, documenting all of the city’s permit applications dating back to 1901. The dataset has 1,226,960 records, but for ease of analysis I chose a subset of records with filing dates ranging from January 1, 2013 to December 31, 2016. This subset of records gives me a dataset with 198,900 records. The dataset’s features include “Permit Type”, “Number of Proposed Stories”, “Estimated Cost”, “Proposed Use”, “Proposed Construction Type”, and “Location” (geographic coordinates of proposed development), all of which are features that could potentially be informative for a predictive model.


The model was engineered with the following research question in mind: Can I predict how long it takes for a given building permit to be issued in the City of San Francisco? This is a regression problem, because I am predicting a continuous variable—in this case, the number of days between filing a permit with the city and having it issued. An analysis of this question could be incredibly valuable for the construction industry, with the delay in issuing building permits considered the main reason for discrepancy in demand and supply in the real estate industry. Additionally, a geographic analysis of the variance in permit issuance times across neighborhoods could unearth systemic inequities in development speeds in different neighborhoods, showcasing an unjust prioritization of certain neighborhoods and demographic groups over others.


Link to dataset: https://data.sfgov.org/Housing-and-Buildings/Building-Permits/i98e-djp9/data
