# Webscrapping

## Packages Using for Extracting Website content

## 1)News-Please


News-please is an open source, easy-to-use news crawler that extracts structured information from almost any news website. 
news-please combines the power of multiple state-of-the-art libraries and tools, such as scrapy, Newspaper, and readability. news-please also features a library mode, which allows Python developers to use the crawling and extraction functionality within their own program.

**News-please extracts the following attributes from news articles. An examplary json file as extracted by news-please can be found here.**
- headline
- lead paragraph
- main text
- main image
- name(s) of author(s)
- publication date
- language


***References***


1)https://github.com/fhamborg/news-please


2)https://pypi.org/project/news-please/

## 2)Scrapy


Scrapy is a Python framework for large scale web scraping. It gives you all the tools you need to efficiently extract data from websites,
process them as you want, and store them in your preferred structure and format.

***Methods for Extracting content***
- parse() − It will extract the links of our interest.
- response.urljoin − The parse() method will use this method to build a new url and provide a new request, which will be sent later to callback.
- parse_dir_contents() − This is a callback which will actually scrape the data of interest.


***Disadvantages***
- Steep learning curve
- Overkill for easy jobs
- Not beginner-friendly

***References***


1)https://www.analyticsvidhya.com/blog/2020/04/5-popular-python-libraries-web-scraping/


2)https://zetcode.com/python/urllib3/

## 3)Newspaper3k


The Newspaper3k package is a Python library used for Web Scraping articles, It is built on top of requests and for parsing lxml.
***Procedure***
1)First we will define a list containing the URLs or assign a single URL.
2)We will create an Article object passing in the parameters such as the name of the URL and optional parameters like language=’en’, for English
3)We will then download and parse the file.
4)Finally, display the data extracted.

***Newspaper3k extracts following:***

- Url
- Content
- Published Date
- Title

***References***


1)https://www.geeksforgeeks.org/scraping-websites-with-newspaper3k-in-pyth


2)https://blog.finxter.com/newspaper3k-a-python-library-for-fast-web-scraping/#:~:text=Newspaper3k%20is%20a%20Python%20library,while%20it%20parses%20for%20lxml%20.


## 4)Urllib And Request


URllib is a python package that combines several modules to preprocess the URLs, in other words, it is a library used for HTTP requests using python language 
on URLs

Urllib is a package that collects several modules for working with URLs, such as:

- urllib.request for opening and reading.
- urllib.parse for parsing URLs
- urllib.error for the exceptions raised
- urllib.robotparser for parsing robot.txt files

***References***


1)https://www.geeksforgeeks.org/python-urllib-module/


2)https://realpython.com/urllib-request/


## 5)RoboBrowser

***RoboBrowser is a simple, Pythonic library for browsing the web without a standalone web browser. RoboBrowser can fetch a page, click on links and buttons, and fill out and submit forms. If you need to interact with web services that don’t have APIs, RoboBrowser can help.***

***RoboBrowser combines the best of two excellent Python libraries: Requests and BeautifulSoup.***

***References***

1)https://robobrowser.readthedocs.io/en/latest/readme.html
