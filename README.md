## Recipe Diet Classification from Ingredients

 this project goal is to classify diets based on the recipe ingredients.
 
 the following steps are made to solve this problem
 -  loading the dataset from a json file DietDS.json
 -  clean dataset ingredient colmn using regex by removing 
         - punctuation, digits, stop words, brand names
 - encoding the feature column using TfidfVectorizer( which Convert a collection of raw documents to a matrix of TF-IDF features).
 - Split the data to (X-TFIDF Matrix, Y-Label value of Diet into training and test data(70:30).
 - Preform Knn machine learning algorithm to get an accurecy 

