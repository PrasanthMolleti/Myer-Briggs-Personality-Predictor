## [Myer-Briggs-Personality-Predictor](https://github.com/PrasanthMolleti/Myer-Briggs-Personality-Predictor)

The Myer Briggs personality test classifies a person into one of the following 16 psychological types:

![Myer Briggs personality types](https://images.saymedia-content.com/.image/c_limit%2Ccs_srgb%2Cq_auto:eco%2Cw_640/MTc0MjkzNDY3ODg1OTM4NTU2/the-history-and-significance-of-the-myers-briggs-personality-test.webp)


[The Myer Briggs Personality Predictor](https://github.com/PrasanthMolleti/Myer-Briggs-Personality-Predictor) can be used to predict a person's Myer Briggs Personality type(MBPT) using their social media posts based on the inter-connection between their psychological traits and writing style.


An [imbalanced-dataset](https://github.com/esharma3/myers-briggs-personality-prediction/blob/master/data/mbti_1.csv) which contains a users' social media posts and their respective MBPT was used. To combat this imbalance various methods like imbalance datapoint grouping, random under-sampling and Imbalance Learn library's imbalance pipeline were used.

Sentiment Analysis is performed by using the Sentiment Intensity Analyzer and its compound sentiment score on the cleaned datatset.

Parts Of Speech tagging is done using the NLTK POS tagger and their average count for each user was extracted.
The different types of POS used are : Noun, Pronoun, Adjective, Adverb, Preposition, Verb, Conjuuction, Determiner, Number, Particle and Punctuation.

Various classification supervised models used are :
- TF-IDF Logistic Regression
- Count Vectorized Logistic Regression
- TF-IDF SVC
- Count SVC
- TF-IDF Logistic Lasso Regression
- Count Logistic Lassio Regression
- TF-IDF Logistic Ridge Regression
- Count Logistic Ridge Regression
- TF-IDF Random Forest
- Count Random Forest
