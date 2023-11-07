# Community-Transmission-Map
Community Tranmission Map based on HHS PCR COVID Cases

About

The CDC ended their national US COVID community-level transmission map May of 2023. A replacement map is needed as it provides a visualization of current levels of COVID transmission across the US. This map is important as it accounts for a 7-day cumulative COVID rate and provides an assessment of the degree of COVID transmission levels within each state. However, the data being used to estimate COVID transmission rates on this map relies on laboratory-confirmed COVID results, which is a severe underestimate of the actual total volume of COVID cases across the US. Consequently, the map cannot be used to accurately account for actual the total count of COVID cases within each state. Even though the data are extremely lacking, we use the available data to help provide public awareness that COVID transmission continues to occur and at different degrees of transmission levels.

Data

HHS provides daily counts of laboratory-based PCR-confirmed COVID cases aggregated at the state level. Using these data, we aggregate the total count of the daily number of confirmed COVID cases reported by at least 39 states including Washington DC from the CDC. The following states have consistently not reported their data to the CDC: Alabama, Colorado, Connecticut, Delaware, Florida, Missouri, New Jersey, New Mexico, Oregon, Pennsylvania, and Texas. Some of these states do provide their data within their local state department of health dashboard. We also share the data we used in developing these maps in the PCDC’s Github.

Methods

This COVID transmission map displays the cumulative total of new daily COVID cases per 100,000 population in a state. We chose to take a cumulative total of 7 days of data for each state if they consistently reported COVID cases across 7 days. 

Our model is pretty straightforward: First, we add all the new COVID cases in a state for 7 days. Then, we divide that number by the total population in each state. On the map, we show the numbers as a rate of 7 days of cases per 100,000 total population.

COVID levels were grouped according to intensity. Low transmission is considered anything below 1 new COVID cases per 100,000. Moderate is defined as 1-10 cases per 100,000. Substantial is defined as 10 to 20 cases per 100,000High is defined as 21 to 40 cases per 100,000. Very High is defined as greater than 40 cases per 100,000

We used ArcPro, a mapping software, to develop the maps. 

Assumptions

In reporting these data on this map, we made several assumptions. COVID testing data was consistently and uniformly collected at each state. States sharing data from their public health departments reported all PCR-based laboratory data.

Limitations

Several limitations in developing and reporting the data in these maps. Rapid antigen test results are uncommonly reported and results in a severe underestimate of COVID case counts. This is because of a popular use of rapid antigen COVID tests and a lack of formal reporting mechanism for positive rapid antigen COVID tests that loop back into a single database. Seven day cumulative totals of COVID cases is not a perfect approach compared to daily cumulative totals of COVID cases.
