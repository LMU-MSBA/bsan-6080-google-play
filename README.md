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

# Sprint 1: 
# Business Understanding Phase
## 1.1 Determine Business Objective [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Background: 
Our mission is connecting the right third-party app and game developers with the right opportunities at the right time.  We will be part of the Google Play Partnerships team, focused on helping strategic Google partners have successful businesses using Google Play and the Android platform.  Google Play Store makes money from in-app purchases, cost to download the app, and advertising within the play store. 

### Business Objectives: 
 1. Determinants of install 
 2. Number of installs vs. ratings
 3. Under performing apps
 4. App Categories
 5. Who is performing well and what do they have in common? Who isn’t performing well and why do they underperform?


### Business Success Criteria
→ Data pipeline that connects cleaned data to our business intelligence visualization and modeling tools

→ Tableau dashboard for high level view of the KPIs

→ Python Model to provide recommendations to key stakeholders based on historical data

## 1.2 Assess Situation [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Inventory of resources
→ Greg Lontok 

→ Gautham (author of Kaggle dataset)

→ Tableau, Python, Trello, Project Management 

→ Fellow group members  

→ Google Play Store and Google

→ Other faculty and coding reference materials for Machine Learning and Text Analysis

### Requirements, assumptions, and constraints
→ List sprints and what is due 

→ Assuming correct and error-free data was pulled by Gautham 

→ Assuming Google Play monotizes on installs and in-app purchases 

→ Availability of resources

→ Lack of transparency in some columns (ex: in-app purchases is boolean) 

→ Review text is not included in the dataset, so we must scrape the text ourselves

→ Lack of transparency on full funnel (we are only seeing the middle of the funnel like inventory data and user in app purchase data is not available)
 
### Comprehensibility:

 
### Risks and contingencies
→ Risk: Falling behind on the sprints 

    → Contingency: We must maintain our schedule and let our team members know if we are falling behind on something
  
→ Risk: Might have to find a new data set

    → Contingency: If we feel that we are missing data or certain variable we need for analysis, we may need to look for additional data sources
 
### Terminology
→ Description of each of the columns

→ Digital marketing and app field

→ Acquisition = installs

→ Data mining

→ Sentiment analysis 

→ Ratings (goes back to description of the columns)

→ Understanding of the terminology used in the data


### Costs and benefits
→ Time 

→ Insights gleaned 

→ Benefit to Google because it gives factual and data-driven insights that can help the play store better understand developer needs

→ Benefit to developers 

→ Benefit to the people

→ Benefit to us in workforce (experience)

## 1.3 Determine Data Mining Goals [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)

### Data Mining Goals
→ Mine data that allows us to analyze app reviews through text analytics 

→ Find data that would supplement our original dataset in order to run machine learning models

    → Possible ML:  kNN (Recommendation model) 

### Data Mining Success Criteria
→ Demonstrating we can create an accurate and provide a recommendation or prediction that would supplement our original analysis, using the data we mined

→ Successfully run some type of sentiment analysis on review data mined from the Google Play Store

## 1.4 Produce Project Plan [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)

### Project Plan: 
→ Regular team meetings to collaborate on items that need team input and attribute tasks to each team member 

→ Follow given sprint schedule 

→ Acknowledge and keep in mind our risks and contingencies

→ Set group deadlines before actual deadlines

→ Prioritize using the Fibonacci Scale

→ Utilize Microsoft Teams for coordinating

### Initial Assessment of Tools & Techniques:
→ Tableau: Used for creating dashboards and analyzing KPIs

→ Python:  Used to clean and manipulate/organize the data

→ Machine Learning Models:  Used to do in depth predictive and recommendation analyses

→ Text Analysis:  Used to analyze review data to come to a conclusion regarding customer sentiment

→ Trello:  Used to organize the group and manage project goals/tasks

→ Microsoft Teams:  Used to communicate with the group

→ Excel:  Platform used for storing the CSV with our data

→ Scrum:  Used for organizing team goals and deadlines

→ CRISP-DM: Used for project management 


# Sprint 2: 
# Data Understanding Phase
## 2.1 Collect Initial Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)

### Initial Data Collection Report
→ Google Reviews Scrape: https://colab.research.google.com/drive/1jLlPrux8C4x_kxdt5lzTnD3LxnIRpkC5?usp=sharing

→ Food Delivery App Reviews Scraping: https://colab.research.google.com/drive/15MfyTemDVcDCmTipgLCaMS_RIAUepJuH?usp=sharing

→ Kaggle Google Play Store Apps: https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps

### Initial Data Cleaning Report



## 2.2 Describe Data [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Data Decription Report

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
→  Data Quality and Data Exploration included in same Python notebooks

Kaggle Google Playstore: https://colab.research.google.com/drive/1Nk2vDVvqLUrBaeQooCGDI6F0QJtTJdJB?usp=sharing

Food Delivery App Reviews Scraping: https://colab.research.google.com/drive/15MfyTemDVcDCmTipgLCaMS_RIAUepJuH?usp=sharing

Google Reviews Scrape: https://colab.research.google.com/drive/1jLlPrux8C4x_kxdt5lzTnD3LxnIRpkC5?usp=sharing



## 2.4 Verify Data Quality [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)
### Data Quality Report
→ Data Quality and Data Exploration included in same Python notebooks

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


## 4.2 Generate Test Design [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)


## 4.3 Build Model [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)


## 4.4 Assess Model [↑](https://github.com/LMU-MSBA/bsan-6080-google-play#table-of-content)


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
