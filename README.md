# Toto_Singapore

Extraction & Analysis of TOTO Results
A mini-project to analyse 3 years of TOTO Group 1 data.

totocreate.py: create an sqlite database for storing toto data
totoscrape.py: scrape toto results from Singapore Pool's website
toto_all_locations.py: scrape all branches & authorised sellers from Singapore Pool's website
totogeocode.py: geocode addresses into latitude and longitude using Google Maps API



The TOTO $8Million draw snowballed 3x to  coming this Monday 18 Oct 9pm, with a $8 million prize for the jackpot. Being a true-blue Singaporean, I have bought some numbers too. We all know that this is a game of chance, luck and rather low probability of winning, but wouldn’t it be interesting to see some real data?

There are two parts of this project. The first is to get the data. 3 years of Group 1 jackpot data are available in Singapore Pool’s website. The extraction was automated using Python, and dumped into a sqlite database. Google Maps API was also used to geocode Singapore Pool branch’s addresses so as to place markers in a map.

With the more time-consuming coding over, all the data were finally visualised using Tableau. And the resulting dashboard above is created.

The eventual dashboard resulting from this project:
https://public.tableau.com/views/Toto102018-21-FINAL/TOTO?:language=en-US&:display_count=n&:origin=viz_share_link
