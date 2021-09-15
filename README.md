#COVID-19 VAERS ANALYSIS

# Self-Assessment ..

I was responsible for overseeing the collection, GitHub storage, and interpretation of data for a COVID-19 VAERS ANALYSIS. My duties included sifting through data points, reviewing the initial dataset. I created and organized the first version of the readme file. I was able to help chose the topic. I wrote the report outlining Covid Vaccines Adverse events using Tableau to help with the questions and selection of the Machine learning to predict life-threatening events for people over the age of 60.  

We communicated well with each other. We focused on goals and results. Everyone contributes their fair share. We offered each other support. We were organized, and  overcame the challenges to analyze & evaluate risk factors using adverse events based on age to predict the life-threatening risk probability of receiving a COVID-19 vaccine. 

# Team Assessment  

We did a great job comuncation over Slack, Zoom and Google Meet 4 times week. In addiontion to the clases were able to meet Saturdays and Sundays to be able complete the project. We had chanllenges with size of the dataset, but we were able to find a solutions by applying what we learned throught the couse. We followed the ETL process and applyed the following steps. 

## Preliminary Data Preprocessing:
Using LabelEncoder, we will take a list of the symptoms that were found from patients with life threatening events, and convert them each into unique numbers.
After that, we use OneHotEncoder to encode the other categorical features as an array.
Using StandardScaler, we use it to remove the mean and scaling to unit variance.

## Preliminary Feature Engineering and Selection:
For our feature selection, we went with a plotly bar graph to show feature importance of the top 15 columns. We decided to use this over the SelectFromModel feature because it was visually easier to read and gave us the different levels of the least important columns.

## Training and Testing:
Applying the Train_Test_Split method, it uses arrays or matrices into random train and test subsets to input data into a single call for splitting (and optionally subsampling) data in a one-liner. At this time, there is no need for additional training of this model.


Here are a few qualities that green team possesses.
1) We communicate well with each other.
2) We focus on goals and results. 
3) Everyone contributes their fair share. 
4) We offered each other support. 
5) Team members are diverse.
6) Good leadership.
7) We are organized. 
8) We have fun.



# Summary of Project 

Presents a cohesive, three- to four-sentence 
summary of the project that could be used on a 
LinkedIn profile, in an interview or cover letter, or 
as an elevator pitch, including all of the following: 
✓ Topic addressed ✓ Machine module used ✓ Results of the analysis 

I was responsible for overseeing the collection, storage, and interpretation of data for a COVID-19 VAERS ANALYSIS. Our duties include sifting through data points to create organized categories, comparing data points to current data processes, loading the data in a SQL database and writing reports outlining Covid Vaccines Adverse events using Tableau and created a project were we used Machine learning to predict life-threatening events for people over the age of 60.  

## Machine Learning Model: Random Forest Classifier
we learned how to utilize Scikit-Learn's RandomForestClassifier, an ensemble learning model, to predict life-threatening events for people over the age of 60. Originally, we looked into predicting life-threatening events for people who either died, or were hospitalized but the data was too skewed to produce any usable results. The type of data provided ultimately led to this model and process.

## Model:
We used RandomForestClassifier, an estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. Even though multiclass-multioutput is not supported, it was the best option because of reduced variance from combining diverse trees

## Accuracy Score:
As of right now, the random forest predictive accuracy is 72%. With the dataset narrowed down to ids that only contained life-threatening symptoms, it is predicting the chance of these symptoms to happen to people over the age of 60.

## Conclusion:
We were able to predict life-threatening events for people over the age of 60 by narrowing down to a DataFrame containing ID's that only had those filtered symptoms. There are further changes we can try, by doing slight adjustments to our model. We could run the prediction for each gender over 60, or even predict for each Covid-19 vaccine.

