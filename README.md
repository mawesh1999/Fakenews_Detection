## Fake News Detection ##
Due to the boost of the Internet in the last decade Online News has been a crucial aspect of the Society
We have worked on this project as a final year project of our Bachelor's degree.
We have primarily Depend on the Text corpus of the Data to predict the essence of fake news 
We have Collected Data form Kaggle
Cleaned Data to remove
  -Null Fields
  -Blank Spaces
  -Removing Unproductive words(the, for, in etc)
Preprocessed Data to Derive the lexeme/root of the words to remove duplicates with similar roots
Created a tfid term frequency vectorizer along with a count vectorizer to associate each word with relative Importance
Developed Various Machine Learning Models and tested on Test Data with satisfying Results (F1 score)
  -Decision Tree           {f1 Score- 0.90}
  -Random Forest           {f1 Score- 0.93}
  -Niave Baise             {f1 Score- 0.96}
  -Logistic Regression     {f1 Score- 0.88}
  
