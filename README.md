# Web Scraping Utility

This Python script is designed to fetch links from Google search results, scrape HTML tables from those links, and convert them to CSV format. Additionally, it scrapes paragraphs from web pages and appends them to a Word document.

## Usage

1. **Install Dependencies**: Make sure you have the required dependencies installed. You can install them using pip:

    ```
    pip install beautifulsoup4 requests python-docx pandas
    ```

2. **Run the Script**: Execute the `main()` function in the script. This function prompts the user to enter a search query, fetches relevant links from Google, scrapes tables from those links, and saves them to CSV files. It also scrapes paragraphs from the web pages and appends them to a Word document.

    ```
    python script.py
    ```

3. **Output Files**:
    - `demo.csv`: CSV file containing the scraped tables.
    - `paragraphs.docx`: Word document containing the scraped paragraphs.

## Notes
- Ensure you have an active internet connection for fetching links and scraping web content.
- Some websites may have restrictions on web scraping. Respect the terms of service of the websites you are scraping.
- Modify the script according to your requirements or specific use case.

## Dependencies
- [Beautiful Soup](https://pypi.org/project/beautifulsoup4/): For parsing HTML and XML documents.
- [Requests](https://pypi.org/project/requests/): For making HTTP requests.
- [python-docx](https://python-docx.readthedocs.io/en/latest/): For creating and updating Microsoft Word (.docx) files.
- [Pandas](https://pypi.org/project/pandas/): For data manipulation and analysis.

---
