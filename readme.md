# (ord GoBike System Data Exploration)
## by (Ahmed Elberry)


## Dataset

> Ford GoBike System Data(201902-Fordgobike-Tripdata)
The data consists of some demographic information for the users such as age and gender and other information such as the user type (Customer or subscriber) as well as if the member of the bike for all program or not.



## Summary of Findings

> Two factors have been analyzed to check for the effect on the trip duration. these factors are as follows: 1-Age Group: Young users(<20) and senior users(late 70s) are more likely to spend more time on the bike trip 2-Weekday: the longest trip durations have been observed on the weekend; Saturday and Sunday.
> For the subscription status, it has been found that the percentage of Males who are subscribers are higher than that of Females. Furthermore, it has also been found that the age of most of the bike users lies around 30 years old.


## Key Insights for Presentation
Plots that were chosen are:
1-Distribtuion of the user's age as well as the age groups and subscription status as this will allows as to see if there is  arelation between the user's age group and the subscription status
2-Distribution of users with respect tot their gender and trip duation to be able to see if there is a reating between user's gender and the trip duration which might be related to the gender' stamina
3-ploting the bike share column as this will allow us to Track members who are enrolled in the Bike Share for All program and investigate their age, gender, user type as well as their usage pattern facots such as the weekday of usage
> Polishing:
>>Adding clear titles and axes labels. Adjusting the legend as it was ovelapping part of the plot as well as increasing the resoltuon of plots as some of them was blurry. Furthremore, colors have been enhanced for a better comparsion
>>Examples of the code lines used for polishing
>>>plt.legend(bbox_to_anchor=(1, 1), loc='upper left', borderaxespad=0)
>>>plt.figure(dpi=800)
>>>plt.tight_layout()