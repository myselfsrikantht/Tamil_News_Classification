# Tamil_News_Classification
# INTRODUCTION
This is a Tamil News Classification ML project. I have trained the model for the classification of news into five categories: education, crime, business, technology, and sports. I collected the data by scraping information from the hindutamil.in website. Now, let's delve into this project and get started!

# DATA SCRAPING
I scraped the titles of news articles related to education, crime, business, technology, and sports, along with their respective categories, from the hindutamil.in website."

# METHODS & MODELS
**`Bag of Words`**

**`N-Grams`**

**`Tf-idf`**

**`Chi_Square Test`**

**`Logistic Regression`**

**`Decision Tree`**

**`Random Forest`**

**`Naive Bayes (Gaussian, Multinomial & Bernoulli)`**

**`SVM (Linear, RBF, poly)`**

**`Accuracy Score`**

**`K-fold Cross Validation`**

**`Some other Own Methods`**

# PROCEDURE
Step 1: Import the scraped 'Scraped_data.CSV' file.

Step 2: Check the data information, including missing values and format details.

Step 3: Identify and remove duplicate entries in the data frame.

Step 4: Check the data distribution (balanced/imbalanced) for classes in the 'Category' column.

Step 5: Remove English text from the 'Title' column of the data frame.

Step 6: Convert the Tamil text in the 'Title' column to Thanglish in the data frame.

Step 7: Remove punctuation and numbers from the 'Title' column of the data frame.

Step 8: In preprocessing, encode the categorical data in the 'Category' column using the Label Encoding method.

Step 9: Apply the Bag of Words NLP method to extract features from the 'Title' column.

Step 10: Split the data into a test set and a training set.

Step 11: Fit the following models and calculate their corresponding test and train prediction accuracy: Logistic Regression, Decision Tree, Random Forest, Naive Bayes (Gaussian, Multinomial, Bernoulli), SVM (Linear, rbf, polynomial).

Step 12: Select features using the Chi-square test.

Step 13: Fit all the models again and calculate their corresponding test and train prediction accuracy.

Step 14: Implement a method where you calculate the sum of the 1st extracted Bag of Words (BoW) variable with respect to the classes in the target variable.

Step 15: Fit all the models again and calculate their corresponding test and train prediction accuracy.

Step 16: Implement another method where you calculate the total sum of each variable in the 'zero_df' data frame and exclude features with a total less than 5.

Step 17: Fit all the models again and calculate their corresponding test and train prediction accuracy.

Step 18: Repeat the above process with the limit changed from 5 to 10.

Step 19: Fit all the models again and calculate their corresponding test and train prediction accuracy.

Step 20: Repeat the above process with the limit changed from 10 to 50.

Step 21: Fit all the models again and calculate their corresponding test and train prediction accuracy.

Step 22: Apply the N-gram NLP method to extract features from the data frame.

Step 23: Fit all the models again and calculate their corresponding test and train prediction accuracy.

Step 24: Apply the TF-IDF NLP method to extract features from the data frame.

Step 25: Fit all the models again and calculate their corresponding test and train prediction accuracy.

Step 26: Select features using the Chi-square test.

Step 27: Fit all the models again and calculate their corresponding test and train prediction accuracy.

Step 28: Implement a custom method to extract words from the 'Title' column in the 'df1' DataFrame and count unique words for each class.

Step 29: Fit all the models again and calculate their corresponding test and train prediction accuracy.

Step 30: Use K-Fold Cross-validation to assess the model performance.

# CONCLUSION
In the final analysis, I achieved a 99.18% accuracy in predicting the categories of Tamil news articles, distinguishing between education, business, sports, crime, and technology news.
