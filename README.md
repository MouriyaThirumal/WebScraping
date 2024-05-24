# WebScraping

Web scraping involves extracting data from websites and transforming it into a structured format for analysis or use in other applications. Here is a detailed breakdown of the web scraping process in this project:

Step 1: Sending a Request
We use the requests library to send an HTTP request to the target website. This allows us to retrieve the HTML content of the web page.

Step 2: Parsing HTML Content
BeautifulSoup is used to parse the HTML content. It helps us navigate the HTML structure and extract the required data elements.

Step 3: Extracting Data
Using BeautifulSoup's methods, we locate the specific HTML elements that contain the data we are interested in.

Step 4: Structuring Data
The extracted data is then structured into a Pandas DataFrame, making it easier to manipulate and analyze.

#Data Cleaning

The extracted data undergoes a cleaning process to ensure its quality and usability. This involves:

Parsing the HTML content using BeautifulSoup.
Extracting the relevant information and structuring it into a Pandas DataFrame.

Handling Null Values:
During the data cleaning process, null values were encountered. Instead of dropping these null values, they were retained to preserve the integrity of the dataset. Removing null values could lead to loss of critical information and potential bias in the analysis.

No Duplicate Values:
The dataset has been carefully checked for duplicate values. Any duplicates identified during the cleaning process were removed to ensure that each entry in the dataset is unique and accurate.

