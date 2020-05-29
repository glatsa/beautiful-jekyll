---
layout: page
title: Portfolio
---

## R Project #1: League of Legions Champions Analysis

  * Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark. 
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model. 
* See Code for [Champions Analysis] 

<p align="center">
  <img src="https://raw.githubusercontent.com/glatsa/glatsa.github.io/master/assets/img/Champions.png" width="480" height="270" />
</p>

## R Project #2: Denver Airport Flight Delay Analysis
* Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark. 
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model. 
* See Code for [Flight Delay Analysis]

<p align="center">
  <img src="https://raw.githubusercontent.com/glatsa/glatsa.github.io/master/assets/img/US.png" width="480" height="270" />
</p>

## Python Project #1: Jefferson Housing Market Analysis
* Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark. 
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model. 
* See Code for [Housing Market Analysis]

<p align="center">
  <img src="https://raw.githubusercontent.com/glatsa/glatsa.github.io/master/assets/img/Map.png" width="480" height="360" />
</p>

## Python Project #2: Reddit Scrapping Tool
* Created a tool that estimates data science salaries (MAE ~ $ 11K) to help data scientists negotiate their income when they get a job.
* Scraped over 1000 job descriptions from glassdoor using python and selenium
* Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark. 
* Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model. 
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

# Enter Personal API Info: addition info @ https://gilberttanner.com/blog/scraping-redditdata
cid = # Enter your own from Redit
csec = # Enter your own from Redit
ua = # Enter your own from Redit

# Check Connection
reddit = praw.Reddit(client_id= cid, client_secret= csec, user_agent= ua)
print(reddit.read_only)

# To be Continued ...
# Check the Above Link for Reddit Scrapping Tool
```


[Champions Analysis]: https://raw.githubusercontent.com/glatsa/Graduate-School/master/IST%20687/IST%20687%20Final%20Project/IST%20687%20Final%20Project%20Code.R 
[Flight Delay Analysis]: https://github.com/glatsa/Graduate-School/blob/master/IST%20719/IST%20719%20Final%20Project/IST%20719%20Final%20Project%20Code.R
[Housing Market Analysis]: https://github.com/glatsa/Graduate-School/blob/master/IST%20652/IST%20652%20Final%20Project/IST%20652%20Final%20Project%20Code.ipynb
[Reddit Scrapping Tool]: https://github.com/glatsa/Graduate-School/blob/master/IST%20736/Reddit%20Scraping%20Tool.ipynb
