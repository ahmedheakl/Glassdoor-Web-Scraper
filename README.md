# Glassdoor-Web-Scraper
This code is used to get all of the job information from Glassdoor website.

# Technologies
I used Selenium to extract the valuable information about jobs such as salaries, company informations, rating ... etc. I couldn't use Beautifulsoup library as it is dependent on the get request method which I couldn't use here because every job in a different tab, and I have to navigate through all of them. 

# How to use
You can go to the main.py file and add in your attribute and run the file and it will automatically run the scraper function for you. Just don't forget to include the chromedriver.exe file in the same directory as the main.py and scraper.py files. The dataframe created by scraper function will be saved as an csv file in the csv_saved directory, which can be used later for data analysis purposes. 
