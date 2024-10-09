# Book_Recommendation_Project

This project consists of two key notebooks that work together to provide a Book Search functionality and a Book Recommendation System.

## Book Search Notebook:

* Implements a search function allowing users to find books based on title.
* Uses data preprocessing to clean and prepare the dataset for search queries.
* Displays relevant book search results efficiently.

## Book Recommendation Notebook:

* Builds a recommendation system by identifying users with mutual book likings and suggesting other books that these users have rated highly.
* Suggests the top 10 books for users based on their interactions and general popularity trends.
  
## Project Structure:
1. book_search.ipynb: Contains the code to search for books from a dataset.
2. book_recommendation.ipynb: Builds a recommendation engine that suggests books to users.

## Dataset:
* goodreads_books.json.gz: A compressed JSON file containing detailed information about books in the Goodreads corpus.
* book_id_map.csv: Maps the book_id from the Goodreads books file to the csv_id used in the 'goodreads_interactions' file.
* goodreads_interactions.csv: Contains data on user ratings for various books.

