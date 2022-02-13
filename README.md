# Bike-sharing program in Des Moines!

In this project, bike users is analyzed based on their gender, time usages, weekday usage rate & customer type.

Before starting our analysis, Pandas library of Python is used to reformat "tripduration" column of our database to datetime format. The below code is used in this stage:

	 - bike_data_df["tripduration"] = pd.to_datetime(bike_data_df["tripduration"], unit='s') 
The analysis of tripdurations based on hour and gender shows that the duration of the most trips are less than 20 minutes and male use bicycle more than women.



![C:\Data Analytics\GitHob Repository\BIKE-SHAIRING\1.png]

The consumption pattern of bicycle usage based on hours of weekdays shows that the most consumer use bicycle between 8 to 9 am and 5 to 7pm in weekdays except Wednesdays. At weekend, time usage is from 9 am to 7 pm.
picture 3

Moreover, female and male have the same consumption patterns but male use the bicycle more than female.
picture 4

The most users are subscribers. they use bicycle on Thursday and Friday more than other days.

https://public.tableau.com/app/profile/zeinab.homayounmher/viz/tripduration-ride-gender/Story1?publish=yes
  
