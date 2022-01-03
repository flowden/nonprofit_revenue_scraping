# nonprofit_revenue_scraping

I wrote this code to scrape a list of environmental nonprofits' 2020 revenues
from GuideStar, which is the best nonprofit data repository. I used Pandas, 
BeautifulSoup, and Selenium webdrivers. I used the webdriver to log into my
paid Guidestar account and then navigate to the search bar using HTML tags.
I then searched for each nonprofit's name in the GuideStar search bar and accessed
its revenue from the search results. I formatted all revenues by removing commas,
dollar signs, and other characters. I scrapped additional metadata, including
gross receipts and assets as well. 
