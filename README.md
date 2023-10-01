# Collaborative-Recommendation-Based-Books-recommender-system
# Step 1. 
## Download book data
* Go to https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/books
* Download book data from https://drive.google.com/uc?id=1LXpK1UfqtP89H1tYy0pBGHjYk8IhigUK

## Download interaction data
* Go to https://sites.google.com/eng.ucsd.edu/ucsdbookgraph/shelves
* Download https://drive.google.com/open?id=1zmylV7XW2dfQVCLeg1LbllfQtHD2KUon
* Download https://drive.google.com/uc?id=1CHTAaNwyzvbi1TR08MJrJ03BxA266Yxr

## Extract data

# Step 2.
## Explaining the code files
### 1. Search.ipynb
* Built a search engine that could be used to efficiently search a book through the catalog.
* In order to increase reduce search time, all titles are converted to lowercase, punctuations such as '-' are removed. Also only those books are selected which has been rated more than 15 times.
* We read the 'goodreads_books.json.gz' file which contains all the books. Further we extract these columns out of json file, Book_id, title, ratings, url(goodreads link), url_image.
*   
