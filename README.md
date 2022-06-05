# Portfolio
Aditya Phulallwar Data Science Portfolio


## [Project 0 - Recette : Project Overview](https://github.com/addy024/recette)
* Recette is a recipe book plus an e-commerce app. It features recipes all over the cuisines and service to purchase online all the ingredients required to make your
favourite recipe all in a single app.
* Recette specialist is that it is a Single Page Application (SPA) and cross-platform application well simply it can run on any browser and also IOS and android mobile device. 
* Recette not only provides the platform for the home chef to publish their recipes to a whole world but also earn some commission form their work.
* Well, there may be many blogs or even an app for recipes, but the problem arises when you start to prepare them. Most of the time, you won't get all the ingredients
at your local store, you want to make that delicious dish, you give up making them. But not anymore with the Recette you can order all the required ingredients
for your recipe in a single click. All the ingredients with the required amount will be delivered at your doorstep.

![](/images/recette1.png)


## [Project 1 - Credit Card Defaults : Project Overview](https://github.com/addy024/Credit-Card-Defaults/blob/main/Credit_Card_Defaults_project.ipynb)
* **Goal** - is to develop a predictive model for whether an account will default next month, given demographics and historical data.
* Defined Business Problem. 
* Familiarized with Data and Performed Data Cleaning with Verification of Data Integrity.
* Explored the Credit Limit and Demographic Features, Implemented One-Hot Encoding for a Categorical Feature, Explored the Finanical History Features in the Dataset, Explored the Response Variable and Concluding the Initial Exploration, Examined the Relationships between features and the Response Variable (Visualized too).
* Modeling **(Logistic Regression,
 Random Forest,
 XGBoost Classifier)**
* Characterized Costs and Savings.

![](/images/CreditCardDefaults.png)


## [Project 2 - KPI and Engagement to Conversion Explanatory Analysis on Bank Marketing : Project Overview](https://github.com/addy024/KPI-and-Engagement-to-Conversion-Explanatory-Analysis-on-Bank-Marketing/blob/main/Bank_Marketing.ipynb)
* **Goal** - is to identify KPI and perform Explanatory Analysis On Conversion using Modeling. 
* Explore various factors with respect to Conversion rate, such as 
  * Contact
  * Age 
  * Age Group and Marital Status 
  * month 
  * Job 
  * Default Rates 
* Prepared data for Explanatory Modeling (Encoded Categorical Variables)
* Modelled a Decision Tree  
* Interpret the Decision Tree and Gain Insights.

![](/images/KPIAndEADecisionTree.png)


## [Project 3 - Airbnb's in New York - Project Process Overview](https://public.tableau.com/app/profile/aditya.phulallwar/viz/AirbnbsinNewYork_16433013641550/AirbnbsinNewYorkCity)
* Data join, blending and union.
* Geographical Roles
* Parameters 
* Created a Measure Selector for displaying different measures on a graph.
* Edited Tooltips
* Customizing - and formatting - filters in dashboards
* Dashboard actions
* Custom color palettes

![](/images/Airbnb.png)


## [Project 4 - Google Play Store Exploratory Data Analysis](https://github.com/addy024/Google-Play-store-apps-exploratory-data-analysis-/blob/main/Jovaian_ml_EDA_project.ipynb)
**Inferences and Conculsion**
* Most of the values Size of Apps are "Varies with device" or are less than 20mb.
* Most of the App ratings are in between 4 and 5.
* Communication, entertainment, social and video players apps have more installations than any other categories.
* There are more Family type of apps in the google playstore.
* There no such strong relation to indicate that Price of app effect number of installations but it does indicating weak negative relation.
* There are far more Free apps and paid apps.
* Only 7% of apps are Paid ones.
* "I'm Rich - Trump Edition" App is the most costliest app in the Google PlayStore.
* There are 44 apps that has installations over 100 millions.
* Communication type of apps has the most number of 100+ milions installations.
* Looks like people really enjoyed and gave mostly positive review to "10 Best Foods for You".
* July has most number of updates than any other months.
* Minecraft App has earned the highest amount over 69,900,000.

![](/images/GooglePlayStore.png)


## [Project 5 - Movie Recommendation System : Project Overview](https://github.com/addy024/Movie-Recommendation-System)
**Conculsion**

   * The user with the highest number of records has rated 2391 movies.
   * Each user has rated atleast 20 movies.
   * The Movie with the highest number of ratings is Forrest Gump (1994) and has been rated 341 times.
   * Each movie has been rated by atleast one user.
   * The recommendations for the userId 85 are Half Baked (1998) and Pink Flamingos (1972).

**Process**

  * Import and Prepare data(join, Check validation of data,).
  * Data Analysis.
  * Feature Engineering. (Convert Title name to title Id)
  * Modeling - ALS. 
  * Recommend top movies which user might like.
  * Helper Function for future predictions.
  * Save Model.

![](/images/movie.png)


## [Project 6 - Food101](https://github.com/addy024/Food101)

**Process**

 * Explore the Food101 data from TensorFlow datasets
 * plotting images
 * Preprocessing functions 
 * Batch and prepare dataset
 * Modelling callbacks
 * Setup mixed precision model
 * Preparing model's layer for fine tuning
 * EfficientNetB0
 * Evaluation and Preditions 


![](/images/Samosa.png)

## [Project 7 - SkimLit](https://github.com/addy024/SkimLit)

Replication of the deep learning model behind the 2017 paper PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts. Transfer Learning with pre-trained token embedding + character embedding + positional embedding.

**Process**

 * Process data
 * Label encode
 * baseline model with TFidfVectorizer and MultinomialNB
 * Custom Text embedding
 * Conv1D with token embeddings
 * NLP feature extraction model from Tensorflow Hub
 * Conv1D with character embedding
 * Combining pretrained token embeddings + character embeddings (hybrid embedding layer)
 * Transfer learning with pretrained token embeddings + character embeddings + positional embeddings (tribrid embedding)
 * Evaluating and Predictions

![](/images/model.png)


## [Project 8 - Nyc Taxi Data ETL Pipeline and Reporting Dashboard](https://github.com/addy024/NycTaxiDatasetETLAndReporting)

**Scenario:** We will be resposible for processing New York City Taxi Service data. There are three types of taxis/services in New York. Yellow Taxis, Green Taxis and For Hire Vehicles and We collect ride-related information. We receive this data once a month in the form of different file format such as parquet, csv, json, etc. Our Task is to Orchestrate the pipeline for extract, Transform and build dimensions and facts for making monthly aggregated reports and KPIs.

Data Source - https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

![](/images/Report1.png)

**Orchestrating the Pipeline Process**
 * Build Data Lake (Databricks DBFS)
 * Capture raw data in DataLake.
 * Use Databricks to profile, merge & process data. (Spark, Scala)
 * Build dimensions, facts, KPIs & reporting (Spark, Scala, Spark sql, Databricks Dashboard)
 * Store Data back to Data lake 

![](/images/Report2.png)

![]([/images/Dashwarehouse.png](https://github.com/addy024/Portfolio/blob/main/images/Datawarehouse.png))
