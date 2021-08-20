# Topic Filter Rating of Hawaii Airbnb Listings via Natural Language Processing
Jon Yu

## Abstract
Airbnb has experienced exponential growth since its launch 2008. Aided by low mortgage rates in recent years which saw 56% quarter to quarter increase in multifamily unit investments and surge of new landlords (https://capitalcounselor.com/airbnb-statistics/), Airbnb currently observes 14,000 new hosts per month in 2021 (https://capitalcounselor.com/airbnb-statistics/). However, becoming a multi-property landlord does not necessarily pave the way to financial independence as the U.S. has reported 50% relative increase in unemployment from July 2019 to July 2021 (https://data.bls.gov/timeseries/LNS14000000).

As a newly entering entrepreneur who isn't an established superhost, what can you do to appeal to guests and maximize your Airbnb listing's occupancy rate? To aid in this pursuit, I decided to launch this natural language processing and unsupervised learning project.


## Data
Honolulu, Hawaii, boasts the highest Airbnb occupancy rate in the U.S. at 68% (https://capitalcounselor.com/airbnb-statistics/). Hence, the below two data sets from Inside Airbnb (http://insideairbnb.com/get-the-data.html) detailing Hawaii Airbnb's serve as the crux of this project. 

1. 21,808 listing entries
2. 603,048 review entries (documents of the corpus)

Subsequent to NLP on the "reviews" data set, the two data frames were together using the listing ID.

## Algorithms/Tools

langdetect, googletrans to automatically detect and translate non-English reviews

## Findings

## Communication
In addition to a [sample video](Hidden Rating Demo on Tableau.mov) of the Tableu model depicting the alternative Airbnb rating system, an online deployment is also available on https://public.tableau.com/app/profile/jon1263/viz/NLPAirbnb/Sheet1?publish=yes.
