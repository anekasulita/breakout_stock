# breakout_stock
Finding stock from Indonesia Stock Exchange which are break-out.

The logic is simple. It looks for daily stock data, which is downloaded from www.dataharianbei.com 
the data is in CSV Format. 
The format is : 
<date>,<ticker>,<open>,<high>,<low>,<close>,<volume>

The break-out definition is :
- the latest stock closing price is maximum closing price during a period (a month)
- the latest daily volume is bigger than 1.5 * average volume during a period (a month)

the result is the descending list of stock with break-out criteria.

this list is helping investor to decide stock purchase in Indonesia Stock Exchange.
