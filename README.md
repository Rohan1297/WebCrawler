# WebCrawler

Web crawling and web scraping are two different but related concepts. Web crawling is a component of web scraping, the crawler logic finds URLs to be processed by the scraper code.
A web crawler starts with a list of URLs to visit, called the seed. For each URL, the crawler finds links in the HTML, filters those links based on some criteria and adds the new links to a queue. All the HTML or some specific information is extracted to be processed by a different pipeline.
In this assignment I will be building a distributed web crawler in Python using two libraries: requests and Beautiful Soup.
To build a simple web crawler in Python we need at least one library to download the HTML from a URL and an HTML parsing library to extract links. Python provides standard libraries urllib for making HTTP requests and html.parser for parsing HTML.

The standard Python libraries for requests and HTML parsing are not very developer-friendly. Other popular libraries like requests, branded as HTTP for humans, and Beautiful Soup provide a better developer experience.

Required Tools:

Python3
Pip
Beautiful Soup and Requests libraries
Visual Studio code or any IDE
