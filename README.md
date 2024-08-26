# WEB SCRAPING PROJECT
## Extracting and Analyzing School Performance Data
### Project Overview
This project involves the extraction of tabular data from a generated webpage using Python.

The **primary objective** was to automate the data collection process, clean and structure the extracted data, and prepare it for further analysis.

The data was sourced from the [official website of Moi Kapsowar Girls](https://moikapsowargirls.sc.ke/kcse-results-analysis/), specifically focusing on their KCSE results analysis.

### Tools and Libraries Used
- **Python**: Core programming language used for the project.
- **Requests**: To send HTTP requests and retrieve the webpage content.
- **BeautifulSoup**: For parsing the HTML content and locating the required tables.
- **Pandas**: For data manipulation, cleaning, and structuring the extracted data into DataFrames.
- **CSV**: To export the cleaned data into CSV files for further analysis.

### Project Structure
1. Data Extraction:

The webpage was accessed using the requests library, and the HTML content was retrieved.

The HTML content was parsed using BeautifulSoup to locate the two target tables on the webpage.

2. Data Cleaning and Structuring:

The tables lacked headers, so appropriate column names were manually defined based on the data context.

The first rows of the tables, which were not relevant to the analysis, were excluded from the final dataset.

The data from each table was extracted, cleaned, and structured into pandas DataFrames.

3. Data Export:

The cleaned DataFrames were exported as CSV files for further analysis.

The CSV files were saved to a specified directory, ensuring the data was organized and easily accessible.

**NB: For a detailed step-by-step explanation, follow through in the attached [script!](http://localhost:8888/notebooks/Web%20Scrapping%20Project.ipynb)**

#### Thank you!

😄
