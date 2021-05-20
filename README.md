# May 2021

# Microloans & Microlending: Ironhack F.P
![image](https://user-images.githubusercontent.com/80153432/119024531-73e30e00-b9a3-11eb-9622-d1f41fbfd9e1.png)
Photo Source: Kiva.com

# What is Kiva?
Is an international nonprofit, founded in 2005 in San Francisco, with a mission to expand financial access to help underserved communities thrive.

Exploring the data, Wranglingand Cleaning, Developing a Machine Learning Model and creating Visualisations on Kiva Loans a dataset got from Kaggle(https://www.kaggle.com/kiva/data-science-for-good-kiva-crowdfunding).


# Content
*[Project Outline](#project-outline)
*[Scenario](#scenario)
*[Objective](#objective)
*[Variables-description](#variables-description)
*[Data](#data)
*[Database](#database)
*[Visualisation](#visualisation)
*[Statistical Analysis](#statistical-analysis)
*[Conclusion](#conclusion)


# Project Outline
The project started with looking for suitable data to work with, which was then downloaded from Kaggle. The data was wrangled(converting and mapping it so as to prepare it for futher analysis steps) and cleaned(finding and correcting inaccuracies) of duplicate records, empty fields and fixing structural errors). All these processes prepared it for developing a model which predicts; if sector and gender determine how fast and successful a loan application is on Kiva.This output was further visualised using Tableau to answer this hypothesis as well as give insights otherwise unseen through just text and numbers. 


# Objectives
1. To build a model that will predict the the sucess of loan applications based on features provided in the dataset.

2. If impact can meausured based on how successful of failure a funded project is, if the platform is creating sustained development or more dependency. 


# Description of Variables
- id: Loan ID
- funded_amount: Amount of loan which has been purchased by Kiva lenders
- paid_amount: Amount of the loan which has been paid off
- activity: Activity for which loan is requested
- sector: Sector for which loan is requested
- country_code: Country code
- country: Country name
- region: Town name
- location.geo.level: Indicator for whether the latitude and longitude given is for country or  town
- partner_id: Field partner ID for local lending institutions, see a complete list at      https://www.kiva.org/about/due-diligence/field-partner-role
- borrowers.first_name: First name of borrower
- borrowers.last_name: Last name of borrower
- borrowers.gender: Gender of borrower
- currency: Payment amount in local currency
- processed_date: Date payment is processed
- rounded_local_amount: Rounded local payment amount
- settlement_date: Settlement date of payment
- lat: Latitude of loan location, as indicated by location.geo.level
- lon: Longitude of loan location, as indicated by location.geo.level
- Source: https://www.kaggle.com/kiva/data-science-for-good-kiva-crowdfunding


# Data

The data was outsourced from Kaggle. I at one point attempted Web Scrapping for more information on impact which was not successful.

Python was used for all codes to conduct several steps which dived deeper into the data to reach the analyis and reporting stage. 

Also several libraries were heavily relied on for plotting visualisations and and analysis such as: 
- pandas
- seaborn
- xlrd
- openpyxl
- pywedge
- matplotlib
- sklearn
- stats model
- datetime
- scipy

# The WorkFlow
![image](https://user-images.githubusercontent.com/80153432/119024207-2070c000-b9a3-11eb-9bc9-9aaf085efd5f.png)


# Visualisation
Tableau visualise distinctive  plots, grapths, pie charts and dashboards so that the data is analysed and understood more meaningfuly to draw insights. 
Tableau visualizations for this project can be found under this link; 
![image](https://user-images.githubusercontent.com/80153432/119027476-aa6e5800-b9a6-11eb-88d7-d3ed0a301e56.png)



# Conclusion
Features of greatest significance included the sector, gender, country, loan amount and funded amount; all deserving of further exploration and may be of importance in an unsupervised learning attempt such as clustering.

The results are not to my satisfaction.Getting data on success meatures would have given more insights into tracking the Kiva crowd funding model. Also it is such a beautful data source full of insights given adequate time for deeper exploration.



# Useful Links
In addition to Ironhack class material, here are some other useful sources.
- https://www.kaggle.com/kiva/data-science-for-good-kiva-crowdfunding
- https://scikit-learn.org/stable/modules/generated/sklearn.multiclass.OneVsRestClassifier.html
- https://www.analyticsvidhya.com/blog/2021/02/interactive-widget-based-hyperparameter-tuning-and-tracking-in-pywedge/
- https://scikit-learn.org/stable/modules/generated/sklearn.multiclass.OneVsOneClassifier.html
- https://programmerbackpack.com/introduction-to-random-forests-classifier-and-step-by-step-sklearn-implementation/
- https://towardsdatascience.com/scale-standardize-or-normalize-with-scikit-learn-6ccc7d176a02#:~:text=MinMaxScaler%20preserves%20the%20shape%20of,MinMaxScaler%20is%200%20to%201.
- https://pypi.org/project/pywedge/
