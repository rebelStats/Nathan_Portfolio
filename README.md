# Nathan_Portfolio
Nathan Kardos's Data Science Portfolio

# [Project 1 : Image Classification of Wild vs Farmed Salmon Using the Vision Transformer (ViT) Model](https://github.com/rebelStats/Vision_Transformer_Salmon)
* Acquired 400+ labeled images of wild and farmed salmon from Kaggle API.
* Developed image preprocessing pipeline in Python to introduce horizontal and vertical image rotation in PyTorch.
* Developed and optimized image classification pipeline with Vision Transformer (ViT) model using both HuggingFace API and Pytorch Lightning, achieved 85% model accuracy on test dataset.
* Established 2 model deployment pipelines, AWS SageMaker Real-time Inference Endpoints with S3 and Lambdas as backend. and a Flask WebApp in Python on open-sourced platform (Heroku).



# [Project 2 : Public Bike Rental Ride Distance Analysis and Modeling](https://github.com/rebelStats/Bike-Data)
* Public bike rental dataset was downloaded from Kaggle
* Data was cleaned and new features created
* Multiple predictive models were implemented with Random Forrest performing the best as expected
* App to predict bike ride distances was published on [Streamlit](https://rebelstats-bike-data-streamlitbike-app-of2ukx.streamlitapp.com/)


# [Project 3 : Data Science Salary Scarping and Cleaning](https://github.com/rebelStats/ds_sal)
* Built a scraper using Seleium to scrape hundreds of job postings from Glassdoor.com
* Glassdoor updates their site frequently so it may not run anymore (data scraped in Fall 2021)
* Data was gathered from different cities in the US using the Glassdoor search engine
* Data was cleaned and too few useful oberservations were gathered to create any models


# [Project 4 : Kaggle's Titanic Dataset](https://github.com/rebelStats/TitanicAnlysis)
* Built a predictive model using kaggle's popular Titanic dataset
* Data was cleaned and missing values were imputed using KNN imputation
* Categorical variables were created from quanitative variables
* Implemented XGboost with parameter tuning with grid search

# [Project 5 : Statistical Analysis of Differences in Personality Among Ages and Genders](https://www.yumpu.com/en/document/read/66248233/personality-analysis)
* Analyzed personality survey data from Univeristy of Pensylvania
* Analyzed the relationship between personality and age as well as personality and sex
* Built regression and other predictive models to predict sex from personality
