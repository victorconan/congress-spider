# congress-spider
A python scraper to scrape legislation info from US Congress (https://www.congress.gov/)

This is a small web scraper based on Python 2.7 to scrape the legislation info from US Congress and store the data to MySQL database.

The program will scrape the following info from US Congress:

- Legislation code. e.g H.R.6534 
- Congress. e.g. 114th Congress
- Legislation bill name. e.g. OPEN Act
- Sponsor. e.g. Rep. Cartwright
- Committees. e.g. House-Transportation and Infrastructure
- Cosponsors. e.g. Rep. Culberson
- Status. e.g. 11/17/2016 Referred to House Administration

To run this program, you need the following python packages:

- Beautiful Soup
- MySQLdb

Compatibility: python 2.7.12
