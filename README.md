# (Dataset Exploration Title)
## by (your name here)


## Dataset

> The "New York Bike Sharing" dataset provides information on bike sharing usage in New York. The purpose of the dataset is to investigate the factors that drive participation in the bike sharing system. The dataset includes information on various attributes such as duration of the trip, start and end time, start and end station names, user type, member gender, bike share type, day of the trip, age, start time hour, and age group. With a total of 183412 observations and 16 variables, the data provides insights into the usage patterns of the bike sharing system. By analyzing variables such as user type, member gender, and age group, one can determine which demographic segments are most likely to participate in the bike sharing system. The data also provides information on trip duration, start and end time, and day of the week, which can be used to analyze usage patterns and identify peak usage times.

The following data wrangling process were performed to prepare the data for analysis:

- Drop unwanted columns

- Convert start_time and end_time to datetime type

- Extract days from start_time column

- Calculate user age by subtracting member_birth_year from 2023

- Bin user age into groups: Gen Z, Millennials, Older Generation.

## Summary of Findings

> The findings of the investigation showed that there were outlier points in the age distribution which were dropped. It was observed that millennials were the highest users of the bike sharing service, followed by the Gen Z and older generations. Usage was higher on weekdays compared to weekends. Subscribers used the system more than customers and males used the system more than other genders. The findings suggest that younger generations, specifically millennial males, are more receptive to the bike sharing system, and this trend is even more pronounced among subscribers. The relationship between user type and age and member gender was found to be weak, but the relationship between age and user openness to bike sharing was strong across all genders, with age being a stronger predictor of user openness than user type or member gender. The Market St at 10th St station was the busiest start station.
 Yes, The findings will be presented in the explanatory presentation.

## Key Insights for Presentation

> For the presentation, I focused more on how other factors influence the bike sharing system. I started off by introducing a distribution that shows the peak hours for the bike sharing system, followed by the distribution of the number of users open to the system. Then, I introduced a plot showing the distribution of users open to the bike sharing service over different User type. I also looked into the relationship between Age, Gender and how they influence the bike sharing system.