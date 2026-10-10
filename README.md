# Digital-Books-Publishing-Analytics


##  Project Overview

Digital Book Publishing Analysis is a data analytics project that explores book ratings, popularity, publishing trends, formats, genres, and authors using data collected from Goodreads.
The project uses web scraping, data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization to identify patterns and insights in book-related data.

##  Objectives

- Collect book information from Goodreads using web scraping.
- Clean and preprocess the collected dataset.
- Analyze book ratings, popularity, genres, formats, and publication trends.
- Explore relationships between book-related variables.
- Apply statistical techniques to investigate average book ratings.
- Present meaningful insights through visualizations.

## Technologies Used

- **Python** – Programming and analysis
- **Requests** – Sending HTTP requests
- **BeautifulSoup** – Parsing HTML content
- **Selenium** – Browser automation and webpage extraction
- **Pandas** – Data cleaning and manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **SciPy** – Statistical calculations and hypothesis testing
- **Jupyter Notebook** – Development and analysis environment

##  Dataset Description

The dataset contains approximately 600 book records collected from Goodreads.

| Column | Description |
|---|---|
| `Title` | Name of the book |
| `Author` | Book author |
| `Average_Rating` | Average reader rating |
| `Rating_Count` | Number of ratings received |
| `List_Score` | Score associated with the Goodreads list entry |
| `Total_Votes` | Number of votes associated with the list entry |
| `Book_URL` | Link to the book's Goodreads page |
| `Pages` | Number of pages |
| `Format` | Book format, such as Hardcover or Paperback |
| `Publication_Date` | Original publication date |
| `Genres` | Genres associated with the book |
| `Publication_Year` | Year derived from the publication date |

##  Project Workflow

1. **Web Scraping:** Collected book details from Goodreads list pages and individual book pages.
2. **Data Collection:** Extracted book titles, authors, ratings, rating counts, list information, page counts, formats, publication dates, and genres.
3. **Data Cleaning:** Examined missing values, converted data types, handled unavailable values, and prepared the dataset for analysis.
4. **Exploratory Data Analysis:** Investigated distributions, patterns, and relationships among book attributes.
5. **Data Visualization:** Created charts to communicate findings and identify trends.
6. **Statistical Analysis:** Used correlation analysis and hypothesis testing to explore relationships and evaluate a claim about the mean book rating.

   
##  Insights

1. Fiction is the most common genre in the dataset, followed by other popular categories such as Fantasy and Classics. This shows that the selected Goodreads books are largely concentrated in popular literary and fictional genres.
2. Paperback is the most common book format in the dataset, followed by Hardcover and Mass Market Paperback. Kindle Edition and ebook formats are less common, while Board book appears only rarely. This shows that physical book formats, especially Paperback, dominate the selected Goodreads books.
3. 2000 decade records highest books published.
4. List Score and Total Votes have a perfect positive correlation (1.00), meaning they move together in this dataset. The publication year and number of pages have the least relationship between them.













