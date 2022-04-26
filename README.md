# BSAN 6080 - Google Play Store Project
![alt text](https://github.com/LMU-MSBA/bsan-6080-google-play/blob/aa19293e9a7d70c164595289b56af918484e4255/GPS_Logo.png)

# Table of Contents
* [Sprint 1: ](https://github.com/LMU-MSBA/bsan-6080-google-play#sprint-1)
* [1. Business Understanding Phase](https://github.com/LMU-MSBA/bsan-6080-google-play#business-understanding-phase)
	* [1.1 Determine Business Objective](https://github.com/LMU-MSBA/bsan-6080-google-play#11-determine-business-objective-)
	* [1.2 Assess Situation](https://github.com/LMU-MSBA/bsan-6080-google-play#12-assess-situation-)
	* [1.3 Determine Data Mining Goals](https://github.com/LMU-MSBA/bsan-6080-google-play#13-determine-data-mining-goals-)
	* [1.4 Produce Project Plan](https://github.com/LMU-MSBA/bsan-6080-google-play#14-produce-project-plan-)
* [Sprint 2: ](https://github.com/LMU-MSBA/bsan-6080-google-play#sprint-2)
* [2. Data Understanding Phase](https://github.com/LMU-MSBA/bsan-6080-google-play#data-understanding-phase)
	* [2.1 Collect Initial Data](https://github.com/LMU-MSBA/bsan-6080-google-play#21-collect-initial-data-)
	* [2.2 Describe Data](https://github.com/LMU-MSBA/bsan-6080-google-play#22-describe-data-)
	* [2.3 Explore Data](https://github.com/LMU-MSBA/bsan-6080-google-play#23-explore-data-)
	* [2.4 Verify Data Quality](https://github.com/LMU-MSBA/bsan-6080-google-play#24-verify-data-quality-)
* [Sprint 3: ](https://github.com/LMU-MSBA/bsan-6080-google-play#sprint-3)
* [3. Data Preparation Phase](https://github.com/LMU-MSBA/bsan-6080-google-play#data-preparation-phase)
	* [3.1 Select Data](https://github.com/LMU-MSBA/bsan-6080-google-play#31-select-data-)
	* [3.2 Clean Data](https://github.com/LMU-MSBA/bsan-6080-google-play#32-clean-data-)
	* [3.3 Construct Data](https://github.com/LMU-MSBA/bsan-6080-google-play#33-construct-data-)
	* [3.4 Integrate Data](https://github.com/LMU-MSBA/bsan-6080-google-play#34-integrate-data-)
	* [3.5 Format Data](https://github.com/LMU-MSBA/bsan-6080-google-play#35-format-data-)
* [4. Modeling Phase](https://github.com/LMU-MSBA/bsan-6080-google-play#modeling-phase)
	* [4.1 Selecting Modeling Techniquies](https://github.com/LMU-MSBA/bsan-6080-google-play#41-selecting-modeling-techniquies-)
	* [4.2 Generate Test Design](https://github.com/LMU-MSBA/bsan-6080-google-play#42-generate-test-design-)
	* [4.3 Build Model](https://github.com/LMU-MSBA/bsan-6080-google-play#43-build-model-)
	* [4.4 Assess Model](https://github.com/LMU-MSBA/bsan-6080-google-play#44-assess-model-)
* [5. Evaluation Phase](https://github.com/LMU-MSBA/bsan-6080-google-play#evaluation-phase)
	* [5.1 Evaluate Results](https://github.com/LMU-MSBA/bsan-6080-google-play#51-evaluate-results-)
	* [5.2 Review Process](https://github.com/LMU-MSBA/bsan-6080-google-play#52-review-process-)
	* [5.3 Determine Next Steps](https://github.com/LMU-MSBA/bsan-6080-google-play#53-determine-next-steps-)

# Sprint 1: 
# Business Understanding Phase
## 1.1 Determine Business Objective [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Background: 


### Business Objectives: 


### Business Success Criteria


## 1.2 Assess Situation [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Inventory of resources


 
### Requirements, assumptions, and constraints

 
### Comprehensibility:

 
### Risks and contingencies

 
### Terminology
 

### Costs and benefits


## 1.3 Determine Data Mining Goals [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)

### Data Mining Goals


### Data Mining Success Criteria


## 1.4 Produce Project Plan [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)

# Sprint 2: 
# Data Understanding Phase
## 2.1 Collect Initial Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)

### Initial Data Collection Report



### Initial Data Cleaning Report



## 2.2 Describe Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Data Decription Report




## 2.3 Explore Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Data Exploration Report




## 2.4 Verify Data Quality [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Data Quality Report



# Sprint 3: 
# Data Preparation Phase
## 3.1 Select Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
For all of our datasets, there were many variables that were not pertinent to our analysis. Therefore, we removed them to keep our attention on the relevant variables only. The table below indicates which variables were dropped from their respective datasets.

| Dataset | Removed Variables |
| --- | --- |
| Google Play Store Kaggle | Developer Email, Privacy Policy, Developer Website |
| Google Play Store Reviews | Review Id, Username, User Image, Review Created Version, Sort Order |
| Google Play Store Food Delivery Reviews | Review Id, Username, User Image, Review Created Version, Sort Order |

For our Google Play Store Kaggle Dataset, our inclusion criteria was based on potential to evaluate how apps on Google Play Store as a whole compare to apps in the Food Delivery Category. While we could have removed more than what we did, we wanted to make sure to keep enough features to construct meaningful comparison dashboards.

For our Google Play Store Reviews and Google Play Store Food Delivery Reviews Datasets, our inclusion criteria was based on variables that could lead to insights or impact a review being classified as “high risk.” As we were only interested in the review characteristics and the text itself, we dropped columns with user information or unrelated review information.

## 3.2 Clean Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
After selecting our data, we moved forward with the data cleaning process. Even though the main dataset we pulled from Kaggle was fairly clean, we needed to conduct some additional cleaning. First, null values needed to be addressed. Blanks and values that represented missing values were interpolated or coerced to np.nan in order to allow for calculations. Additionally, the date values needed to be updated from Unix date time into proper datetime format, as datetime format is more easily understood.

Our Google Play Store Reviews and our scraped Google Play Store Food Delivery Reviews datasets were both relatively clean as well. However, similar to the main dataset there were issues with date variables. Both the review date and reply date columns were object data types. To correct this we re-read the data using the date parser available through pandas read_csv(). At this stage we also decided to rename some of the variables into easier to understand or easier to code with names. The null values in this dataset did not concern us, as values were only missing from the reply text and reply date variables. This indicated that there was not a reply from the app owner to the reviewer, which makes sense.

As a part of data cleaning, text pre-processing was also required before modeling could take place. Text pre-processing is used to bring a standard format to the text. This standardization across a document corpus helps build meaningful features and reduce noise that can be instigated by certain text components, such as irrelevant symbols or special characters. To do this, we created a series of functions that would convert all words to lowercase, strip and remove punctuation, remove stop words, lemmatize the text, map NLTK position tags, and put the clean version of the review text into a new variable called “clean_text”. The functions we created are displayed below.

```
#convert to lowercase, strip and remove punctuations
def preprocess(text):
    text = text.lower() 
    text=text.strip()  
    text=re.compile('<.*?>').sub('', text) 
    text = re.compile('[%s]' % re.escape(string.punctuation)).sub(' ', text)  
    text = re.sub('\s+', ' ', text)  
    text = re.sub(r'\[[0-9]*\]',' ',text) 
    text=re.sub(r'[^\w\s]', '', str(text).lower().strip())
    text = re.sub(r'\d',' ',text) 
    text = re.sub(r'\s+',' ',text) 
    return text

# stopword removal
def stopword(string):
    a= [i for i in string.split() if i not in stopwords.words('english')]
    return ' '.join(a)
# lemmatization
# initialize the lemmatizer
wl = WordNetLemmatizer()
 
# this is a helper function to map NTLK position tags
def get_wordnet_pos(tag):
    if tag.startswith('J'):
        return wordnet.ADJ
    elif tag.startswith('V'):
        return wordnet.VERB
    elif tag.startswith('N'):
        return wordnet.NOUN
    elif tag.startswith('R'):
        return wordnet.ADV
    else:
        return wordnet.NOUN
# tokenize the sentence
def lemmatizer(string):
    word_pos_tags = nltk.pos_tag(word_tokenize(string)) # Get position tags
    a=[wl.lemmatize(tag[0], get_wordnet_pos(tag[1])) for idx, tag in enumerate(word_pos_tags)] # Map the position tag and lemmatize the word/token
    return " ".join(a)

```
```
def finalpreprocess(string):
    return lemmatizer(stopword(preprocess(string)))
df['clean_text'] = df['review_text'].apply(lambda x: finalpreprocess(x))
df.head(2)
```

## 3.3 Construct Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
In our main Google Play Store dataset, minimum installs and maximum install values were provided in the data, but to get an approximate and more specific install number we created a new value to interpolate the values and create an estimated installs field that we can use in our analysis. Originally, we tried creating an estimated value by taking min+max / 2, but after further consideration we determined interpolating the values would be a more accurate and appropriate way to represent estimates.

For our Google Play Store Reviews and Google Play Store Food Delivery Reviews datasets, in order to conduct our analysis, we needed to create criteria on which we would base whether a review was “high risk” or not. We determined that a “high risk” review would have a low rating (a rating of 1 or 2), a polarity less than 0, and a subjectivity score greater than 0.5. A negative polarity indicates negative review sentiment. Higher subjectivity means that the text contains personal opinion rather than factual information. We created a binary variable called “high_risk_review,” where if the review met all of the criteria it would display a 1, else a 0. We felt this variable would give us a good representation of high risk reviews. We also felt it was very tailorable to fit the needs of an app owner, perhaps they want to be more or less strict on what they consider to be a “high risk” review.

After creating the “high_risk_review” variable, we then checked the balance of the variable as it would be used as our label column in our analysis. We discovered it was very unbalanced. To correct this we used undersampling. After mitigating the skewness, we were now ready to start modeling.

## 3.4 Integrate Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
Main tables in the database are:
* applications
* food_delivery_reviews
* App_reviews

## 3.5 Format Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
AWS RDS database connection details: aws_rds_db.txt file in Github 

Exploratory SQL using AWS Postgres Database:
```
-- Explore tables
SELECT *
FROM applications
;

SELECT *
FROM app_reviews
;

SELECT *
FROM food_delivery_reviews
;


-- Demonstrate JOINS 

-- JOIN applications with food_delivery_reviews (using doordash as an example)
SELECT *
FROM applications a 
LEFT JOIN food_delivery_reviews f
	ON a.app_id = f.app_id
WHERE a.app_id = 'com.dd.doordash'
;

-- JOIN applications with app_reviews (using com.anydo as an example)
SELECT *
FROM applications a 
LEFT JOIN app_reviews r 
	ON a.app_id = r.app_id
WHERE a.app_id = 'com.anydo'
;
```

# Modeling Phase
## 4.1 Selecting Modeling Techniquies [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
For model selection, our goal was to find the best model for predicting “high risk” reviews based on the review text alone. As our goal was to find the most effective model for building a sentiment monitoring system, we tested across as many machine learning and deep learning classifier models as we could. For our machine learning models, we included Logistic Regression, Support Vector, Decision Tree, Random Forest, and Multinomial Naive Bayes classifiers. For all the machine learning classifier models, we ran for both count vectorizer and TF-IDF vectorizer. For our deep learning models, we included BERT, Glove, Word2Vec, and FastText.

## 4.2 Generate Test Design [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
To measure the success of supervised models, we will assess model performance using accuracy, precision, recall, F1 score, and AUC as our performance metrics. The main metric we will use to determine the success of our model is AUC. AUC values between 0.9-1 we will consider excellent, AUC values between 0.8-0.9 we will consider good, AUC values between 0.7-0.8 we will consider fair, AUC values between 0.6-0.7 are poor, and any AUC values below 0.6 we will consider failed. Ideally, we would like to see a model performing in the range of 0.8-1 for all metrics. However, to conclude that the overall model is successful we would also like to see scores in the range of 0.7 to 1 in all the other metric categories.

## 4.3 Build Model [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
As we were testing many different models in our analysis, we tried our best to streamline testing by creating functions that would run and compare the models for us. While they took some time to build, it saved us time in the long run to build, run, and compare the models separately.

For our machine learning models, we created a function that would accept X, y, and a type of vectorizer, run a series of predefined classifier models, calculate metric scores, compare the scores in a table, and indicate in the table which model had the best score for each metric. We ran our machine learning models which included Logistic Regression, Support Vector, Decision Tree, Random Forest, and Multinomial Naive Bayes classifiers. For all the machine learning classifier models, we ran for both count vectorizer and TF-IDF vectorizer.
 
```
def models_evaluation(X, y, vect):

    # splitting the data
    X_train, X_test, y_train, y_test = train_test_split(X, y, random_state=1)

    # create document-term matrices using the vectorizer
    X_train_dtm = vect.fit_transform(X_train)
    X_test_dtm = vect.transform(X_test)

    # perform each machine learning classifier
    # use selected model to predict the high or low star rating
    log_model.fit(X_train_dtm, y_train)
    log = y_pred_class = log_model.predict(X_test_dtm)

    svc_model.fit(X_train_dtm, y_train)
    svc = y_pred_class = svc_model.predict(X_test_dtm)

    dtr_model.fit(X_train_dtm, y_train)
    dtr = y_pred_class = dtr_model.predict(X_test_dtm)

    rfc_model.fit(X_train_dtm, y_train)
    rfc = y_pred_class = rfc_model.predict(X_test_dtm)

    mnb_model.fit(X_train_dtm, y_train)
    mnb = y_pred_class = mnb_model.predict(X_test_dtm)

    # create a data frame with the models perfoamnce metrics scores
    models_scores_table = pd.DataFrame({'Logistic Regression':[accuracy_score(y_test,log).mean(),
                                                               precision_score(y_test,log).mean(),
                                                               recall_score(y_test,log).mean(),
                                                               f1_score(y_test,log).mean(),
                                                               roc_auc_score(y_test,log).mean()],
                                       
                                      'Support Vector Classifier':[accuracy_score(y_test,svc).mean(),
                                                                   precision_score(y_test,svc).mean(),
                                                                   recall_score(y_test,svc).mean(),
                                                                   f1_score(y_test,svc).mean(),
                                                                   roc_auc_score(y_test,svc).mean()],
                                       
                                      'Decision Tree':[accuracy_score(y_test,dtr).mean(),
                                                       precision_score(y_test,dtr).mean(),
                                                       recall_score(y_test,dtr).mean(),
                                                       f1_score(y_test,dtr).mean(),
                                                       roc_auc_score(y_test,dtr).mean()],
                                       
                                      'Random Forest':[accuracy_score(y_test,rfc).mean(),
                                                       precision_score(y_test,rfc).mean(),
                                                       recall_score(y_test,rfc).mean(),
                                                       f1_score(y_test,rfc).mean(),
                                                       roc_auc_score(y_test,rfc).mean()],
                                       
                                      'Multinomial Naive Bayes':[accuracy_score(y_test,mnb).mean(),
                                                              precision_score(y_test,mnb).mean(),
                                                              recall_score(y_test,mnb).mean(),
                                                              f1_score(y_test,mnb).mean(),
                                                              roc_auc_score(y_test,mnb).mean()]},
                                      
                                      index=['Accuracy', 'Precision', 'Recall', 'F1 Score', 'AUC'])
    
    # add 'Best Score' column
    models_scores_table['Best Score'] = models_scores_table.idxmax(axis=1)
    
    # return models performance metrics scores data frame
    return(models_scores_table)
```

For our deep learning models, we included BERT, Glove, Word2Vec, and FastText. Similar to our machine learning models we created a function that would accept three models, calculate metric scores, and create a score comparison table indicating which model performed the best along each metric. We ran the BERT model separately, as it was a different process than the other models. However, we then created another comparison table to compare BERT along with the other models all together.

```
def models_evaluation(model_1, model_2, model_3):

    #MODEL_1
    # transform text into vectors
    vectors_1 = model_1.transform(review_text)

    # split data into training and test portions
    X_train_1, X_test_1, y_train_1, y_test_1 = train_test_split(vectors_1, high_low)

    # train machine learning model
    clf = MLPClassifier()
    clf_1 = clf.fit(X_train_1, y_train_1)

    # output machine learning model performance
    predictions_1 = clf_1.predict(X_test_1)

    #MODEL_2
    # transform text into vectors
    vectors_2 = model_2.transform(review_text)

    # split data into training and test portions
    X_train_2, X_test_2, y_train_2, y_test_2 = train_test_split(vectors_2, high_low)

    # train machine learning model
    clf = MLPClassifier()
    clf_2 = clf.fit(X_train_2, y_train_2)

    # output machine learning model performance
    predictions_2 = clf_2.predict(X_test_2)

    #MODEL_3
    # transform text into vectors
    vectors_3 = model_3.transform(review_text)

    # split data into training and test portions
    X_train_3, X_test_3, y_train_3, y_test_3 = train_test_split(vectors_3, high_low)

    # train machine learning model
    clf = MLPClassifier()
    clf_3 = clf.fit(X_train_3, y_train_3)

    # Output machine learning model performance
    predictions_3 = clf_3.predict(X_test_3)

    # create a data frame with the models perfoamnce metrics scores
    models_scores_table = pd.DataFrame({'glove':[accuracy_score(y_test_1,predictions_1).mean(),
                                                precision_score(y_test_1,predictions_1).mean(),
                                                recall_score(y_test_1,predictions_1).mean(),
                                                f1_score(y_test_1,predictions_1).mean(),
                                                roc_auc_score(y_test_1,predictions_1).mean()],
                                       
                                        'word2vec':[accuracy_score(y_test_2,predictions_2).mean(),
                                                precision_score(y_test_2,predictions_2).mean(),
                                                recall_score(y_test_2,predictions_2).mean(),
                                                f1_score(y_test_2,predictions_2).mean(),
                                                roc_auc_score(y_test_2,predictions_2).mean()],
                                       
                                        'fasttext':[accuracy_score(y_test_3,predictions_3).mean(),
                                                precision_score(y_test_3,predictions_3).mean(),
                                                recall_score(y_test_3,predictions_3).mean(),
                                                f1_score(y_test_3,predictions_3).mean(),
                                                roc_auc_score(y_test_3,predictions_3).mean()]},
                                      
                                        index=['Accuracy', 'Precision', 'Recall', 'F1 Score', 'AUC'])
    
    # add 'Best Score' column
    models_scores_table['Best Score'] = models_scores_table.idxmax(axis=1)
    
    # return models performance metrics scores data frame
    return(models_scores_table)
```

Through the use of these functions, were successfully able to run and compare 9 models in order to find a well performing one to create a sentiment monitoring system.

## 4.4 Assess Model [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
To assess model performance, we used accuracy, precision, recall, F1 score, and AUC as our performance metrics. The main metric we will use to determine the success of our model is AUC. AUC values between 0.9-1 we will consider excellent, AUC values between 0.8-0.9 we will consider good, AUC values between 0.7-0.8 we will consider fair, AUC values between 0.6-0.7 are poor, and any AUC values below 0.6 we will consider failed. Ideally, we would like to see a model performing in the range of 0.8-1 for all metrics.

# Evaluation Phase
## 5.1 Evaluate Results [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)

Google Play Store Reviews - ML Results

w/ CV
| Metric | Logistic Regression | Support Vector Classifier | Decision Tree | Random Forest | Multinomial Naive Bayes | Best Score |
| --- | --- | --- | --- | --- | --- | --- |
|Accuracy	|0.848580	|0.858044	|0.832808	|0.842271	|0.823344	|Support Vector Classifier|
|Precision	|0.853333	|0.856209	|0.858156	|0.893939	|0.781609	|Random Forest|
|Recall		|0.831169	|0.850649	|0.785714	|0.766234	|0.883117	|Multinomial Naive Bayes|
|F1 Score	|0.842105	|0.853420	|0.820339	|0.825175	|0.829268	|Support Vector Classifier|
|AUC		|0.848100	|0.857840	|0.831507	|0.840172	|0.824994	|Support Vector Classifier|

w/ TFIDF
| Metric | Logistic Regression | Support Vector Classifier | Decision Tree | Random Forest | Multinomial Naive Bayes | Best Score |
| --- | --- | --- | --- | --- | --- | --- |
|Accuracy	|0.813880	|0.845426	|0.801262	|0.810726	|0.820189	|Support Vector Classifier|
|Precision	|0.814570	|0.830189	|0.809524	|0.856061	|0.783626	|Random Forest|
|Recall		|0.798701	|0.857143	|0.772727	|0.733766	|0.870130	|Multinomial Naive Bayes|
|F1 Score	|0.806557	|0.843450	|0.790698	|0.790210	|0.824615	|Support Vector Classifier|
|AUC		|0.813461	|0.845749	|0.800474	|0.808601	|0.821568	|Support Vector Classifier|

The above tables show the performance of each machine learning model when utilizing either Countvectorizer or TF-IDF vectorizer in predicting “high risk” reviews. For each field, the highest accuracy, precision, recall, F1-score, and AUC metrics are indicated by the “Best Score” column. The highest-performing model for each field fell mostly between the range of 0.7 to 9.0, reflecting relatively accurate classification. For the Google Play Store Reviews dataset, the Support Vector Classifier, with count vectorizer, was the best model for predicting “high risk” reviews with an AUC of 0.858 and all other scores falling around 0.85.

Google Play Store Reviews - DL Results
| Metric | BERT	| glove	| word2vec | fasttext | Best Score |
| --- | --- | --- | --- | --- | --- |
|Accuracy	|0.955932	|0.831978	|0.845528	|0.867209	|BERT|
|Precision	|0.959184	|0.781250	|0.677778	|0.721519	|BERT|
|Recall		|0.952703	|0.510204	|0.685393	|0.678571	|BERT|
|F1 Score	|0.955932	|0.617284	|0.681564	|0.699387	|BERT|
|AUC		|0.955943	|0.729272	|0.790911	|0.800689	|BERT|

The table above shows the performance of each deep learning model for predicting “high risk” reviews. The highest-performing model for each field fell mostly between the range of 0.7 to 9.0, reflecting relatively accurate classification. For the Google Play Store Reviews dataset, BERT was by far the best model for predicting “high risk” reviews with an AUC of 0.956 and all other scores falling around 0.95.

Food Delivery Reviews Dataset - ML Results

w/ CV
| Metric | Logistic Regression | Support Vector Classifier | Decision Tree | Random Forest | Multinomial Naive Bayes | Best Score |
| --- | --- | --- | --- | --- | --- | --- |
|Accuracy	|0.848580	|0.858044	|0.839117	|0.845426	|0.823344	|Support Vector Classifier|
|Precision	|0.853333	|0.856209	|0.860140	|0.888889	|0.781609	|Random Forest|
|Recall		|0.831169	|0.850649	|0.798701	|0.779221	|0.883117	|Multinomial Naive Bayes|
|F1 Score	|0.842105	|0.853420	|0.828283	|0.830450	|0.829268	|Support Vector Classifier|
|AUC		|0.848100	|0.857840	|0.838001	|0.843598	|0.824994	|Support Vector Classifier|

w/ TFIDF
| Metric | Logistic Regression | Support Vector Classifier | Decision Tree | Random Forest | Multinomial Naive Bayes | Best Score |
| --- | --- | --- | --- | --- | --- | --- |
|Accuracy	|0.813880	|0.845426	|0.807571	|0.794953	|0.820189	|Support Vector Classifier|
|Precision	|0.814570	|0.830189	|0.800000	|0.829630	|0.783626	|Support Vector Classifier|
|Recall		|0.798701	|0.857143	|0.805195	|0.727273	|0.870130	|Multinomial Naive Bayes|
|F1 Score	|0.806557	|0.843450	|0.802589	|0.775087	|0.824615	|Support Vector Classifier|
|AUC		|0.813461	|0.845749	|0.807505	|0.793084	|0.821568	|Support Vector Classifier|

Running the same models on the Food Delivery Reviews dataset garnered very similar results. The highest-performing model for each field fell mostly between the range of 0.7 to 9.0, reflecting relatively accurate classification. The Support Vector Classifier, with count vectorizer, was again the best model for predicting “high risk” reviews with an AUC of 0.858 and all other scores falling around 0.85. 

Food Delivery Reviews Dataset - DL Results
| Metric | BERT	| glove	| word2vec | fasttext | Best Score |
| --- | --- | --- | --- | --- | --- |
|Accuracy	|0.955932	|0.831978	|0.875339	|0.829268	|BERT|
|Precision	|0.959184	|0.818182	|0.784946	|0.696203	|BERT|
|Recall		|0.952703	|0.463918	|0.737374	|0.585106	|BERT|
|F1 Score	|0.955932	|0.592105	|0.760417	|0.635838	|BERT|
|AUC		|0.955943	|0.713576	|0.831650	|0.748917	|BERT|

The table above shows the performance of each deep learning model for predicting “high risk” reviews in the Food Delivery Reviews dataset. Similar to the Google Play Store Reviews dataset, the highest-performing model for each field fell mostly between the range of 0.7 to 9.0, reflecting relatively accurate classification. BERT again was by far the best model for predicting “high risk” reviews with an AUC of 0.956 and all other scores falling around 0.95.

In conclusion, we were able to find a model that performed extremely well for both datasets, with scores all above .95. This reflects our ability to classify “high risk” reviews accurately.

## 5.2 Review Process [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
We were able to create a machine learning model that predicts whether or not a review is considered “high-risk” and therefore needs to be responded to. This will allow for valuable insights to be generated for an app developer and allow that developer to address potential risks to ratings and app perception in a timely manner. 

Coupled with our predictive model, we will also showcase descriptive analytics displayed in operational and analytical dashboards that will likewise showcase valuable insights to the app developer. All of this will promote the business and role of a Business Analyst for Play Partnerships at Google.

## 5.3 Determine Next Steps [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
