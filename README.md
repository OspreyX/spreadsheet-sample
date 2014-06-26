![](https://raw.github.com/oanda/apidocs/master/images/oanda_header.png)
=========

spreadsheet-sample
=======================

Sample Python app for creating an account snapshot file in Excel format.
Requires Python 2.7+, XlsxWriter 0.5.5+, and Requests 2.3.0+.
Note that as this script uses the "count" parameter in retrieving the recent transactions, it is rate limited to once every 60 seconds.

### Usage

~~~
python excel_account_snapshot SANDBOX|PRACTICE|TRADE account_id personal_access_token
~~~
