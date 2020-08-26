# --------------------------------------- 
# This repo refers to a previous version of the preprint and is now outdated. The up-to-date data, model code, and results, can be found at [https://github.com/epidemics/COVIDNPIs/tree/paper](https://github.com/epidemics/COVIDNPIs/tree/paper)
# ---------------------------------------

# Modelling the effectiveness and burden of nonpharmaceutical interventions against COVID-19

Accompanying data and code for Brauner et al (2020), 'The effectiveness and perceived burden of nonpharmaceutical interventions against COVID-19 transmission: a modelling study with 41 countries'. \[Code upload to follow.\]

Daily data on active nonpharmaceutical interventions (NPIs) against COVID-19 in 41 countries. We also include three response variables: total confirmed case count, current known active case count, and total attributed death count.

Data on symptomatic testing regimes was sourced from the [Oxford CGRT database](https://github.com/OxCGRT/covid-policy-tracker). Data on cases and deaths are from the [Johns Hopkins Center for Systems Science and Engineering repository](https://github.com/CSSEGISandData/COVID-19).

These data have been manually checked, but please exercise your own validation before acting on it.

### Data

We include two datasets:

* [daily_npi_data.csv](https://github.com/robust-npis/covid-19-npis/blob/master/data/daily_npi_data.csv) : the modelling dataset, daily coverage of the interventions active in each country
* [npi_source_data.csv](https://github.com/robust-npis/covid-19-npis/blob/master/data/npi_source_data.csv) : including links to the announcement of each NPI in each country.


### NPIs included

| NPI                       | Description |
|---------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Mask wearing              | One or both of:  1) a country has implemented a policy of requiring mask usage among the general public, sometimes limited to certain domains like a duty to wear masks in public transportation and supermarkets  2) survey reports indicate that over 60% of people were wearing masks in public.|
| Symptomatic testing       | Testing is available to anyone showing COVID-19 symptoms (as defined by the country). In a few countries, testing is even available to people without symptoms. |
| Gatherings < 1000         | A country has set a size limit on gatherings. The size limit is at most 1000 people (often less) and gatherings above the maximum size are disallowed. For example, a ban on gatherings of 500 people or more would be classified as “gatherings limited to 1000 or less” but a ban on gatherings of 2000 people or more would not. |
| Gatherings < 100          | A country has set a size limit on gatherings. The size limit is at most 100 people (often less) and gatherings above the maximum size are disallowed.|
| Gatherings < 10           | A country has set a size limit on gatherings. The size limit is at most 10 people (often less) and gatherings above the maximum size are disallowed. |
| Some Businesses Suspended | A country has specified a few kinds of customer-facing businesses that are considered “high risk” and need to suspend operations (blacklist). Common examples are restaurants, bars, nightclubs, and gyms. By default, businesses are not suspended.  |
| Most Businesses Suspended | A country has suspended the operations of many customer-facing businesses. By default, customer-facing businesses are suspended unless they are designated as essential (whitelist). |
| School Closure            | A country has closed many or all schools. (Note that this was accompanied by closing universities in more than 75% of cases in our data.) |
| Stay Home Order           | An order for the general public to stay at home has been issued. This is mandatory, not just a recommendation. Exemptions are usually granted for certain purposes (such as shopping, exercise, or going to work), or, more rarely, for certain times of the day. In practice, a stay-at-home order was often accompanied by other NPIs such as businesses closures. However, a stay-at-home order does not in principle entail these other NPIs,  but only the (additional) order to generally stay at home except for exemptions. |

### See also

* [Oxford COVID-19 Government Response Tracker](https://github.com/OxCGRT/covid-policy-tracker).
* [Johns Hopkins CSSE COVID-19 Data Repository](https://github.com/CSSEGISandData/COVID-19).
* [The Epidemic Forecasting database](http://epidemicforecasting.org/containment).
