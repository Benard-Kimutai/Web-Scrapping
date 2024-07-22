# Web-Scrapping

# Dental Clinics in Nairobi, Kenya - Web Scraping Project

## Project Overview
This project aims to collect data on dental clinics in Nairobi, Kenya, using web scraping techniques. The data is extracted from Google search results and includes information on clinic names, ratings, locations, and phone numbers. The collected data is saved into an Excel file for further use.

## Objectives
- Collect detailed information about dental clinics in Nairobi.
- Store the data in a structured format for easy access and future analysis.

## Tools and Libraries Used
- Selenium: For web scraping and automated browser interactions.
- Pandas: For data manipulation and storage.
- Chrome WebDriver: To control the Chrome browser for scraping.
  
 ## Data Collection Process
- Web Scraping Setup: Initialize Selenium with Chrome WebDriver.
- Navigate to Google Search: Perform a Google search for dental clinics in Nairobi.
- Extract Data: Scrape clinic names, ratings, locations, and phone numbers from the search results.
- Pagination Handling: Iterate through multiple pages of search results to gather a comprehensive list.

## Project Structure
- `scraper.py`: The main script for performing web scraping and saving data.
- `Dental.Clinic_datas.xlsx`: The Excel file where the scraped data is stored.

## Notes
- The script navigates through multiple pages of Google search results to gather comprehensive data.
- I ensured that my internet connection was stable during the scraping process to avoid interruptions.

 ## Insights and Applications
- For Patients: Helps in identifying top-rated dental clinics, their locations, and contact information for appointments.
- For Healthcare Providers: Provides competitive analysis and insights into the distribution of dental services in Nairobi.
- For Researchers: Offers a dataset for further studies on healthcare accessibility and service quality in urban areas.
  
 ## Conclusion
The web scraping project successfully collected and organized data on dental clinics in Nairobi, Kenya. This dataset can serve multiple purposes, from helping patients find the best services to enabling researchers to analyze healthcare trends. The case study highlights the importance and effectiveness of web scraping in gathering valuable data from online sources.
