Web Scraping of Internshala Data
Project Overview
This project focuses on web scraping internship data from Internshala, one of India’s leading platforms for internship and job listings. The main goal is to automate the process of collecting relevant internship listings based on specific keywords and store them in a structured format for further analysis or use.

--------------------------------------------------------------------------------------------------------------------------

✅ Features Implemented
•	Scraping internship listings using search keywords.
•	Extracting data such as:
o	Internship title
o	Company name
o	Location
o	Start date
o	Duration
o	Stipend
o	Posted date
o	Internship type
•	Saving the scraped data into a CSV file.
•	Implemented pagination handling to retrieve data from multiple pages.
•	Data cleaning and formatting for better readability.

--------------------------------------------------------------------------------------------------------------------------

🛠️ Libraries Used
•	requests – to send HTTP requests to Internshala’s site.
•	BeautifulSoup – for parsing and navigating HTML content.
•	pandas – to store, clean, and export data into a CSV format.
•	time – to manage delays between requests (to avoid overloading the server).

--------------------------------------------------------------------------------------------------------------------------


🧠 Steps and Workflow
1.	Import Required Libraries
Loaded all essential Python libraries needed for HTTP requests, parsing HTML, and managing datasets.
2.	Define Search Query
User inputs a search keyword (e.g., "Data Science") to scrape internships related to that domain.
3.	Construct URL and Handle Pagination
Used the search term to dynamically build URLs on Internshala (e.g., https://internshala.com/internships/keywords-data-science) and iterate through multiple pages of results.
4.	Send HTTP Requests
Employed the requests library to fetch the HTML content from Internshala pages.
5.	Parse HTML Using BeautifulSoup
Extracted internship data by identifying key HTML tags and class names.
6.	Store Extracted Data
Collected the relevant fields and stored them in a pandas DataFrame.
7.	Clean the Data
Applied basic text formatting and cleaned inconsistencies in extracted information.
8.	Export to CSV
Saved the final cleaned data to a CSV file (internshala_internships.csv) for future use.

--------------------------------------------------------------------------------------------------------------------------


📁 Output
The final output of the project is a CSV file containing internship data with all essential fields, neatly organized for further analysis or reporting.

--------------------------------------------------------------------------------------------------------------------------


📌 Disclaimer
This project is for educational purposes only. Internshala’s Terms of Use must be respected. Always ensure web scraping activities are in compliance with the target website's robots.txt and usage policies.
