# Web_scraping_companies
Scraping over 1400 company websites.

This scraper imports a list with the names of more than 1400 companies. Using Selenium, the loop iterates through each one of the company names, automating the following tasks: 

1- Type the company's name in the Google search box.

2- Look for the company's website and click on it. 

3- Inside the company's website, it looks for the Modern Slavery Statement, and if it finds it, it will return the link. If it doesn't find it, it will print 'No document found'.

4- Return a list of company names, websites accessed and links to the statement, if found.
