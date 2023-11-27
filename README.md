# TED_Talks_view_prediction_project
TEDed-Talks-views-prediction
TED is devoted to spreading powerful ideas on just about any topic. These datasets contain over 4,000 TED talks including transcripts in many languages Founded in 1984 by Richard Salman as a nonprofit organization that aimed at bringing experts from the fields of Technology, Entertainment, and Design together, TED Conferences have gone on to become the Mecca of ideas from virtually all walks of life. As of 2015, TED and its sister TEDx chapters have published more than 2000 talks for free consumption by the masses and its speaker list boasts of the likes of Al Gore, Jimmy Wales, Shahrukh Khan, and Bill Gates.

---

### Dataset info
    * Total Number of records: 4,005

    * Total Number of attributes ( Column ): 19

### Features information:
* 1. talk_id: Talk identification number provided by TED
* 2. title: Title of the talk
* 3. speaker_1: First speaker in TED's speaker list
* 4. all_speakers: Speakers in the talk
* 5. occupations: Occupations of the speakers
* 6. about_speakers: Blurb about each speaker
* 7. recorded_date: Date the talk was recorded
* 8. published_date: Date the talk was published to TED.com
* 9. event: Event or medium in which the talk was given
* 10. native_lang: Language the talk was given in
* 11. available_lang: All available languages (lang_code) for a talk
* 12. comments: Count of comments
* 13. duration: Duration in seconds
* 14. topics: Related tags or topics for the talk
* 15. related_talks: Related talks (key='talk_id',value='title')
* 16. url: URL of the talk
* 17. description: Description of the talk
* 18. transcript: Full transcript of the talk
 
### Target Variable :

    * views: Contains Count of views of every talk

# The main objective of the project is to build a predictive model, which could help in predicting the views of the videos uploaded on the TEDx website. 
For that we have to do some feature engineering as follows:

* Here, we have only 3 numerical columns in our dataset out of which 1 is our target variable and 2 can be used as features and rest all columns are either categorical or they contains textual data.
* Therefore , our main goal here is to find or generate some numerical or categorical features using these columns. 

# Prerequisites

  * Good understanding of ML algorithms

# Technologies/ Framework used

  * IDE- Google colab

# Project Work flow
---

1. Importing Libraries

2. Loading the dataset

3. Data Cleaning

4. EDA on features

5. Feature selection

6. Fitting the regression models

7. HyperParameter Tuning

8. Evaluation Metrices of the model

9. Final selection of the model

10. Conclusion

# XGBoost

1. XGBoost stands for Extreme Gradient Boosting. XGBoost is a powerful machine learning algorithm that is dominating the world of applied machine learning and Kaggle competitions. It is an implementation of gradient boosted trees designed for speed and accuracy.

2. XGBoost (Extreme Gradient Boosting) is an advanced implementation of the gradient boosting algorithm. It has proved to be a highly effective machine learning algorithm extensively used in machine learning competitions. XGBoost has high predictive power and is almost 10 times faster than other gradient boosting techniques. It also includes a variety of regularization parameters which reduces overfitting and improves overall performance. Hence, it is also known as regularized boosting technique.

# Looking Forward

Concluding our exercise, we've navigated through several crucial steps. Commencing with the loading of data, we proceeded to execute exploratory data analysis, addressed null values, encoded categorical columns, performed feature selection, and subsequently engaged in model building. Throughout these stages, our model errors consistently maintained a range of 2,00,000, approximately 10% of the average views. Impressively, we achieved a 90% accuracy rate in predicting views. Post hyperparameter tuning, we successfully mitigated overfitting, minimized errors through regularization, and reduced the learning rate.

Given that our errors account for only 10%, our models have demonstrated commendable performance on unseen data, owing to factors like adept feature selection and precise model choices.

Looking ahead, future endeavors include implementing dynamic regression time series modeling, leveraging the availability of time features. Additionally, to enhance views on less popular topics, a strategic approach involves engaging more popular speakers. Moreover, we can employ topic modeling techniques to address views within each topic independently.


























