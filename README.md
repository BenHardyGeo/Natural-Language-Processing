# Natural-Language-Processing
This notebook applies natural language processing (NLP) to 14640 tweets about six airline companies. It’s a sentiment analysis, classifying tweets as positive, negative or neutral.

This notebook was prepared for the nineth project of the Post Graduate Program in Artificial Intelligence and Machine Learning: Business Applications from the McCombs School of Business at The University of Texas. Data was provided in a .csv file.

The notebook starts with loading the data and a short QC of the data. This is followed by an exploratory data analysis.

The text is then processed for machine learning: html tag removal, , remove urls, expand contractions, Tokenization, removing numbers, removing special characters and punctuations, removal of stopwords, conversion to lowercase, Lemmatization.

The text is then vectorized using two techniques: CountVectorizer and TF-IDF (Term Frequency – Inverse Document Frequency) both are techniques that essentially convert words into numbers so that we can input them into machine learning algorithms.

The problem is then a supervised learning classification problem we have the input variables (the matrix of vectorized words) and the target variable (the labels). In this case the project called for using a random forest classifier. I followed an example tuning method which tunes only the number of estimators. I then use my preferred method: RandomSearchCV and received slightly better results.

While this project was done as part of a school project. I believe it indicates the quality of work that I’m capable of in real-world applications. I was the top student in my cohort with a final course weighted average of 99.39%. 
