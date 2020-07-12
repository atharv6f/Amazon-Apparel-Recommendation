# Amazon Apparel Recommendation

  # Objective
   Recommending similar apparel recommendations in accordance with a product.

# Dataset
   Obtained from Amazon product advertising (API 5.0). 

# Approach

   Recommendation is done using collaborative filtering (behavior of the user). Content based recommendation is not possible as amazon does not provide user data. 

# Text Processing techniques used:
    1. Bag of words (BOW)
    2. TF-IDF
    3. Word2Vec
    4. Average Word2Vec
    5. Weighted TF-IDF

# Image based recommendation
    VGG 16 is used to convert images to vectors and recommend similiar products
    
   
