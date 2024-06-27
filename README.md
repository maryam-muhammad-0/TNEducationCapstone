# TNEducationCapstone
## Table of Contents
* [Motivation](#Motivation)
* [Technologies](#Technologies)
* [Problems & Hurdles](#problems--hurdles)
  * [Getting the Data](#getting-the-Data)
  * [Data Normalization Trouble](#normalizing-the-data)
  * [Hurdles](#Hurdles)
* [Link to Dashboard](#link-to-dashboard)

## Motivation
#### In March of 2020, most students around the world learned that the way they expected to learn for the remainder of the school year would look drastically different from what they expected. During the third to last month of my senior year at Vanderbilt University, I along with thousands of other undergraduate and graduate students on campus received news that we should expect our Spring break to be extended by two days. Two days later, we were informed that we all had to pack up our bags, mini fridges, and futons to complete the rest of the school year virtually. Shocked, concerned, and confused, I began the work of packing up my entire apartment over the next two days - trying to fit in as many hugs with friends as possible as we struggled to hear the words "goodbye". As a first-generation college student, walking across the graduation stage in May 2020 to collect my diploma was my north star. Despite how hard it was to swallow the truth that that would not happen as I imagined, I found myself grateful that I experienced nearly 100% of college in-person and on-campus. But what about future college goers that would be starting college in unimaginable conditions (social distancing, masking, etc)? How would enrollment and graduation rates be affected? How will existing inequities in the higher education system be impacted?

#### I started my career after graduating at EY-Parthenon, where I conducted market research in the education and technology sectors. Through my research, it was clear to me that Americans are beginning to question the value and investment in higher education leading to lower enrollment rates and the pursuit of online degrees and certifications. Between fall 2009 and fall 2019, before the coronavirus pandemic, there was a decrease of 0.9 million students (5%) enrolled in undergraduate institutions. It decreased by 0.7 million students (or 4%) between fall 2019 and fall 2020 alone. This decrease is to be expected at the start of the 2020 school year, but the COVID-19 pandemic continued to affect the campus learning and living environment through 2022.


#### My project therefore examines the impact of the COVID-19 pandemic on college enrollment and graduation rates from 2019 to 2022. With this research, I hope to uncover trends in those rates given the Race/Ethnicity and Gender of students, as well as trends given the HBCU status and locale of the higher education institution.

## Technologies
#### For this project I used Python 3 within a Jupyter Notebook, Tableau, and Excel. The data was extracted from the National Center for Education Statistics' (NCES) Integrated Post Secondary Education Data System found here at https://nces.ed.gov/ipeds/ as CSV files and imported into Jupyter for data cleaning.

#### For the organization of the cleaned data, Tableau was used to create charts.

## Problems & Hurdles
### Getting the Data
#### The data was obtained from the NCES IPEDS database: 
#### I retrieved the data from the NCES IPEDS database which includes numerous fields and categories under which the data may fall. Because of the large number and variation of fields, I took careful care to select the appropriate fields for the data by reading the individual descriptions of each of the fields. The data must be pulled by year, so I replicated this process for each of the years between and including 2019 and 2022. 
### Normalizing the Data
#### One thing that might become evident in examining average graduation rate by Race/Ethnicity is that because of the low numbers of students in specific groups ("American Indians/Pacific Islanders"), their average graduation rates are skewed. However, I believe that this doesn't greatly alter the overall graduation rate from 2019-2022.
### Hurdles
#### Pulling the data was slightly laborious. The NCES website also malfunctioned on several occasions making it difficult to extract the data easily, though, with time, this was resolved.

## Link to Presentation
#### https://docs.google.com/presentation/d/17NSTLlBfxeGQ8Mrm7Zt2_hHxDshBmyEgxTWfJEyO2NE/edit#slide=id.p
