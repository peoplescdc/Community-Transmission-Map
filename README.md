# Community-Transmission-Map
Community Tranmission Map based on HHS PCR COVID Cases (Link here: https://docs.google.com/document/d/e/2PACX-1vQjZfuOPvYZxvie_2CInHuY9NvTqdUoNE3DFQM4c4T6A7kT8sZx8jU7gYXrbEi9drBO2RtyVNoLcQRW/pub)

About

The CDC ended their national US COVID community-level transmission map May of 2023. A replacement map is needed as it provides a visualization of current levels of COVID transmission across the US. This map is important as it accounts for a 7-day cumulative COVID rate and provides an assessment of the degree of COVID transmission levels within each state. However, the data being used to estimate COVID transmission rates on this map relies on laboratory-confirmed COVID results, which is a severe underestimate of the actual total volume of COVID cases across the US. Consequently, the map cannot be used to accurately account for actual the total count of COVID cases within each state. Even though the data are extremely lacking, we use available data to help provide public awareness that COVID transmission continues to occur at different degrees of transmission levels and the COVID pandemic is not over.

Data

HHS provides daily counts of laboratory-based PCR-confirmed COVID cases aggregated at the state level. (https://healthdata.gov/dataset/COVID-19-Diagnostic-Laboratory-Testing-PCR-Testing/j8mb-icvb). Using these data from the CDC, we report the total count of a cumulative 7 day total of daily number of confirmed COVID cases reported from at least 37 to 39 states including Washington DC. The following states have not consistently reported their data to the CDC: Alabama, Arkansas (sometimes), Colorado, Connecticut, Delaware, Florida, Missouri, Montana (sometimes), New Jersey, New Mexico, Oregon, South Dakota, and Texas. Some of these states do provide their data within their local state department of health dashboard, but the data from these states are not included in the maps. We also share the data we used in developing these maps provided by the CDC for public viewing in the PCDC’s Github.

Methods

This COVID transmission map displays the cumulative total of new daily COVID cases per 100,000 population in a state. We chose to take a cumulative total of 7 days of data for each state if they consistently reported COVID cases across 7 days. 

Our model is pretty straightforward: First, we add all the new COVID cases in a state for 7 days. Then, we divide that number by the total population in each state. On the map, we show the numbers as a rate of 7 days of cases per 100,000 total population.

COVID levels were grouped according to intensity. Low transmission is considered anything below 1 new COVID cases per 100,000. Moderate is defined as 1-10 cases per 100,000. Substantial is defined as 10 to 20 cases per 100,000High is defined as 21 to 40 cases per 100,000. Very High is defined as greater than 40 cases per 100,000. States with no data were shaded in white with lines.

In developing this image, we used ArcPro, a mapping software.


Assumptions

In reporting these data on this map, we made several assumptions. COVID testing data was consistently and uniformly collected at each state. States sharing data from their public health departments reported all PCR-based laboratory data.

Limitations

Several limitations in developing and reporting the data in these maps. The CDC consistently reports 39 states but this entails a two to three week delay in reporting. Rapid antigen test results are uncommonly reported and results in a severe underestimate of COVID case counts. This is because of a popular use of rapid antigen COVID tests and a lack of formal reporting mechanism for positive rapid antigen COVID tests that loop back into a single database. Seven day cumulative totals of COVID cases is not a perfect approach compared to daily cumulative totals of COVID cases. Some states do provide their data within their local state department of health dashboard, but the data from these states are not included in the maps

Note: Please be patient with us as we develop these maps. Feel free to share feedback with us via this form or your contact information if you would like to commit to helping improve these maps. (https://forms.gle/ubio6oF8SgqTHxwT9)
