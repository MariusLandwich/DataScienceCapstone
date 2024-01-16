# DataScienceCapstone


## 📑 Summary
This is the final capstone of the "IBM Data Science Professional Certificate" that combines all the course content into one project. The project aims to predict whether the first stage of the Falcon 9 rocket will land successfully and to find the optimal place for the rocket launches.

My Certificate can be found <a href=https://www.coursera.org/account/accomplishments/professional-cert/8YX3K3W9C857>here</a>.

### Business Understanding
SpaceX is able to launch Falcon 9 rockets at a cost of approximately $62m which is far cheaper than other providers. The cost saving comes form the ability to land and reuse the first stage of the rockets. If we can make predictions on whether the first stage will land, we can determine the cost of a rocket launch and use this information to assess whether or not an alternate company should bid against SpaceX for a rocket launch.

## 📑 Main Topics
The project includes the folowing steps:

1. [Data Collection](https://github.com/MariusLandwich/DataScienceCapstone/tree/main/01.%20Data%20Collection)
   - GET Requests to the SpaceX REST API
   - Web Scrapping to collect Falcon 9 historical launch records from a Wikipedia page
2. [Data Wrangling](https://github.com/MariusLandwich/DataScienceCapstone/tree/main/02.%20Data%20Wrangling)
   - Using the `fillna()` method to remove all of the NaN values
   - `value_counts()` method to determine the following:
        - Number of launches on each site
        - Number and occurrence of each orbit
        - Number and occurrence of mission outcome per orbit type
   - Creating a landing outcome label that shows the following:
        - 0 when the booster did not land successfully
        - 1 when the booster did land successfully
3. [Exploratory Data Analysis](https://github.com/MariusLandwich/DataScienceCapstone/tree/main/03.%20Exploratory%20Data%20Analysis)
   - Using `SQL` to manipulate and evaluate the SpaceX dataset in order to get a better understanding of the data
   - Using `Pandas` and `Matplotlib` to visualize relationships between variables, and determine patterns
4. [Interactice Visual Analytics](https://github.com/MariusLandwich/DataScienceCapstone/tree/main/04.%20Visual%20Analytics)
   - Geospatial analytics of the data using `Folium`
   - Creating an interactive dashboard by using `Plotly Dash`
5. [Predictive Analytics (Classifiaction)](https://github.com/MariusLandwich/DataScienceCapstone/tree/main/05.%20Predictive%20Analytics%20(Classification))
   - Using the `Scikit-Learn` package to:
        - Pre-process (standardize) the data
        - Split the data into training and testing data using train_test_split
        - Train and evaluate different classification models
        - Find hyperparameters using GridSearchCV
   - Plotting confusion matrices for each classification model
   - Assessing the accuracy of each classification model



## 🔑 Key Learnings
- Making use of data science methodologies in order to define and formulate a real-world business problem
- Using data analysis and data visualisation to load a dataset, clean it, and extract meaningful insights from it
- Interactive dashboard development with Plotly Dash
- Interactive map development using Folium
- Using machine learning to build a predictive model to help a business function more efficiently
- Structuring and building a data-findings report
