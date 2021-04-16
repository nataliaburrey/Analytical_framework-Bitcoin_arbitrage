[
<img width="639" alt="Screen Shot 2021-04-12 at 8 20 29 PM" src="https://user-images.githubusercontent.com/80833988/114492020-8e6bdf80-9bcc-11eb-88f3-94b0022230ab.png">
](url)


# Crypto Arbitrage

* Analytical framework for identifying arbitrage situations

> "For this assignment, I will sort through historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. My task is to apply the three phases of financial analysis to determine if any arbitrage opportunities exist for Bitcoin.
"

- [Introduction](#Introduction)
- [Why?](#why)
- [How to Install](#how-to-install)
- [How to use](#how-to-use)
- Technologies used
    - [Libraries](#Libraries)
    - [Interfaces](#Interfaces)
- [Conclusions](#Conclusions)



## Introduction

In this Challenge I created a Jupyter notebook that contains the code for data collection, preparation, and analysis, including any visualizations. Within the same notebook file, you can find comments and text to document my analysis, including the answers to the questions in the Challenge instructions. For each line of code there is comments, necessary labels and lables for the visualizations are included. 

To accomplish these tasks, the following phases of financial analysis were perfomed:

* Data collection from given CSV files in a Jupyter notebook file.
* Preparation of the datasets for analysis by cleaning missing and erroneous data.
* High level  data analyses through summary statistics and visualizations: for deeper analysis closing price column was selected. Specifically, 3 time periods were selected to identify arbitrage opportunities (EARLY: February 2016, MIDDLE: December 2017, LATE: December 2018) with further focus on specific dates.



## Why?

To understand Bitcoin price change over time we need to know some background behind the technology, in this case - Halving event. Here is a quote from Investopedia: 
> "After every 210,000 blocks mined, or roughly every four years, the block reward given to Bitcoin miners for processing transactions is cut in half. This cuts in half the rate at which new Bitcoin is released into circulation. This is Bitcoin's way of using a synthetic form of inflation that halves every four years until all Bitcoin is released and is in circulation."
(https://www.investopedia.com/bitcoin-halving-4843769)

[
<img width="1506" alt="Screen Shot 2021-04-12 at 6 09 52 PM" src="https://user-images.githubusercontent.com/80833988/114481862-5491dd80-9bba-11eb-9dbd-84c7f875c0c9.png">
](url)

In this analisys I can clearly witness the impact of such an event. Particularly second halving, happened in July of 2016, brought incredible arbitrage opportunities about half a year after - as we can see analyzing the MIDDLE time period in December 2017.

In 2020 happened not only pandemic- big event for crypto world- third Bitcoin blockchain halving event - and now, as of today - April 2021 - we are at the all-time-high Bitcoin price $61,788.45. 

Although arbitrage opportunities with Bitcoing nowadays are narrow, we can see that halving events causing volatility, sharp price rise and periods of possible arbitrage profits. The forth Halving event is coming - we better start prepearing now! 

## How to install

* Save GitHub repository Challenge_3_Crypto_Arbitrage

```
git clone https://github.com/nataliaburrey/Challenge_3_Crypto_arbitrage.git
```

## How to use

* Open a Jupyter Lab: In Terminal type command

```
jupyter lab
```


* Choose [ crypto_arbitrage.ipynb ] file to see cleaned data, visualizations and analysis report.

[
<img width="320" alt="Screen Shot 2021-04-12 at 7 46 45 PM" src="https://user-images.githubusercontent.com/80833988/114489380-e48a5400-9bc7-11eb-8c47-c4c18194f32b.png">
](url)

* Collect the data : in order for Jupyter Lab to use accurate data, make sure to have Resources folder with CSV files
> "bitstamp.csv and coinbase.csv" 

[
<img width="265" alt="Screen Shot 2021-04-12 at 7 45 00 PM" src="https://user-images.githubusercontent.com/80833988/114489248-aa20b700-9bc7-11eb-885b-5862f7c1cffb.png">
](url)



## Technologies used

### Libraries


We are using Pandas- a software library written for the Python programming language for data manipulation and analysis.
The following libriries has to be imported:

```
import pandas as pd
from pathlib import Path
%matplotlib inline
import numpy as np
```
In particular, Pandas offers data structures and operations for manipulating numerical tables and time series. It is free software released under the three-clause BSD license.

> " Written in: Python, Cython, C .  
Original author(s): Wes McKinney. . 
License: New BSD License
"



### Interfaces

* Jupyter Lab
* GitHub
* You can download Anaconda packedge on MacOC [HERE](https://www.anaconda.com/products/individual)
Make sure to use following packedge:

[
![anaconda_python37](https://user-images.githubusercontent.com/80833988/113497395-828b6980-94b8-11eb-918c-df4a446f817d.png)
](url)





## Helps recruiters

* The project was created in collaboration with Berkeley Fintech Bootcamp team: Allan Hall, Joel Gonzales, Siege.
* Tutor Lavina Tang helped me to polish my code and tought me how to run separate parts of code to see if it works every step.
* AskBCS Learning Assistant was used to troubleshoot some of the accuring problems outside of the classroom



## Conclusions

Arbitrage profits are extremely hard to come by at the market for Bitcoin matures across time. As Bitcoin grows in popularity, the prices across the two exchanges trade more in line with one another. That makes is very difficult find a point where the price difference exceeds the minimum profit threshold of 1%.

Our careful analyses of Bitcoin price on 2 popular crypto platforms Bitstamp and Coinbase identified that period of arbitrage opportunities came after second halving event, happened after EARLY analyzed period of 2016. Prices of Bitcoin was steadily going up until reached "all time high" during price volatility of December 2017.

This is why the only profitable period we found during our analyze were MIDDLE 2017-12-09 with 1440 potentially profitable trades presenting opportunity to make 1095460.4 total profit. That was a great opportunity!

We can see that the arbitrage opportunities in Bitcoin didn’t last. It was a temporary situation, because arbitrage is basically a zero-risk transaction. Inconsistency in the price creates a possibility to profit immediately. As we know time factor in investment equation creates a great risk, and in this scenario we witnessed in the MIDDLE period we see opportunity to make high profits essentially risk-free. Its a dream of any investor- earning profits without a risk. Such an opportunity increases demand for buying the lower-priced asset(in out case- Bitstamp exchange), this drives the price on this platform up. On the other side of the arbitrage trade (Coinbase platform in this scenario) an increased number of higher priced assets drives that price down. Eventually two prices sync, as we can see in the LATE period of December 2018 -the arbitrage opportunity disappears.



---

Feel free to contact me via channels

* Email:(nataliaburrey@gmail.com) 
* LinkedIn: (https://www.linkedin.com/in/natalia-burrey-181822175/)



---

* License

MIT
