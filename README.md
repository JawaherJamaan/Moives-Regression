# TMDB Moives Project Proposal 

This repository to meet requirements for data science bootcamp with SADIA.


# Do the highest profit films depend on the genres of film and cast?

 Film production is such a big industry that has the attention of just about anyone who can see them.
 Major studios and indie filmmakers alike spend much of their days looking for new sources of revenue 
 this study help filmmakers decide whether or not the cast and genre of the movie affect the revenue.

## Dataset
We have data set **tmdb-moives** that represents movies information based on TMDB rating with 10,000 records
and 21 features. I use this data set for extract useful information to production companies.
This dataset can be found at [Kaggle](https://www.kaggle.com/tmdb/tmdb-movie-metadata).


This dataset contains Moives for the follwing genres:

- Action 
- Animation 
- Comedy 
- Crime 
- Drama 
- Experimental 
- Fantasy 
- Historical 
- Horror 
- Romance 
- Science Fiction 
- Thriller 
- Western 
- Other Genres

The dataset is available as the ```.csv``` file. a sample of data is shown in the following table:
<table width="100%">
 <tr>
  <th>id</th><th>imdb_id</th><th>popularity</th><th>budget</th><th>revenue</th><th>original_title</th><th>cast</th><th>homepage</th><th>director</th><th>tagline</th><th>keywords</th><th>overview</th><th>runtime</th><th>genres</th><th>production_companies</th><th>release_date</th><th>vote_count</th><th>vote_average</th><th>release_year</th><th>budget_adj</th><th>revenue_adj</th>
 </tr>
 <tr>
  <th>135397</th><th>tt0369610</th><th>32.985763</th><th>150000000</th><th>1513528810</th><th>Jurassic World</th><th>Chris Pratt|Bryce Dallas Howard|Irrfan Khan|Vi...</th><th>http://www.jurassicworld.com/</th><th>Colin Trevorrow</th><th>The park is open.</th><th>monster|dna|tyrannosaurus rex|velociraptor|island</th><th>Twenty-two years after the events of Jurassic ...</th><th>124</th><th>Action|Adventure|Science Fiction|Thriller</th><th>Universal Studios|Amblin Entertainment|Legenda...</th><th>6/9/15</th><th>5562</th><th>6.5</th><th>2015</th><th>1.379999e+08</th><th>1.392446e+09</th>
 </tr>
</table>


The most important features for this study :<br>
**genres**, which contained the type of moives <br>
**cast**, which included the tweet date <br>
**user_location** are used to identify <br>
The Regression Analysis is the process of predicting a Label based on the features at hand
so, here we use regression to know relationship between revenue and other features like cast and genres.


## Tools
I uesd Jupyter notebook to write codes and import libraries to achieve the goal of this dataset, such as:<br>
```numby, matplotlib, pandas``` for EDA the data and train a model.<br>
and for regression use  ```pickle``` will be used to analyzes the relationship between two or more features
it is type of supervised learning to train the model. 

## **TO DO**: 
- I will do wrangling data and exploratory data analysis before used the model.  
- **NOTE:** 
