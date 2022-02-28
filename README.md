Udacity project - Starbucks Capstone project

Analysis on Starbucks mobile app data.

#### Datasets:

Data comes from the Starbucks' mobile app.

The Starbucks mobile app data is contained in three datasets:

profile.json - user database

portfolio.json - offer types and characteristics

transcript.json - transactions made by users


#### Topics discussed:

-How demographic groups respond to offers 

-How each offer type performs and what revenue it generates.

The discoveries are detailed in [this blog post](https://medium.com/@tudosedotstefan/transaction-analysis-for-the-starbucks-mobile-app-9afdf8ab9723)

## Project files


##### ./data

This folder contains the raw files of the Starbucks transactions. 

##### Starbucks_Capstone_notebook.ipynb

The first notebook contains the steps taken to clean and model the data.

##### Starbucks_Capstone_analysis.ipynb

Modelled data is retrieved from the three databases and analysed. Topic questions are found and answered here.

#### OfferPerson.db, Portfolio.db, Profile.db

These databases are the result from the Starbucks_Capstone_notebook ready for analysis.

## Project dependencies

Main programming language and package manager
- Python 3.8+
- pip - package manager - https://pypi.org/project/pip/

Data Analysis
- Pandas - https://pandas.pydata.org/
- NumPy - https://numpy.org/

Database management
- SQLAlchemy - https://www.sqlalchemy.org/