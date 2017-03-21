
# Python web tutorials
*Make use of internet with Python* 

## List of tutorials

* [Making HTTP requests](Making_HTTP_requests.ipynb) - how to get data from Internet with Requests library
* [HTML and JSON processing](HTML_and_JSON_processing.ipynb) - basic operations with HTML and JSON
* [Simple HTTP server](Simple_HTTP_server.ipynb) - how to run simple HTTP server

## Lessons

### Lesson 1

#### Based on Tutorials

* [Making HTTP requests](Making_HTTP_requests.ipynb)
* [HTML and JSON processing](HTML_and_JSON_processing.ipynb)

#### Task 1

1. Obtain numerical data from any API - most of the APIs will require to sign up. Example APIs:
    * [Oanda](https://www.oanda.com/) - Forex market prices API
    * [Open Notify](http://open-notify.org/) - open source project to provide a simple programming interface for some of NASA’s       awesome data

2. Record short history from the API via for loop with defined sampling (sleep function will be enough, no need to use cron).
3. Plot the data.
4. Do something with data (calculate autocorrelation function, remove trend, estimate mean value na standard deviation, try to predict data with any simple model).

#### Task 2

For this task use HTMLParser of ElementTree XML API. Data can be obtained with Requests library.

1. Download data from any wiki page (where is enough conent, for example: https://en.wikipedia.org/wiki/Linear_discriminant_analysis)
2. Print out the most import paragraphs of wiki page content.
3. Print out all references - pairs of `href` content (link) and `<a></a>` content (displayed text) 
4. Make some operations with the page content (most important paragraphs) - histogram of used words, count of individual letters, etc.


### Lesson 2

#### Based on Tutorials

* [Making HTTP requests](Making_HTTP_requests.ipynb)
* [HTML and JSON processing](HTML_and_JSON_processing.ipynb)
* [Simple HTTP server](Simple_HTTP_server.ipynb)

#### Task 1

1. Create simple server
