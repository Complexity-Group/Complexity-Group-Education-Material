# search-filters-tool

A lightweight, client-side search and filter tool that pulls structured data from Google Sheets and displays dynamic, searchable results in the browser.

## Search + Filters Tool

This project provides a flexible and interactive interface for exploring datasets using keyword search and multiple filters.

The tool allows users to:

- Search records using multiple keywords
- Filter by concept, format, difficulty, publisher, and author
- Narrow results using a dual-range year slider
- View tagged concepts for each result
- Open linked documents directly from results
- Automatically update when the Google Sheet is modified

## How It Works

- Data is stored in a public Google Sheet  
- The sheet is published as a CSV  
- JavaScript fetches and parses the CSV using PapaParse  
- Filter options are generated dynamically from the dataset  
- Results are filtered and rendered in real time on the page  

## Deployment

This tool is fully client-side and can be embedded into any website.

### Steps:

1. Publish your Google Sheet to the web as a CSV  
2. Copy the Google Sheets CSV URL  
3. Replace the `csvUrl` variable in the script with your link  
4. Paste the HTML file into your site (or host it separately)  
5. Open in browser or embed (e.g., Squarespace Code Block)  

## Updating Data

No code changes are needed to update content.

- Simply edit the Google Sheet  
- Keep column headers consistent  
- Changes will automatically reflect on refresh  

## Technologies Used

- HTML  
- CSS  
- JavaScript  
- PapaParse  
- Google Sheets  
