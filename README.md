# Introduction

Recommending movies to users based on their on interest or similar movies similar to one particular movie. Here we attempt to solve this problem based on some famous approaches used in this area,User-Based Collaborative Filtering which uses and takes into account the users’ preferences and already watched movies in order to recommend similar movies.  Also Item-Based Collaborative Filtering, this approach takes the movies’ ratings and recommends the most similar moviesto it based on the features we have like the rating maybe the popularity.
<br><br>Later we explore some purposed ideas of our own to strengthen the recommendations and letting the user have more  control  over  the  recommendations  filter  by  genres  and  movie  language,  we  achieve  this  kind  of  conditional recommendation by weighting some features in the latent feature vector before constructing the correlation matrix.

## Requirements
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required packages with the latest updates.

- pandas <br/>
- numpy <br/>
- imblearn <br/>
- matplotlib <br/>
- seaborn <br/>
- plotly <br/>
- tqdm <br/>
- mlxtend <br/>
- sklearn <br/>
- yellowbrick <br/>
- xgboost <br/>
- wordcloud <br/>
- nltk <br/>
- gensim <br/>
- pyLDAvis <br/>
- surprise <br/>

## Usage
Better to run it on colab or if you intend to run it locally make sure you have sufficient amount of RAM as it needs alot of resources to process the text data, also running it with GPU will be much better and faster, however running it on CPU will be just fine.

## Dataset
The dataset is obtained from kaggle https://www.kaggle.com/rounakbanik/the-movies-dataset, it has 270,000 user ratings and 45,000 movies that we used to train our models and output the final recommendations to the use.


## Sections
1. Importing required libraries
2. Data preprocessing
3. Data visualization
4. Feature Engineering (Bow, TF-IDF)
5. Classification
6. Clustering
7. Item-based collaborative filtering
8. User-basd collaborative filtering
9. PKI (Prior Knowledge Input)
10. Conditional generation based on genre

# Results and expected output
![recommender](https://user-images.githubusercontent.com/25733573/145745755-7bcf5103-9133-4018-b6cd-36156c75bfcb.jpg)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
