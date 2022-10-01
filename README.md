# Fordgobike-Tripdata-Project
## by Ajani Ayooluwa
## Fordgobike-Tripdata-System Data Description
In this project, I will be working with the [Ford GoBike System dataset](https://www.google.com/url?q=https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv&sa=D&source=editors&ust=1664451931435624&usg=AOvVaw0JRo4WtCpd1Mt2Oy5dF7ee). The dataset consists of information regarding the individual rides made in a bike-sharing system covering the greater San Francisco Bay area for the month of february in the year 2019.<br>
The dataset features include the duration of the trip, the time at which the trip started, the time at which the trip ended, the name of the station at which the passengers embarked and much more.
## Summary of Findings
1. __Univariate Exploration:__
    - The average duration for all trips been 500 seconds, having above 74% of the trips embarked on by male riders. 
    - The most number of trips were taken on Thursdays while the Weekends have the least number of trips taken as most people prefer to rest at home during the weekends. 
    - The most trips were taken between 8 and 9 in the morning and 5 and 6 in the evening which could be as a result of the work rush and return. 
    - The active riders are between the ages of 18 and 50 years.
    - Most rider do not share the bikes with others during their trips.
    - The Subscriber riders took the most trips.
2. __Bivariate Exploration:__
    - Older people generally prefer shorter trips.
    - Although there are more male riders, it is clear that the other gender riders generally embark on trips of longer durations than their counterparts.
    - Weekend trips take longer compared to trips taken on other days of the week. Most visits to family occur on the weekend and this might be the cause of this.
    - Although there are more subscribers than customers, the customer riders trips take a longer duration than the subscribers.
    - Only the subscriber riders are allowed bike share premium right.
3. __Multivariate Exploration:__
    - For the subsciber riders, the shared trip on average have longer durations than those not shared.
    - The female riders had longer ride durations than the male riders. 
    - For both user types, the other gender riders take longer trips than their counterparts.
    - Due to the very short trip duration we can conclude that the subscriber user type do not travel long distances. 
    - The day of the week with longest trips is sunday for both user types.

## Key Insights for Presentation
- Most trips are a less than 30 minutes long, having a peak at 500 seconds implying that the riders mostly use the bikes to cover relatively short distances in addition to that the female riders had longer trip durations than the male riders. 
- For the both user types, the other gender riders take longer trips than their counterparts.
- A majority of riders are between 18 and 50 years, having the most riders within the ages 27 and 33.
- Most trips were taken on Thursdays and Tuesdays while the Weekends as expected have the least number of trips this maybe be due to fact that most people being spend the weekend resting at home.
- The Busiest hours of the day in the morning are 8am and 9am, while in the evening, the busiest hours are 5pm and 6pm and so should be targeted to boost sales.

# Table of Contents
- `Jupyter Notebooks:` the Jupyter Notebook version of the analysis.
- `HTML Notebooks:` the HTML Notebook version of the Explanatory data analysis.
- `Datasets.7z:` the zipped datasets.
- `Requirements.txt`: the required python libraries.<br>
`Note:` The datasets should be extracted from the zipped dataset folder

# Installation and Configuration
Download Anaconda at https://www.anaconda.com/download/ and install the libraries in the requirement.txt file using PIP

Install Jupyter Notebook by running the following command:
```
conda install jupyter notebook
```
or
```
pip install jupyter notebook
```

Then launch the Jupyter Notebook to view the .ipynb file.
