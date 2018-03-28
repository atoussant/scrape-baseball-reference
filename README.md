# scrape-baseball-reference
Scrapes Baseball Reference website for Cy Young voter information (table is commented out)

Baseball-reference (and other sports reference websites) comment out certain tables within their HTML. When HTML code is commented out the rvest package needs a few extra steps to retrieve the information. This code does exactly that. Although this was build for a specific case, the code could be easily generalized to scrape other tables from baseball-reference or basketball-reference websites, or any website that has tables listed under comments in their HTML.

