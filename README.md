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
* [6. Deployment Phase](https://github.com/LMU-MSBA/bsan-6080-google-play#deployment-phase)
	* [6.1 Plan Deployment](https://github.com/LMU-MSBA/bsan-6080-google-play/blob/main/README.md#61-plan-deployment-)
	* [6.2 Plan Monitoring & Maintenance](https://github.com/LMU-MSBA/bsan-6080-google-play#62-plan-monitoring--maintenance-)
	* [6.3 Product Final Report](https://github.com/LMU-MSBA/bsan-6080-google-play/blob/main/README.md#63-product-final-report-)
	* [6.4 Review Project](https://github.com/LMU-MSBA/bsan-6080-google-play#64-review-project-)

# Sprint 1: 
# Business Understanding Phase
## 1.1 Determine Business Objective [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Background: 
Our mission is connecting the right third-party app and game developers with the right opportunities at the right time.  We will be part of the Google Play Partnerships team, focused on helping strategic Google partners have successful businesses using Google Play and the Android platform.  Google Play Store makes money from in-app purchases, cost to download the app, and advertising within the play store. 

### Business Objectives: 
Our main business objective is to help app owners in the Food Delivery Category determine how well they are doing as a brand.  We also would like to understand the product sentiment surrounding these brands, by analyzing the reviews that are left for that specific app or app category.  To provide app developers with the best insights, we will also need to conduct an overall analysis of the Google Playstore in order to create meaningful results that allow a business to take action.  

### Business Success Criteria
Our success criteria consists of KPIs and goals that we are aiming to achieve in order to deliver a strong result to our client, the Google Play Store partner. Examples of metrics that we will look at as KPIs include: ratings, rating counts, installs, and sentiment towards apps.  In order to showcase these success metrics, we will need to build dashboards using Tableau that provide views into how a certain app or app category is performing in the Google Play Store environment.  Using historical data, we will also utilize Python to model our sentiment analysis, making a properly running model a pivotal element of our business success criteria.  

## 1.2 Assess Situation [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Inventory of resources
Resources that we will utilize in our project include the people around us as well as tools and information found on the internet.  Human resources that will be key to the success of our project are our professors and advisors.  This includes the professor for this course Greg Lontok and other professors from other courses we are currently enrolled in.  Utilizing the group element of this group project, we will also be able to rely on each other for support and help should one of us ever get stuck on a task.  Tableau, Python, and SQL will be our key tools for analyzing the data and uncovering the necessary insights we are looking to find.  Project management tools will also be key to our success, including resources such as Trello and GitHub to organize our final assessment.  Since the business we are looking into is Google, we should be able to find plenty of information about the company readily at our fingertips through doing a quick internet search.  Likewise, through using the internet we can gain a better understanding and knowledge base about the Google Play Store.  

### Requirements, assumptions, and constraints
The requirements that will need to be completed on a regular basis will be recorded through the list of sprints that are required to be completed for this project.  They will be completed according to their due dates.  

Assumptions that we will need to make for this project are first, that the author of the Kaggle dataset we are using is pulling the data correctly from the Google Play Store.  After researching some web scraping of the Google Play Store, we are confident and comfortable in making the assumption that the Kaggle dataset was created correctly.  The second assumption is that we will need to assume that the Google Play Store monetizes on installs and in-app purchases.  With these two fields being looked at as potential KPIs, it is important for them to truly have an impact on Google.

The constraints we face include first, the availability of resources.  We are limited to ourselves, our professors, and the internet.  It will likely be difficult to find a primary source at Google who can provide data or help for this project.  Another constraint is that the review text is not included in the main Kaggle dataset, therefore we will need to do web scraping in order to source those records.  Finally, another constraint is that we are looking at a very specific segment of the marketing funnel with little transparency to other aspects of the funnel.  For example we can see the number of installs, but the marketing that is taking place at the top of the funnel to get those installs is not made known to us through our data.  
 
### Comprehensibility:

 
### Risks and contingencies
Our first risk is that we could fall behind on sprints, throwing off our deadlines and our overall final assessment.  The contingency to this risk is that we must maintain our schedule in Trello and let our team members know if we are falling behind on a task.  The communication regarding progress will be pivotal in ensuring we do not fall behind and we as a team can help each other succeed.

Our second risk is that we might have to find a new data set at some point during this project.  The contingency to this risk is that if we feel that we are missing data or certain variables that we need for analysis, then we may need to look for additional data sources.  We already see this being present in the need for review data.  The lack of reviews in the main Kaggle dataset means that we must web scrape our data to supplement our existing dataset.
 
### Terminology
The terminology that will need to be understood relates to how the columns in our data are named as well as the need to know of digital marketing terms and terms related to app data and app stores. The description of the columns in our data are certainly key terms that will need to be kept in mind (Please note the Data Description in Sprint 2 for column names).  Other key terms that will need to be noted is the use of the word acquisition being frequently used by Google to represent app installs.  It will be important to know terminology surrounding data mining and web scraping, as that will be a key source for obtaining data.  In the modeling phase we will need to familiarize ourselves with the terms related to the topic of sentiment analysis.  Overall, we will need to understand the terms being used in the data and the terminology being used as we progress through our analysis.

### Costs and benefits
Through undertaking this project we anticipate that there will be certain costs and benefits derived as outcomes from this project.  The main will be time.  We expect this thorough analysis into the Google Play Store will take an ample amount of time in order to glean the insights that we desire from the data.  

Meanwhile, we also expect there to be many benefits that outweigh the cost factor.  This will be a benefit to Google because it gives factual and data-driven insights that can help the play store better understand developer needs.  This project will likewise benefit the developers as they will be able to draw valuable insights into not only their app but also the Google Play Store environment as a whole.  Finally, this will be a benefit to us as a team since this project will provide valuable experience that we need to start our careers and will act as a strong resume builder.   

## 1.3 Determine Data Mining Goals [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)

### Data Mining Goals
The goals that we have for data mining are two fold.  First, we desire to mine data that allows us to analyze app reviews through text analysis, so that we can derive sentiment from those reviews.  Second, we want to find data that would appropriately supplement our original dataset in order to run machine learning models.  Possible machine learning models would include NLP, Word2Vec, or BERT in order to analyze our web scraped text data. 

### Data Mining Success Criteria
The success criteria that we have outlined for our data mining endeavors includes the following.  We seek to demonstrate we can create an accurate model from our mined data and provide a recommendation or prediction that would supplement our original analysis.  Likewise, we aspire to successfully run some type of sentiment analysis on review data mined from the Google Play Store, fulfilling the intended need for the web scraped data.  

## 1.4 Produce Project Plan [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)

### Project Plan: 
The project plan that we have laid out includes the following.  First, we will organize regular team meetings to collaborate on items that need collective input.  This team meeting will also provide an opportunity for us to allocate tasks to each team member according to the Sprint guidelines.  To that end, our next step in the project plan is to ensure we are following the given Sprint schedule.  This will allow us to maintain a consistent timeline and allow us to not fall behind on tasks and deliverables.  Next, we will need to acknowledge and keep in mind our risks and contingencies throughout the duration of the project.  In order to avoid falling into any major pitfalls, being aware of risks can help our group move forward with our tasks smoothly. We will also need to be sure to set group deadlines before actual deadlines.  Meaning, as a group we will need to set deadlines that we will be held accountable for, so as not to leave all tasks to the last minute.  Finally, we will utilize communication tools such as Microsoft Teams to coordinate our operations and plan our regular meetings.  Having strong and frequent communication will allow us to remain in sync and succeed in this project.   

### Initial Assessment of Tools & Techniques:
As we begin our project, there are several tools and techniques that stand out.  Tableau will be used for creating dashboards and analyzing KPIs, playing a key role in what we present as a final product.  Similarly, Python will be used to conduct analysis while also being used to clean and manipulate our data.  Python will also be used in our machine learning models.  Our machine learning models will primarily be built in order to address the portion of our project we are devoting to text analysis.  Text analysis is going to be used to analyze app review data to come to a conclusion regarding customer sentiment.  A project management tool we will be utilizing is Trello, which will allow us to organize our tasks and manage project goals.  Microsoft Teams will be a tool used to compliment Trello so that we as a team can communicate and be better organized when it comes to project management.  Finally, two techniques that we hope to implement successfully to benefit the operation of this project are Scrum and CRISP-DM.  Scrum is a technique we will use to organize team meetings, goals, and deadlines we have for the various Sprints.  Likewise CRISP-DM will be used to manage the project specifically relating to the tasks we need to accomplish and guiding us in how we need to approach certain tasks related to our project.  

# Sprint 2: 
# Data Understanding Phase
## 2.1 Collect Initial Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)

### Initial Data Collection Report
The following links are where our collected data is located.  This includes both the Kaggle dataset we found as well as two notebooks used for web scraping app reviews.    

→ Google Reviews Scrape: https://colab.research.google.com/drive/1jLlPrux8C4x_kxdt5lzTnD3LxnIRpkC5?usp=sharing

→ Food Delivery App Reviews Scraping: https://colab.research.google.com/drive/15MfyTemDVcDCmTipgLCaMS_RIAUepJuH?usp=sharing

→ Kaggle Google Play Store Apps: https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps

### Initial Data Cleaning Report



## 2.2 Describe Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Data Decription Report
The below report showcases the columns and data types for our datasets.  These are the main tables that will be used for our project and analysis.  Upon completion of Sprint 3 the data will be placed into an AWS database for easy querying of data through SQL or Tableau.

**applications Table (603,047 Rows)**
| PK/FK      | Name | Data Type |
| ----------- | ----------- | ----------- |
|       | app_name | object |
| PK      | app_id | object |
|       | category | object |
|       | rating | float64 |
|       | rating_count | float64 |
|       | installs | object |
|       | minimum_installs | float64 |
|       | maximum_installs | int64 |
|       | free | bool |
|       | price | float64 |
|       | currency | object |
|       | size | object |
|       | minimum_android | object |
|       | developer_id | object |
|       | released | object |
|       | last_updated | int64 |
|       | content_rating | object |
|       | ad_supported | bool |
|       | in_app_purchases | bool |
|       | editors_choice | bool |
|       | updated_date | datetime64 |
|       | estimated_installs | int64 |


**food_delivery_reviews Table (13,474 Rows)**
| PK/FK      | Name | Data Type |
| ----------- | ----------- | ----------- |
|   PK    | review_id | object |
|       | username | object |
|       | userimage | object |
|       | review_text | object |
|       | rating | int64 |
|       | up_count | int64 |
|       | review_created_version | object |
|       | reply_text | object |
|       | reply_date | datetime64 |
|       | sort_order | object |
|   FK    | app_id | object |

**app_reviews Table (12,495 Rows)**
| PK/FK      | Name | Data Type |
| ----------- | ----------- | ----------- |
|   PK    | review_id | object |
|       | userName | object |
|       | userImage | object |
|       | content | int64 |
|       | score | int64 |
|       | thumpsUpCount | object |
|       | reviewCreatedVersion | object |
|       | at | object |
|       | replyContent | object |
|       | repliedAt | object |
|       | sortOrder | object |
|   FK    | app_id | object |


## 2.3 Explore Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Data Exploration Report
In the early data exploration phase of this project we looked at the three datasets and ran simple analyses in Python to get a better understanding of how we can work with the data.   Using charts and graphs to visually represent columns and variables in the data we can easily and clearly interpret any trends or noticeable callouts in the data.  Through doing basic data exploration one can often find data quality issues, leading into the next section of Sprint 2.

Kaggle Google Playstore: https://colab.research.google.com/drive/1Nk2vDVvqLUrBaeQooCGDI6F0QJtTJdJB?usp=sharing

Food Delivery App Reviews Scraping: https://colab.research.google.com/drive/15MfyTemDVcDCmTipgLCaMS_RIAUepJuH?usp=sharing

Google Reviews Scrape: https://colab.research.google.com/drive/1jLlPrux8C4x_kxdt5lzTnD3LxnIRpkC5?usp=sharing



## 2.4 Verify Data Quality [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Data Quality Report
After doing basic data exploration, we made sure to address the data quality.  In this step we made sure the data consisted of all the variables we needed to run our analysis and proceed with the project.  Once the data content was deemed satisfactory, we began looking at what data cleaning steps would need to be taken.  We addressed data cleaning issues like null values, incorrect or unhandy data types, and the need to interpolate certain values.  Once data cleaning steps were addressed to ensure our data was at its highest quality, we were ready to proceed with the next stages of our project consisting of data modeling and analysis.  (The below notebooks are the same as the Data Exploration notebooks, for ease of use we kept Data Exploration and Data Quality in the same Python notebook)

Kaggle Google Playstore: https://colab.research.google.com/drive/1Nk2vDVvqLUrBaeQooCGDI6F0QJtTJdJB?usp=sharing

Food Delivery App Reviews Scraping: https://colab.research.google.com/drive/15MfyTemDVcDCmTipgLCaMS_RIAUepJuH?usp=sharing

Google Reviews Scrape: https://colab.research.google.com/drive/1jLlPrux8C4x_kxdt5lzTnD3LxnIRpkC5?usp=sharing


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
```

## 3.3 Construct Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
In our main Google Play Store dataset, minimum installs and maximum install values were provided in the data, but to get an approximate and more specific install number we created a new value to interpolate the values and create an estimated installs field that we can use in our analysis. Originally, we tried creating an estimated value by taking min+max / 2, but after further consideration we determined interpolating the values would be a more accurate and appropriate way to represent estimates.

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
The goal of our modeling phase is to add value to our dashboards by using the current variables to create richer ones with the help from some modeling. For model selection, we chose to conduct sentiment analysis. Sentiment analysis looks at the emotion expressed through text. This type of analysis would allow us to gain greater insight when it comes to customer opinions. Further, it would give us some more criteria to determine high risk reviews in the dataset, beyond simply looking at app ratings. This will help us identify how well DoorDash is doing when it comes to responding to agitated app users.

## 4.2 Generate Test Design [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
With our sentiment analysis, our hope is to be able to calculate and understand the polarity and subjectivity of reviews in the dataset. Polarity is a measure of how positive or negative the text is. Polarity lies in the range of -1 to 1, where 1 means a positive statement and -1 means a negative statement. Subjectivity is a measure of the amount of personal opinion and factual information contained in the text. A higher subjectivity means that the text contains more personal opinion rather than factual information. Subjectivity lies in the range of 0 to 1. If we can calculate these scores and they can provide us with interesting patterns and results, our model will be a success.

## 4.3 Build Model [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
To build our model we created two separate functions for computing polarity and subjectivity. We then applied them to our clean text column to give us a column for each with the calculated scores.

```
# create a function to get the subjectivity
def subjectivity(text): 
    return TextBlob(text).sentiment.subjectivity

# create a function to get the polarity
def polarity(text): 
    return TextBlob(text).sentiment.polarity
```

We now had 2 new variables in the dataset we could continue analyzing through our dashboards. This included polarity scores and subjectivity scores. This also gave us new criteria to work with when considering a high risk review from a sentiment standpoint. We will discuss this more in our model assessment.

## 4.4 Assess Model [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
As mentioned previously, a successful sentiment analysis would allow us to create additional variables that would allow for richer dashboards in the end. Specifically, we wanted to create a variable for high risk reviews. To determine high risk reviews in the dataset, we had to come up with criteria that took into account rating and sentiment scores. We determined that a “high risk” review would have a low rating (a rating of 1 or 2), a polarity less than 0, and a subjectivity score greater than 0.5. A negative polarity indicates negative review sentiment. Higher subjectivity means that the text contains personal opinion rather than factual information. 

With our newly calculated sentiment scores, we created a binary variable called “high_risk_review,” where if the review met all of the criteria it would display a 1, else a 0. We felt this variable would give us a good representation of high risk reviews. We also felt that this variable could easily be tailored to fit the needs of an app owner, like DoorDash, perhaps they want to be more or less strict on what they consider to be a “high risk” review. We created plots to look into the distribution of high risk reviews in the dataset and distribution of replies to high risk reviews. Just from this quick look we were able to see there is a lot of room for improvement when it comes to replies and is something valuable to look further into. In the end we were happy with our model results and we are ready to include the variable for high risk reviews into our dashboards.

# Evaluation Phase
## 5.1 Evaluate Results [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
We were able to create a machine learning model that predicts whether or not a review is considered “high-risk” and therefore needs to be responded to. This will allow for valuable insights to be generated for an app developer and allow that developer to address potential risks to ratings and app perception in a timely manner. 

Coupled with our predictive model, we will also showcase descriptive analytics displayed in operational and analytical dashboards that will likewise showcase valuable insights to the app developer. All of this will promote the business and role of a Business Analyst for Play Partnerships at Google.

## 5.2 Review Process [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
The first step of our modeling process was to understand how we wanted to approach addressing our goals and determine what model would best be suited for accomplishing this.  Once we determined that text sentiment analysis was the best method for us to draw insights from reviews from the app store, we set out collecting the necessary data and building the model.  We collected the necessary data for the text sentiment analysis and the EDA that we would conduct through finding any available pre existing data and then researching how to web scrape reviews from the Google Play Store.  We were successful in finding sources online that provided guidance in how to web scrape from Google’s platform.  

The next step of our process consisted of cleaning and preparing the data for analysis.  There were several elements in our various datasets that required cleaning and so we made sure to address any potential data issues that could hinder our progress in building and executing our desired models.   

Following the data cleaning, we built the models needed for analyzing both the general Google Play Store environment as well as the text sentiment analysis. Once the models had been built and were running smoothly, we revisited how we can use the outputs in order to create dashboards that would be meaningful to a client or business partner or in this case an app developer.  This led to us coming to the conclusion that some of our original questions may need to change slightly and the direction we want to go will have to be pivoted.  We learned that the datasets may not fully achieve the goals we originally set out and to achieve a granular look like we originally desired, we may need to change either our goals or how we approach the data. Once we determined the revised goals and came to a conclusion on how we want to use our outputs, we set out on creating the dashboards and providing valuable insights from our data. 


## 5.3 Determine Next Steps [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
With our models created, goals refined, and early stages of the dashboard creation begun, we can look towards our next steps as we progress further into the final stages of this project.  First and foremost, we will need to finalize our dashboards as those are at the center of our analysis and will guide us in creating business insights.  Once the dashboards have been created, we will need to review what is being visualized and what analysis and meaning can be drawn from the dashboards to provide a recommendation to our client.  Based on our results we will share how the client’s app is doing in relation to similar apps in their category and against the Google Play Store environment as a whole.  

With the dashboards created and insights gained, we will then want to revisit the Machine Learning and Deep Learning models that were created in order to conduct the text sentiment analysis.  We would want to see how these models could be potentially improved for future use or see if there are any next steps for building the models out further for an even deeper analysis in the future.  

After we review our models and dashboards, we will look to construct our final report and prepare for our presentation.  We will finalize all of the written material from the previous sprints in order to make a final report that can be created in the form of a GitHub ReadMe file.  The final presentation will require us to build a slide deck with all of our insights, dashboards, explanation of our data, and most importantly our conclusion and recommendations for our clients.  

Finally, with the report and presentation completed, we evaluate how our project functioned as a whole.  We will need to review what went well and what should be improved upon for future projects of this nature.  Examining our progress and end result internally as a team will help us grow in our ability to manage projects and effectively apply skills we’ve learned to projects later in our careers. 



# Deployment Phase
## 6.1 Plan Deployment [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
Deployment Plan:

## 6.2 Plan Monitoring & Maintenance [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)

Plan Monitoring & Maintenance: 
In order to maintain our data system in the future, a few systems would need to be implemented. First, we would need to be able to pull a more real time version of our Kaggle dataset that has high level metrics surrounding all apps on the google play store. We could then maintain this data through our AWS instance after it is dumped in through some sort of procedure that rights any additions or modifications to the table on some sort of cadence (daily, hourly, weekly, etc). Next, the organization would need to decide what would be the most beneficial form of continuing to update the machine learning models. We could decide if these insights are necessary for continued reporting or if data mining and machine learning models should be included only on an ad hoc basis. Once those decisions are made, Tableau will be able to refresh from our continually refreshing AWS PostgreSQL database. We can create Tableau report data extracts that update on a certain cadence or published Tableau Data Sources that will allow the team to see updated metrics that lead to more real time insight. This overall flow will need to be maintained by the team to ensure that bugs and other refresh errors are handled with care and timeliness. 

## 6.3 Product Final Report [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
Final Presentation Link:

## 6.4 Review Project [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
Experience Documentation:

What should we start doing?: Our group feels that, although we enjoyed the two week sprint system, the workload of the 2 week periods was inbalanced. If we had the ability to start earlier on the first few sprints (or combine 1 and 2 into one 2 week sprint), then we would be able to break up sprint 3 into more approachable and digestible chunks. 

What should we stop doing?: The project description was very comprehensive and in some places repetitive. If the project description and some of the sprints were more succinct this might have been beneficial for the project overall. 

What should we continue doing?: The project management portion of this project is great for our group to be able to hone our skills regarding working in an Agile environment. The freedom to pick a specific job to tailor our project to was also helpful. Our group also benefited from regular meeting times. This scheduled system allowed us to stay on track throughout the project and assign tasks via Trello to be done before or after these meetings. 
