---
layout: page
title: Portfolio
---

## R Project #1: League of Legions Champions Analysis
* First Data Science Project
* Focused on Telling Story of Growing E-Sports Market
* Analyzed 25000 games to determine most important features of characters and play against powerful characters
* Created a Logistic Regression Models with 95% accuracy of determinging winning team
* See Code for [Champions Analysis] 
* See the Presentation about [League of Legions]

<p align="center">
  <img src="https://raw.githubusercontent.com/glatsa/glatsa.github.io/master/assets/img/Champions.png" width="480" height="270" />
</p>

## R Project #2: Denver Airport Flight Departure Analysis
* Analyzed 230,000 fights departing from Denver to understand departure & delay trends (obtained from the [FAA])
* Created the below map weighting each line based upon the number of flights
* Created 3 Multi-Demensional Vizualizations, to show performace for factors of Season, Airline, Destination, and Time of Day. 
* See Code for [Flight Departure Analysis]
* See the Presentation about the [Denver Airport]

<p align="center">
  <img src="https://raw.githubusercontent.com/glatsa/glatsa.github.io/master/assets/img/US.png" width="480" height="270" />
</p>

## Python Project #1: Jefferson Housing Market Analysis
* Analyzed 82,000+ real estate sale transaction in Jefferson County to understand the real estate markert (obtained from the [Jefferson County])
* Successfully Webscrappted to Gather Additional Data 
* Created a function to generate heat maps based upon given critera (sq. footage, price of home, qty of sales, etc..) 
* See Code for [Housing Market Analysis]
* See the Presentation about the [Jefferson Housing Market]

<p align="center">
  <img src="https://raw.githubusercontent.com/glatsa/glatsa.github.io/master/assets/img/Map.png" width="480" height="360" />
</p>

## Python Project #2: Reddit Scrapping Tool
* Successfully connected to [Reddit API] to obtain real time data
* Used a function to filter comments and cleaned the comments with regular expressions
* Used sentiment analsis and LDA models to create models about what factors for each topic  
* See Code for [Reddit Scrapping Tool] 

```python
# Import Python Packages
import praw
from praw.models import MoreComments
import pandas as pd 
import numpy as np
from datetime import datetime
import sys
import pprint

# Enter Personal API Info: 
# addition info @ 
# https://gilberttanner.com/blog/scraping-redditdata
cid = # Enter your own from Redit
csec = # Enter your own from Redit
ua = # Enter your own from Redit

# Check Connection
reddit = praw.Reddit(client_id= cid, client_secret= csec, user_agent= ua)
print(reddit.read_only)

# To be Continued ...
# Check the Above Link for Reddit Scrapping Tool
```

[League of Legions]: https://github.com/glatsa/IST%687/IST%687%Final%Project/IST%687%Final%Project%Presentation.pptx'
[Champions Analysis]: https://raw.githubusercontent.com/glatsa/Graduate-School/master/IST%20687/IST%20687%20Final%20Project/IST%20687%20Final%20Project%20Code.R 
[FAA]: https://www.transtats.bts.gov/Fields.asp
[Denver Airport]: https://drive.google.com/open?id=1MGXpo7St9glUjKF3_knHsDj8VsVdACmZ
[Flight Departure Analysis]: https://github.com/glatsa/Graduate-School/blob/master/IST%20719/IST%20719%20Final%20Project/IST%20719%20Final%20Project%20Code.R
[Jefferson County]: https://propertysearch.jeffco.us/propertyrecordssearch/sales
[Jefferson Housing Market]: https://github.com/glatsa/IST%652/IST%652%Final%Project/IST652%Final%Project%Presentation.pptx
[Housing Market Analysis]: https://github.com/glatsa/Graduate-School/blob/master/IST%20652/IST%20652%20Final%20Project/IST%20652%20Final%20Project%20Code.ipynb
[Reddit API]: https://praw.readthedocs.io/en/latest/
[Reddit Scrapping Tool]: https://github.com/glatsa/Graduate-School/blob/master/IST%20736/Reddit%20Scraping%20Tool.ipynb
