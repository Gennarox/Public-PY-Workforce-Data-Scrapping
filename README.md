# Public Workforce Data Scraping & Optimization  

## Overview  
This project focuses on extracting, processing, and storing publicly available workforce data from Paraguay’s government portal. Using **Python**, it automates the download of data files, processes the extracted information, and uploads it to a **SQL Server database** for further analysis.  

Designed as a hands-on exercise to enhance my skills in **web scraping**, **data engineering**, and **database management**, this project showcases a complete workflow from data ingestion to storage optimization.  

---

## Features  

### 1. Web Scraping  
- Utilizes **Selenium WebDriver** and **BeautifulSoup** to extract HTML data from a JavaScript-based website.  
- Automates downloading `.csv.zip` files containing workforce data.  
- Handles custom file renaming for specific timeframes (current, month-over-month, and year-over-year).  

### 2. Data Processing  
- Unzips, validates, and formats CSV files to ensure schema consistency.  
- Processes large datasets using chunked operations to optimize memory usage.  

### 3. Database Integration  
- Creates and manages **SQL Server** tables dynamically for incoming datasets.  
- Inserts data in chunks for efficiency, handling millions of records per operation.  

---

## Tools & Technologies  

- **Programming Languages**: Python  
- **Libraries**:  
  - **Selenium**, **BeautifulSoup**: Web scraping  
  - **Pandas**: Data manipulation  
  - **SQLAlchemy**, **pyodbc**: Database integration  
- **Database**: SQL Server  
- **Others**: Requests, ZipFile, io, time  

---

## Repository Contents  

- **WebScrapping.ipynb**: Contains scripts for downloading and managing data files from the web.  
- **MainScript.ipynb**: Handles the end-to-end process of data ingestion and integration with the SQL database.  
- **Funciones.ipynb**: Defines reusable functions for data validation, transformation, and database insertion.  

---

## Key Takeaways  

- Streamlined workflow to handle large public datasets efficiently.  
- Leveraged Python for automation, reducing manual data management.  
- Gained deeper insights into workforce trends by preparing data for advanced analytics.  

---

## How to Run  

1. Install dependencies from `requirements.txt`.  
2. Set up a local or remote SQL Server instance with proper configurations.  
3. Update file paths and connection strings in the scripts as necessary.  
4. Run the notebooks sequentially:  
   - Start with **WebScrapping.ipynb** to download and process data files.  
   - Execute **MainScript.ipynb** to upload data to the SQL database.  

---

## Author  

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/ivangennaro) or share feedback on this project.  

