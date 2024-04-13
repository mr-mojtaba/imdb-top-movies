IMDB Top Movies<a name="TOP"></a>
===================

A Python project utilizing the Scrapy framework for crawling the IMDb website, extracting the list and details of the top 250 movies, and storing the extracted data in a JSON, CSV or XML file.

- - - -

![picture alt](https://github.com/mr-mojtaba/imdb-top-movies/blob/main/media/sample.png "1000x800" "Title is optional")

### Python and package used:
Name  | Version
-------- | --------
Python | 3.12.0
Scrapy | 2.11.1

### How to use:
1- Navigate to the spiders directory path.

2- Execute the spider using the command associated with the desired output file format.

For JSON file:
```sh
scrapy runspider top_250_movies.py -o top_250_movies.json -t json 
```

For CSV file:
```sh
scrapy runspider top_250_movies.py -o top_250_movies.scv -t csv 
```

For XML file:
```sh
scrapy runspider top_250_movies.py -o top_250_movies.xml -t xml 
```
