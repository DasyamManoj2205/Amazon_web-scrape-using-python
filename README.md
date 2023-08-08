# Amazon_web-scrape-using-python
## Web Scraping
  It is the process of parsing and extracting data from websites. We can scrape data using different tools like Beautiful Soup,Pandas etc.,
## Steps :
  # Here’s a summary of the steps we have followed to build Amazon Web scraper:
  1. Firstly, we outlined, What data do we need? What should be the format of that data? What does each column represent?
  2. We imported all the required Python libraries like Beautiful Soup, Requests, Pandas and numpy.
  3. We scraped Title, Price,Rating, Review count and availabity by parsing the HTML content using beatuiful soup and created functions.
  4. Craete a soup object containing all the data and fetch the required tag objects
  5. Loop for each link for extracting the product details by calling the functions we created earlier
  6. All the data we have appened into dictonary, we have used pandas to create data frame
  7. DataFrame is a 2-dimensional labeled data structure with columns of potentially different types. With the use of data frames we have dropped na values
  8. Finaly, we have converted the data into csv format.
