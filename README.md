# nonprofit_revenue_scraping

I wrote this code to scrape a list of environmental nonprofits' 2020 revenues
from GuideStar, a comprehensive nonprofit data repository. I used Pandas, 
BeautifulSoup, and Selenium webdrivers. I used the webdriver to log into my
paid Guidestar account and then navigate to the search bar using HTML tags.
I then searched for each nonprofit's EIN (tax identification code) in GuideStar's
search bar and accessed its revenue from the search results. I also included a 
timer to have the code sleep for a moment to avoid the website from thinking I was
a bot. I formatted all revenues by removing commas, dollar signs,
and other characters. Finally, I scrapped additional metadata, including
gross receipts and assets as well. 
