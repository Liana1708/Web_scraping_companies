# Web_scraping_companies_Modern_Slavery
Scraping over a 1000 company websites.

This scraper imports a list with the names of more than 1000 companies. Using Selenium, the loop iterates through each one of the company names, automating the following tasks: 

1- Type the company's name in the Google search box.

2- Look for the company's website and click on it. 

3- Inside the company's webpage, it looks for the Modern Slavery Statement, and if it finds it, it returns the link. If it doesn't find it, it will print 'No statement found'. 

4- Return a list of company names, websites accessed and links to the Modern Slavery Statement, if found. 
