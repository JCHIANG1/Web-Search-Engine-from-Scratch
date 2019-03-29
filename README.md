Short video for the code walk through and high level explanation of the crawler structure: https://www.youtube.com/watch?v=5JcaJYhVukk&feature=youtu.be

## -Web-Search-Engine-from-Scratch
The search engine implementation contains the following components:

#### -1. Crawler: 
the crawler is implement with the breadth-first strategy started from "https://www.depaul.edu" to crawl 5,000 pages with no duplication.

#### -2. Link analysis: 
When crawling the page make sure the crawled links are (a)part of the depaul domain, (b) (URL-)normalized, and (c) not already traversed.

#### -3. Index: 
pre-processing the text(e.g. tokenization, case folding, stopword removal) and create an inverted index structure.

#### -4.Query Processing: 
Implement the Vector Space Model and use the TFIDF weighting, the ltc.ltn scheme 

#### -5. Return the top 10 most relevant links

Future work of this project, I would like to do more research on how to return more accurate link when given a query. I will continue to do more experiments on adjusting term weights to put more emphasis on title text, and read some materials about page rank to apply it into my work. Overall, I enjoy doing this project, because I learn more about web crawling, which I have never encounter before.
