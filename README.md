# eBay-Project

* Conducted a thorough analysis of eBay's Presidents Day sale on select products to determine if the presence of an original list price influences the number of items sold
* Scraped all products on product page
* Gathered all the products URL's and wrote them to a file
* Opened the file and dowloaded each of items URL's into a folder where each file is named as the <item.id>.html so you click on each html file and route directly to each item
* Loop through each file in the folder and opens and parses them into a Python object identifying the seller name, seller score, item price, item price, list price, items sold, title, returns allowed(true / false), shipping price, condition (e.g., used, new, like new, seller refurbished, ...)
* Uploaded data that was extracted in the previous step to SQL database
* Convert any price (item price and shipping price) into a "dollar-cent" format (e.g., convert $12.34 into 1234 and $12 into 1200
* Evaluate data and determine whether original list price influences the number of items sold

## Tools
* Python, HTML, SQL
* Packages: BeautifulSoup, Regular Expressions
