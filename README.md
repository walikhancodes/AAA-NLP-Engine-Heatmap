# NLP-Topic-Modeling

ConsumerAffairs_LDA.ipynb - Python script performing NLP (Natural Language Processing) for the purpose of topic modeling. This model peforms topic modeling on the 
customer reviews from the American Automobile Association (AAA) website https://www.consumeraffairs.com/automotive/aaa.html

wkMapTest.ipynb - Python script mapping the results from 'ConsumerAffairs_LDA.ipynb' in a geospatial heatmap using choropleth map from plotly. The script uses a geoJSON 
file containing the shapes for every US city. Attached below is a screenshot of how the map looks. 

STEP 1: Scrapped reviews from consumer affairs website relating to AAA (https://www.consumeraffairs.com/automotive/aaa.html) using the Beautiful Soup library in Python. Then using this scrapped data extracted the relevant parts from html doc of every review and compiled each review onto a single dataset including both the review, rating, and city which the reivew is coming from.

STEP 2; As part of the data pre processing, first we removed all stop-words from the reviews, then converted all words of same base but different part of speech into one base form (lemmatization).

STEP 3: Perform NLP 

![image](https://user-images.githubusercontent.com/76940552/189978322-b6e23c2b-d702-447e-b74b-ea026f5ffcf3.png)

![image](https://user-images.githubusercontent.com/76940552/189978952-49579232-5fdd-43ba-a801-535bf863d1e4.png)

![image](https://user-images.githubusercontent.com/76940552/189980024-7b4f15ef-3a35-4749-821d-176002467f2a.png)

 




