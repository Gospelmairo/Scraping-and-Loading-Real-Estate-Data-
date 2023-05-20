# Web-Scraping-Real-Estate-Data
This project involves scraping real estate data from the website "https://nigeriapropertycentre.com/" for properties listed for rent in Lagos State. The scraped data will be extracted and loaded into a PostgreSQL database. The data to be extracted includes room information, property description, prices, number of bedrooms, bathrooms, toilets, parking availability, and contact details.

## Scraping Process
1. Website: The target website for scraping is "https://nigeriapropertycentre.com/".
2. Scope: The scraping will be focused on properties listed for rent in Lagos State.
3. Number of Pages: The first 700 pages of listings will be scraped, with each page containing 24 listings.
4. Total Listings: The expected outcome is more than 10,000 listing records.
5. Data Extraction: The following information will be extracted for each property listing:
<ul><li>Room type
<li>Property description
<li>Price
<li>Number of bedrooms
<li>Number of bathrooms
<li>Number of toilets
<li>Parking availability
<li>Contact details <ul/>

## Database Setup

1. Database: PostgreSQL will be used to store the extracted data.
2. Schema: Create a schema in the PostgreSQL database to store the real estate data.
3. Tables: Create a table within the schema to store the extracted data, with appropriate column names and data types for each field.
