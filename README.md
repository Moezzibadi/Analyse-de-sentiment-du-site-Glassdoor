# Analyse-de-sentiment-du-site-Glassdoor
 
 The aim of this project is natural language processing and sentiment analysis applied to scraped reviews from employees. 

The notebook has three main parts : 

1) Glassdoor reviews scraping using Selenium

2) Naive Bayes classification for positive and negative reviews recognition

3) Latent Dirichlet Allocation for topic modeling (Not a suitable method for this application as mentioned in presentation - as an alternative one should use : *Biterm Topic Model*)[[1]](#1).

- To be able to run the scraping part, a *secret.json* file is needed.

- For extra information, you can find the Rmarkdown presentaion (in french) here : https://moezzibadi.github.io/Analyse-de-sentiment-du-site-Glassdoor/Proj_gl.html

## References
<a id="1">[1]</a> 
Dijkstra, E. W. (1968). 
Go to statement considered harmful. 
Communications of the ACM, 11(3), 147-148.
