Discussion Questions:


Why is pagination important for large datasets?
Answer: 1. Pagination breaks the data into smaller and more manageable pieces, reducing the server load and speeding up response times.
        2. Pagination offers an easier way to view data, allowing users to navigate through pages efficiently.
        3. Pagination minimizes data transfer by only loading the current page, saving bandwidth and data costs.


How would you customize items per page dynamically?
Answer:


What happens if page is invalid?
Answer: If the page number is not an integer, less than 1, or greater than the total number of pages, get_page() will not raise an error. 
    Instead:

        It returns the first page if the page number is invalid or less than 1 and it returns the last page if the page number is greater than the total number of pages.