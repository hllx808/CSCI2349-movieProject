# Information:

## Group 8
- We analyzed a variety of movie summaries to see what words appear most frequently and whether or not we can establish any patterns.

## How to use...
- The raw_data directory contains the raw data which is the csv for the Kaggle dataset that contains movie plots for ~35,000 movies
- The src directory contains 3 separate files:
- data.ipynb | extracts the Kaggle datasets and filters it so that we focus on only 10 genres and <= 250 movies per genre. Contains other information such as type:token ratios, number of tokens, genres, etc. 
- bigrams-collocations.ipynb | uses the function from data.ipynb to get new dataset. Generates bigrams and collocations for 10 different genres.
- unigrams-wordclouds.ipynb | uses the function from data.ipynb to get new dataset. Generates visualizations for wordclouds, unigrams, word embeddings, and contains data about number of genres and other metadata.
- allGenres.txt is a .txt of all the genres from the raw dataset.
- extensiveStopList.txt is a list of external stopwords used for removing some extra common words when generating visualizations.
- 1) Clone repository 
  ```js
  git clone https://github.com/hllx808/CSCI2349-movieProject.git
   ```
- 2) Cd into src directory
  ```js
  Run data.ipynb to just get the modified dataset
   ```
  ```js
  Run bigrams-collocations.ipynb to get bigrams/collocations
   ```
  ```js
  Run unigrams-wordclouds.ipynb to get wordclouds, unigrams, word embeddings, and other metadata
   ```

  
## Kaggle Dataset Info:
- csv contents: Release Year | Title | Origin/Ethnicity | Director | Cast | Genre | Wiki Page | Plot
- [Kaggle Link](https://www.kaggle.com/datasets/jrobischon/wikipedia-movie-plots)

## Sources
- [Google News Model](https://github.com/eyaler/word2vec-slim/)
- [Sebleier NLTK extended stoplist](https://gist.github.com/sebleier/554280)

