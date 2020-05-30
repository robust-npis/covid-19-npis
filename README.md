# covid-19-dataset
Daily data on active nonpharmaceutical interventions against COVID-19 in 41 countries


## NPIs included in the modelling dataset

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