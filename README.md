# Web Scraping Script

This repository contains a Python script for **web scraping** as part of my learning journey in Python programming. The script extracts tabular data from a website and saves it into a clean and structured CSV file.
## Data Source

The data for this project has been scraped from the following publicly available source:

**[Fortune Global 500 List on Wikipedia](https://en.wikipedia.org/wiki/Fortune_Global_500)**
---

## Table of Contents
1. [Overview](#overview)
2. [Technologies Used](#technologies-used)
3. [Learnings](#learnings)
4. [Next Steps](#next-steps)


---

## Overview

This project uses **BeautifulSoup** and **Pandas** to:
1. Extract tabular data from an HTML page.
2. Parse and clean the extracted data.
3. Save the data into a structured **CSV file**.

The script can handle HTML tables efficiently, manipulate data, and save outputs without duplication or permission issues.

---

## Technologies Used

- **Python** (3.x)
- **BeautifulSoup**: To parse HTML content.
- **Requests**: To fetch web pages.
- **Pandas**: To create and manipulate the dataframe.
- **Jupyter Notebook**: For interactive coding and debugging.

---

## Learnings

Through this project, I learned:

1. **Web Scraping Basics**: 
   - Using the `requests` library to fetch web pages.
   - Parsing HTML content using `BeautifulSoup`.

2. **Data Cleaning and Manipulation**: 
   - Working with **Pandas DataFrames** to clean, organize, and analyze extracted data.

3. **File Handling**: 
   - Saving DataFrames to a CSV file using `to_csv()` while handling common errors like `PermissionError`.

4. **Error Handling**: 
   - Implementing error-handling mechanisms to ensure smooth execution during repeated runs.

5. **Code Organization**: 
   - Writing clean, modular, and reusable code for web scraping tasks.

---

## Next Steps

To enhance this project further, I plan to:

1. **Dynamic Page Scraping**:  
   - Add functionality to scrape multiple pages dynamically based on user input or pagination.

2. **Automating the Script**:  
   - Schedule the script to fetch and update data regularly using automation tools like `cron` jobs or task schedulers.

3. **Data Visualization**:  
   - Visualize the extracted data using libraries such as `Matplotlib` or `Seaborn` to generate meaningful insights.

4. **Error Handling Enhancements**:  
   - Include more robust error handling for:
     - **Network Issues**: Handling timeouts and failed requests.
     - **Missing or Malformed Data**: Skipping bad rows while logging issues.

5. **Export Options**:  
   - Add support to export data to other formats like **Excel** or **JSON**.

6. **Documentation Improvements**:  
   - Enhance the README with visuals such as sample data screenshots or diagrams to improve clarity.

---

