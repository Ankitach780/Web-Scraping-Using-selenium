# Web Scraping Projects using Selenium

This repository contains two web scraping projects using Selenium. The first project scrapes a list of companies, and the second one collects IPL points table data.

## 1. **Company Data Scraping**

This project uses Selenium to scrape company data from the AmbitionBox website. It extracts information about various companies, including:

- Company Name
- Rating
- Location
- Reviews
- Salary
- Job Opportunities

### Features:
- Scrapes data from multiple pages.
- Handles dynamic content loading by scrolling and waiting for elements.
- Saves data in CSV format.

### Installation:

1. Install required dependencies:
    ```bash
    pip install selenium pandas
    ```

2. Ensure you have the appropriate driver for your browser (e.g., ChromeDriver for Chrome).

3. Run the script to start scraping the company data:
    ```bash
    python scrape_companies.py
    ```

### Example Output (CSV):

The data is saved in `company_data.csv` with columns like:

- Company Name
- Rating
- Location
- Reviews
- Salary
- Jobs

---

## 2. **IPL Points Table Scraping**

This project scrapes IPL points table data for the years 2008 to 2024 from the official IPL website. It collects information about:

- Year
- Position in the table
- Team name
- Matches played

### Features:
- Scrapes data for each year from 2008 to 2024.
- Extracts data from the points table.
- Prints and stores relevant data.

### Installation:

1. Install required dependencies:
    ```bash
    pip install selenium
    ```

2. Ensure you have the appropriate driver for your browser (e.g., ChromeDriver for Chrome).

3. Run the script to start scraping the IPL points table:
    ```bash
    python scrape_ipl_points.py
    ```

### Example Output:

For each year, the following data will be printed for each team:

- Year
- Position
- Team Name
- Matches Played

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

