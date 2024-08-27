# WEB SCRAPING PROJECT
## Extracting and Analyzing School Performance Data
### Project Overview
This project involves the extraction of tabular data from a webpage using Python.

![front-view-academic-cap-with-books-pencils](https://github.com/user-attachments/assets/03a8476b-545c-4064-9b98-4ab92e75e1f3)

The **primary objective** was to automate the data collection process, clean and structure the extracted data, and prepare it for further analysis.

The data was sourced from the [official website of Moi Kapsowar Girls](https://moikapsowargirls.sc.ke/kcse-results-analysis/), specifically focusing on their KCSE results analysis.

### 🛠️ Tools and Libraries Used
- **Python**: Core programming language used for the project.
- **Requests**: To send HTTP requests and retrieve the webpage content.
- **BeautifulSoup**: For parsing the HTML content and locating the required tables.
- **Pandas**: For data manipulation, cleaning, and structuring the extracted data into DataFrames.
- **CSV**: To export the cleaned data into CSV files for further analysis.

### 📑 Project Structure
1. **Data Extraction**:
- The webpage was accessed using the requests library, and the HTML content was retrieved.
- The HTML content was parsed using BeautifulSoup to locate the two target tables on the webpage.

2. **Data Cleaning and Structuring**:
- The tables lacked headers, so appropriate column names were manually defined based on the data context.
- The first rows of the tables, which were not relevant to the analysis, were excluded from the final dataset.
- The data from each table was extracted, cleaned, and structured into pandas DataFrames.

3. **Data Export**:
- The cleaned DataFrames were exported as CSV files for further analysis.
- The CSV files were saved to a specified directory, ensuring the data was organized and easily accessible.

**NB: For a detailed step-by-step explanation, follow through in the attached [script!](http://localhost:8888/notebooks/Web%20Scrapping%20Project.ipynb)**

### Project Outcomes
This project demonstrates an efficient approach to web scraping and data extraction, highlighting the importance of data cleaning and preparation in the data analysis pipeline.

The extracted data is now structured and ready for deeper analytical insights, providing a solid foundation for subsequent data-driven decision-making.

### Future Enhancements
Future versions of the project will include an analysis of the extracted data, and generating summary statistics, visualizations, and reports.

### Conclusion
This web scraping project showcases the practical application of Python in automating data extraction and preparation tasks.
The techniques used here can be extended to other web scraping projects, emphasizing the value of clean, structured data in the analytical process.

#### Thank you!

😄
