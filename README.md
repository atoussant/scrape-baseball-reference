# Scrape-baseball-reference
Scrapes Baseball Reference website for Cy Young voter information (table is commented out)

Baseball-reference (and basketball-reference) comment out certain tables within their HTML. When HTML code is commented out the rvest package needs a few extra steps to retrieve the information. This code does exactly that. The code above will scrape Cy Young Award voting records from 2015-2017 for both the American League and National League.

Although this was built for a specific case, the code could be easily generalized to scrape other tables from baseball-reference or basketball-reference websites, or any website that has tables listed under comments in their HTML. One would look within the HTML for the name of the table in the comments and switch it with the 'table#AL_CYA_voting' html_node listed here.

