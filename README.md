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
| Google Play Store Kaggle | Developer Email, Privacy Policy, and Developer Website |
| Google Play Store Reviews | Username, User Image, Review Created Version, and Sort Order |
| Google Play Store Food Reviews | Review Id, Username, User Image, Review Created Version, and Sort Order |

For our Google Play Store Kaggle Dataset, our inclusion criteria was based on potential to evaluate how apps on Google Play Store as a whole compare to apps in the Food Delivery Category. While we could have removed more than what we did, we wanted to make sure to keep enough features to construct meaningful comparison dashboards.

For our Google Play Store Reviews Dataset and our Google Play Store Food Reviews Dataset, our inclusion criteria was based on variables that could lead to insights or impact the review being “high risk.” As we were only interested in the review characteristics and the text itself, we dropped columns with user information or unrelated review information.

## 3.2 Clean Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
Even though the main dataset we pulled from Kaggle was fairly clean, we needed to conduct some additional cleaning. First, null values needed to be accounted for. Blanks and values that represented missing values were interpolated or coerced to np.nan in order to allow for calculations. Additionally, the date values needed to be updated into proper datetime format from Unix date time, as datetime format is more easily understood.

Our Google Play Store Reviews dataset and our scraped Google Play Store Food Delivery Reviews dataset were also both relatively clean. However, similar to the Kaggle dataset there were issues with the date variables. Both the review date and reply date columns were an object data type. To correct this we re-read the data and used the date parser available through pandas read_csv(). As a part of data cleaning, text pre-processing was also required before feature engineering and modeling could  take place. Text pre-processing is used to bring a standard format to the text. This standardization across a document corpus helps build meaningful features and reduce noise that can be instigated by certain text components, such as irrelevant symbols or special characters. To do this we created a series of functions that would convert all words to lowercase, strip and remove punctuation, remove stop words, lemmatize the text, map NLTK position tags, and put the clean version of the review text into a new variable called “clean_text.”

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
Google Play Store Kaggle Dataset:
Minimum installs and maximum install values were provided in the data, but to get an approximate and more specific installs number we created a new value to interpolate the values and create an estimated installs field that we can use in our analysis. Originally we tried creating an estimated value by taking min+max / 2, but after further consideration we determined interpolating the values would be a more accurate and appropriate way to represent estimates.

Google Play Store Reviews Dataset & Google Play Store Food Delivery Reviews:
In order to conduct our analysis. We needed to create criteria on which we would base whether a review was “high risk.” Ultimately, we determined that a “high risk” review would have a low rating, a polarity less than 0, and a subjectivity score greater than 0.5. A negative polarity indicates negative review sentiment. Higher subjectivity means that the text contains personal opinion rather than factual information. We created a binary variable called “high_risk_review,” where if the review met all of the criteria it would display a 1, else a 0.

After creating the “high_risk_review” variable, we then checked the balance of the variable as that would be used as our label column in our analysis. We discovered it was very unbalanced and used undersampling to correct it. After mitigating the skewness, we were not ready to start modeling.


## 3.4 Integrate Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)



## 3.5 Format Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)



# Modeling Phase
## 4.1 Selecting Modeling Techniquies [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
For model selection, our goal was to find the best model for predicting high risk reviews based on text alone. Keeping our end goal in mind of finding the most effective model for building a sentiment monitoring system. In order to do this, we tested across many machine learning and deep learning classifier models. For our machine learning models, we included Logistic Regression, Support Vector, Decision Tree, Random Forest, and Multinomial Naive Bayes classifiers. For all the machine learning classifier models, we ran for both count vectorizer and TF-IDF vectorizer. For our deep learning models, we included BERT, Glove, Word2Vec, and FastText.

## 4.2 Generate Test Design [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)


## 4.3 Build Model [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
As we were testing many different models in our analysis, we tried our best to streamline testing by creating functions that would run and compare the models for us. For our machine learning models, we created a function that would accept X, y, and a type of vectorizer, run a series of predefined classifier models, calculate metric scores, compare the scores in a table, and indicate in the table which model had the best score for each metric. The function used and an example of a resulting table is shown below.

## 4.4 Assess Model [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
To assess model performance, we used accuracy, precision, recall, F1 score, and AUC as our performance metrics. The main metric we will use to determine the success of our model is AUC. AUC values between 0.9-1 we will consider excellent, AUC values between 0.8-0.9 we will consider good, AUC values between 0.7-0.8 we will consider fair, AUC values between 0.6-0.7 are poor, and any AUC values below 0.6 we will consider failed. Ideally, we would like to see a model performing in the range of 0.8-1 for all metrics.

# Evaluation Phase
## 5.1 Evaluate Results [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)


## 5.2 Review Process [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)


## 5.3 Determine Next Steps [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
