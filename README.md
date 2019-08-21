<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# How to predict bike usage
*[Laurent Guerguy]*

*[Data Analytics, June 2019, Barcelona]*

## Content
- [Project Description](#project-description)
- [Dataset](#dataset)
- [Results](#results)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
This project looks at trying to predict the usage of bikes in the future as part of a bike sharing system.
This will be achieved by using Time Series predicition with a SARIMA model.


<a name="dataset"></a>

## Dataset
The dataset gives information about the use of the bikesharing system of Washington called Capital Bike for 2011 and 2012. It shows the amount of rides done every day using the bikeshare system, some information about the weather and the type of day (weekday, weekend or holidays).
The data is obtained from the following website: https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset


<a name="results"></a>

## Results

By looking at the data for bike usage as a function of time (or instant) one can see a periodic pattern to the data whereby the usage of bikes is higher during the summer and lower during the winter (see graph below).

![graph_usage_time](../images/graph_usage_time.png "Bike usage as a function of time")


This data can be analyzed using time series. 
In order to check for seasonality in the data the decomposition method is used.
It seems logical to think that the behaviour of people using a bike could be different as a function of the day of the week.

and it gives the following results:

![decomposition_lag_7](../images/decomposition_lag_7.png "Decomposition analysis for lag 7")






<a name="organization"></a>

## Organization
I organized my work using Trello.
I used tools like Jupyter Notebook and Matplotlib Seaborn and Tableau for data visualization

<a name="links"></a>

## Links
Include the links to your repository, slides and trello. Feel free to include any other links associated to your project. 

[Repository](https://github.com/laurent-guerguy/Project-Week-5-Your-Own-Project/tree/master/your-project)  
[Slides](https://slides.com/)  
[Trello](https://trello.com/en)  
