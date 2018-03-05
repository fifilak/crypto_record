# crypto_record
My first repository on GitHub

This is my first repository on GitHub, I will slowly be improving the script. I'm beginner in python programming and this is my first project. I'm open to every suggestion and will really appriciate feedback and proposals for improvements. To run it at this point, I use Anaconda Navigator (https://www.anaconda.com/what-is-anaconda/)

## Beginners script for cryptocurrency portfolio tracking. 

This python script calculates the total value, profit/loss of any porfolio together with percentage per owned crypto and it's value in EUR/USD. It takes as an input csv file, which can be created from xls file containing 2 columns defined as: 

* A - list of owned cryptocurrencies indexed by name shorcut (eg. Bitcoin -> BTC)
* B - list of available amount of defined cryptocurrency (eg. 3.56)

To visualize this, first 3 rows of a excel file containing relevant data looks as follows:

|   |  A  |   B  |
|---|:---:|:----:|
| 1 | BTC |  2.4 |
| 2 | ETH | 0.92 |
| 3 | ADA | 2034 |

This file has to be converted into csv and located in the same folder as the .ipynb notebook file. 

At this point, the script takes the as an input csv file, integer money_invested and downloads data about first X (can be altered) cryptocurrencies from Coinmarketcap and makes the calculations.

Finally, the data are visualized in the following way:

*Investment: 2000\
*Current value: 8101.057\
*Profit in percentage: 405.05 %\
*Profit in euro: 6101.057 eur

|   | symbol | amount 1 | price_eur | current_value | % of portfolio |
|:-:|:------:|:--------:|:---------:|:-------------:|:--------------:|
| 0 |   BTC  |    0.1   |  9325.77  |    932.577    |      11.5      |
| 1 |   LTC  |     1    |   175.28  |     175.28    |      2.15      |
| 2 |   ETH  |    10    |   701.12  |     7011.2    |      86.35     |

