# Movie Search Engine using Elasticsearch

This project is about creating a movie search engine using Elasticsearch and Python. It presents the results to the user using Machine Learning. It was made during the "Data Retrieval" course at CEID, University of Patras.

### First Script
---
The first script is the most simple one. After a user searches a movie title, the search engine uses the BM25 metric of Elasticsearch and returns the results in descending order.

### Second Script
---
The second script is an extension to the first one. The main difference is that for the presentation of the results it takes into account the personal ratings of the user and also the mean rating of each movies.

### Third Script
---
The third and final script focuses on filling the empty ratings of the users to further improve the search results. Specifically, we perfom a clustering on the users based on their preferences/ratings and then we fill in the empty values using the mean rating of the movies of that user's cluster. This is done using the k-means clustering.