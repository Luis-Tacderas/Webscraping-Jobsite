# Webscraping-Kaiser Permanente Job Page
## pip install selenium
## For chrome you first need to download the webdriver at https://chromedriver.chromium.org/downloads.

# About this project
## Summary
A webscraping project written in Python using Jupyter Notebooks to collect open "Data 0Reporting and Analytics Consultant" near Pleasanton, CA in KP.
I came up with this project to automate my job search within Kaiser Permanente by comparing my list of jobs I already applied for to all open positions
so I may know which ones I may apply to.

## Challenges
https://www.kaiserpermanentejobs.org/search-jobs data entry of location is using auto-complete capability which I have not yet found how to implement in Selenium.

## Conclusions
TBD

## Cool Techniques
Web scraping using Selenium

pandas

## What Else I might have done
1. Able to figure out the location auto complete and be able to enter process multiple locations and mulyiple keywords.
2. Add capability to go  though all the pages and capture all openings, for now I am only doing the first page.
3. Click on the open position;s and scrape the salary min max values
4. Analyze the average salary for different levels and compare to data from Glassdoor or other job sites (web scrape as well) or any 3rd party datasets available
   to see how KP's salary offer compares to the rest of the industry.
5. Store my list of jobs already appied for in MySQL. Add ability to scrape the status of positions I have applied for and update my the MysQL DB. Create a flask api
   for the MySQL or PostGres or MongoDB for CRUD operations.
   

