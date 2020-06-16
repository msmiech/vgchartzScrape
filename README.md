# vgchartz scraper
This is a fork of vgchartzfull, a python script based on BeautifulSoup.
It creates a dataset based on data from 
http://www.vgchartz.com/gamedb/

This fork uses the requests module instead of urllib. It also retries to download the page data if it fails. There are also constants for configuration at the top of the script. Also, it uses the HTTPS URL instead of the HTTP one.

The BeautifulSoup module is required.
It can be installed by pip.

sudo pip install BeautifulSoup

Thanks to Chris Albon.
http://chrisalbon.com/python/beautiful_soup_scrape_table.html

Improvements based on
https://www.statworx.com/at/blog/web-scraping-101-in-python-with-requests-beautifulsoup/