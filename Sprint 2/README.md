# Sprint 2 - Data Understanding
## 2.1 Task: Collect Initial Data
### Initial Data Collection Report: 
→ Google Reviews Scrape: https://colab.research.google.com/drive/1jLlPrux8C4x_kxdt5lzTnD3LxnIRpkC5?usp=sharing

→ Food Delivery App Reviews Scraping: https://colab.research.google.com/drive/15MfyTemDVcDCmTipgLCaMS_RIAUepJuH?usp=sharing

→ Kaggle Google Play Store Apps: https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps


## 2.2 Task: Describe Data
### Data Description Report: 
 
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


## 2.3 Task: Explore Data
### Data Exploration Report: 
→  Data Quality and Data Exploration included in same Python notebooks

Kaggle Google Playstore: https://colab.research.google.com/drive/1Nk2vDVvqLUrBaeQooCGDI6F0QJtTJdJB?usp=sharing

Food Delivery App Reviews Scraping: https://colab.research.google.com/drive/15MfyTemDVcDCmTipgLCaMS_RIAUepJuH?usp=sharing

Google Reviews Scrape: https://colab.research.google.com/drive/1jLlPrux8C4x_kxdt5lzTnD3LxnIRpkC5?usp=sharing

## 2.4 Task: Verify Data Quality

### Data Quality Report: 
→ Data Quality and Data Exploration included in same Python notebooks

Kaggle Google Playstore: https://colab.research.google.com/drive/1Nk2vDVvqLUrBaeQooCGDI6F0QJtTJdJB?usp=sharing

Food Delivery App Reviews Scraping: https://colab.research.google.com/drive/15MfyTemDVcDCmTipgLCaMS_RIAUepJuH?usp=sharing

Google Reviews Scrape: https://colab.research.google.com/drive/1jLlPrux8C4x_kxdt5lzTnD3LxnIRpkC5?usp=sharing
 




