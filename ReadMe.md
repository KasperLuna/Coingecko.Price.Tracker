# Python Coingecko Price Tracker:

1. download the latest Python install (https://www.python.org/downloads/)
2. install python (make sure to enable PATH variable in install)
3. download this repo as a ZIP and extract cgcryptrack.py
4. run the following commands in the directory with the python script to install dependencies:
	- `python -m pip install prettytable`
	- `pip install pycoingecko`
5. run the script with `python cgcryptrack.py` or double click the file.

## To edit displayed coins:
1. update the usd_coins (for USD pricing) or php_coins (for PHP Pricing) dictionaries with the following format
	- ``"TICKER" : "name-on-coingecko"`` 
- to find any token's name, use the coingecko url of the coin

