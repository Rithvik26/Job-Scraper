# Job-Scraper

JOB SCRAPER: Job search Automation ( Python, BeautifulSoup and Selenium ).

-->Used BeautifulSoup to extract the HTML and parse it,with the help of find and find_all functions to identify and iterate over each job listing of the websites like https//in.indeed.com,as it has a standardized URL,and finally stored and saved the result job lists into a DataFrame like excel from where users can select based on their interests.Finally included all these funcions into a single function for user comfort while using.

-->For some websites in the URL there wasn’t a consistent pattern with the keyword arguments.So,Used Selenium Webdriver to interact with the website to enter the job title and location specified, and to retrieve the search results.Basically generalizing for all websites.
