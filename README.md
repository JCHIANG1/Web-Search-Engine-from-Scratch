## -Web-Search-Engine-from-Scratch
The search engine implementation contains the following components:
#### -1. Crawler: use the breadth-first strategy to crawl 5,000 pages. For this project I start crawling at "https://www.depaul.edu" 
and Perform a Web traversal using the BFS strategy that only crawl HTML pages.
#### -2. When crawling the page conduct link analysis that make sure the crawled links are (a)part of the domain, (b) (URL-)normalized, and (c)  not already traversed.
#### -3. Index: pre-processing the text(e.g. tokenization, case folding, stopword removal) and create an inverted index structure.
#### -4.Query Processing: Implement the Vector Space Model and use the TFIDF weighting, the ltc.ltn scheme 

Future work of this project, I would like to do more research on how to return more accurate link when given a query. I will continue to do more experiments on adjusting term weights to put more emphasis on title text, and read some materials about page rank to apply it into my work. Overall, I enjoy doing this project, because I learn more about web crawling, which I have never encounter before.
