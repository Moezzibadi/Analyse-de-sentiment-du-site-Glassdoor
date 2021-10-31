# Analyse-de-sentiment-du-site-Glassdoor
 
 The aim of this project is natural language processing and sentiment analysis applied to scraped reviews from employees. 

The notebook has three main parts : 

1) Glassdoor reviews scraping using Selenium

2) Naive Bayes classification for positive and negative reviews recognition

3) Latent Dirichlet Allocation [[1]](#1) for topic modeling (Not a suitable method for this application as mentioned in presentation - as an alternative one should use : *Biterm Topic Model* [[2]](#2)).

- To be able to run the scraping part, a *secret.json* file containing the log-in identification is needed.

- For extra information, you can find the Rmarkdown presentaion (in french) here : https://moezzibadi.github.io/Analyse-de-sentiment-du-site-Glassdoor/Proj_gl.html

## References
<a id="1">[1]</a> 
Blei D. et al. (2003).
Latent Dirichlet Allocation (LDA)
Journal of Machine Learning Research - Pages 993-1022.
https://www.seas.upenn.edu/~cis520/lectures/LDA.pdf

<a id="2">[2]</a> 
Xiaohui Yan et al. ( 2013). 
A biterm topic model for short texts
Proceedings of the 22nd international conference on World Wide Web - Pages 1445–1456.
https://doi.org/10.1145/2488388.2488514


