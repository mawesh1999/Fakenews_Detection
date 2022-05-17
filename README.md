## Fake News Detection ##
Due to the boost of Internet in the last decade Online News has been a cruicial aspect of the Society
We have worked on this project as final year project of our Bachelors degree.
We have primarily Depend on the Text corpus of the Data to predict the essence of fake news 
We have Collected Data form kaggle
Cleaned Data to remove
  -Null Fields
  -Blank Spaces
  -Removing Unproductive words(the, for, in etc)
Preprocessed Data to Derive the lexeme/root of the words to remove duplicate with similar roots
Created a tfid term frequency vectorizer along with count vectorizeer to associate each word with relative Importance
Developed Various Machine Learning Models wnd tested on Test Data with satisfying Result(F1 score)
  -Decision Tree           {f1 Score- 0.90}
  -Random Forest           {f1 Score- 0.93}
  -Niave Baise             {f1 Score- 0.96}
  -Logistic Regression     {f1 Score- 0.88}
  
