# 🕸️ WEB SCRAPING PROJECT
## Extracting and Analyzing School Performance Data
### Project Overview
This project involves the extraction of tabular data from a webpage using Python.

The **primary objective** was to automate the data collection process, clean and structure the extracted data, and prepare it for further analysis.

### Data Source
The data was sourced from the [official website of Moi Kapsowar Girls](https://moikapsowargirls.sc.ke/kcse-results-analysis/).

### 🛠️ Tools and Libraries Used
- **Jupyter Notebook**: Interactive environment used for writing, testing, and documenting the code.
- **Python**: Primary programming language utilized.
- **Requests**: Library used to send HTTP requests and retrieve the HTML content of the webpage.
- **BeautifulSoup**: HTML parser employed to extract the specific kcse result tables.
- **Pandas**: Library used to manipulate, and organize the extracted data into DataFrames.
- **CSV**: Format used to export the final data for storage and further analysis.

### 📂 Files
1. [Project Notebook File](https://github.com/patriciavalentine/KCSE-RESULTS-WEB-SCRAPING/blob/main/Web%20Scraping%20Project.ipynb). 
2. [First Extracted Data](https://github.com/patriciavalentine/KCSE-RESULTS-WEB-SCRAPING/blob/main/KCSE%202020%20RESULTS%20ANALYSIS.csv).
3. [Second Extracted Data](https://github.com/patriciavalentine/KCSE-RESULTS-WEB-SCRAPING/blob/main/KCSE%202021%20RESULTS%20ANALYSIS.csv).

## THE PROCESS

![front-view-academic-cap-with-books-pencils](https://github.com/user-attachments/assets/03a8476b-545c-4064-9b98-4ab92e75e1f3)

### 💻 Project Structure:
1. **Data Extraction**.
- The webpage was accessed using the requests library, and the HTML content was retrieved.
- The HTML content was parsed using *BeautifulSoup* to locate the two target tables on the webpage.

2. **Data Cleaning and Structuring**.
- The tables lacked headers, so appropriate column names were manually defined based on the data context.
- The first rows of the tables, which were not relevant to the analysis, were excluded from the final dataset.
- The data from each table was extracted, cleaned, and structured into *pandas* DataFrames.

3. **Data Export**.
- The cleaned DataFrames were exported as CSV files for further analysis.
- The CSV files were saved to a specified directory, ensuring the data was organized and easily accessible.

**NOTE:**

**For a detailed step-by-step explanation, follow through in the attached [notebook file!](http://localhost:8888/notebooks/Web%20Scrapping%20Project.ipynb)**

### Project Outcomes
The extracted data is now structured and ready for deeper analytical insights, providing a solid foundation for subsequent data-driven decision-making. The future versions of this project will include an analysis of the extracted data, and generating summary statistics, visualizations, and necessary reports.

*This web scraping project showcases the practical application of Python in automating data extraction and preparation tasks.
The techniques used here can be extended to other web scraping projects, emphasizing the value of clean, structured data in the analytical process.*

## THE END.
### Thank you!
💙
