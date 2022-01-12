# Arbitrage Analysis
### Task 
Using historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. Your task is to apply the three phases of financial analysis to determine if any arbitrage opportunities exist for Bitcoin.

**After reviewing the profit information across each date from the different time periods, can you identify any patterns or trends?**
We can clearly see that in the early date there was a bigger opportunity to profit from the arbitrage, which clearly is reduced as time passed, reducing our profit to $0 in the late period. 

### Early Period
#### Analysis
There were 73 profitable arbitrage trades to be made in the Middle Period resulting in \$14147.17 of profit with an average of \$193.79 per trade. All of them ocurring between around 2am and 8pm.

**Date:** '2018-01-16'
**Data Summary**
|Unit|Value|
|--------|--------|
|count | 73.000000|
|mean | 193.796849|
|std |   88.701429|
|min |  112.520000|
|25% |  139.420000|
|50% |  171.310000|
|75% |  210.060000|
|max |  606.800000|

**Profitable Trades (First and Last 5)**
|Date and Time|Profit|
|--------|--------|
|2018-01-16 02:56:00 | 162.01|
|2018-01-16 02:57:00 | 135.00|
|2018-01-16 02:59:00 | 176.13|
|2018-01-16 03:00:00 | 134.01|
|2018-01-16 03:06:00 | 241.54|
| | ... |
|2018-01-16 19:23:00 | 125.09|
|2018-01-16 19:26:00 | 131.78|
|2018-01-16 19:38:00 | 124.01|
|2018-01-16 19:48:00 | 117.63|
|2018-01-16 20:07:00 | 113.69|

**Total Profit:** $14147.17


### Middle Period
#### Analysis
There were 3 profitable arbitrage trades to be made in the Middle Period resulting in \$330.07 of profit with an average of \$110.02 per trade. All of them ocurring from 8:30am to 9:40am

**Date:** '2018-02-24'
**Data Summary**
|Unit|Value|
|--------|--------|
|count |  3.000000|
|mean | 110.023333|
|std |   10.129246|
|min |  101.750000|
|25% |  104.375000|
|50% |  107.000000|
|75% |  114.160000|
|max |  121.320000|

**Profitable Trades**
|Date and Time|Profit|
|--------|--------|
|2018-02-24 08:32:00 | 121.32|
|2018-02-24 09:32:00 | 107.00|
|2018-02-24 09:39:00 | 101.75|

**Total Profit:** $330.07


### Late Period
#### Analysis
There were no profitable arbitrage trades to be made in the Late Period resulting.

**Date:** '2018-03-26'
**Data Summary**
|Unit|Value|
|--------|-------|
|count | 0.0|
|mean | NaN|
|std |  NaN|
|min |  NaN|
|25% |  NaN|
|50% |  NaN|
|75% |  NaN|
|max |  NaN|

**Profitable Trades**
None

**Total Profit:** $0

## Technologies
*Developed in Python and tested on MacOS.*
It requires to have the following installed (Versions tested):
- Python 3.9.7
- Path
- pandas
- matplotlib

---

## Installation Guide
1. Clone this project using git with the following command: `git clone git@github.com:galcivar/module_03.git`
2. Install Python you should follow this instructions depending on you OS: https://realpython.com/installing-python/

---

## Usage
You can use this program by navigating to the folder of the project (where app.py is) and run:
`jupiter lab` then open the `crypto_arbitrage.ipynb` file in Jupiter Lab

---

## Contributors
Gabriel Alcivar
[Email](mailto:galcivar@galgomedia.com) - [LinkedIn](https://www.linkedin.com/in/gabriel-alcivar-aa83a710b/) - [GitHub](https://github.com/galcivar/)

---

## MIT License

Copyright (c) [2022] [Gabriel Alcivar]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
