# # Recipe Diet Classification from Ingredients
# 
# this project goal is to classify diets based on the recipe ingredients.
# 
# the following steps are made to solve this problem
# * 1- loading the dataset from a json file DietDS.json
# * 2- clean dataset ingredient colmn using regex by removing 
#         - punctuation, digits, stop words, brand names
# * 3- encoding the feature column using TfidfVectorizer( which Convert a collection of raw documents to a matrix of TF-IDF features).
# * 4- Split the data to (X-TFIDF Matrix, Y-Label value of Diet into training and test data(70:30).
# * 5- preform Knn machine learning algorithm to get an accurecy 


