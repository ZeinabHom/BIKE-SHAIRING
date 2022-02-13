# Bike-sharing program in Des Moines!

In this project, bike users is analyzed based on their gender, time/day usages & customer type.

Before starting our analysis, Pandas library of Python is used to reformat "tripduration" column of our database to datetime format. The below code is used in this stage:

	 - bike_data_df["tripduration"] = pd.to_datetime(bike_data_df["tripduration"], unit='s') 

The analysis of tripdurations based on hour and gender shows that the duration of the most trips are less than 20 minutes and male use bicycle more than women.

![1](https://user-images.githubusercontent.com/91231253/153736182-7024b5ac-ea17-407a-8964-f92c9936e984.png)


![2](https://user-images.githubusercontent.com/91231253/153736183-f4bebb11-f66f-4262-b5ce-d0963c58274d.png)

The consumption pattern of bicycle usage based on hours of weekdays shows that the most consumer use bicycle between 8 to 9 am and 5 to 7pm in weekdays except Wednesdays. At weekend, time usage is from 9 am to 7 pm.

![3](https://user-images.githubusercontent.com/91231253/153736186-22143776-8ea5-41a6-9f16-03e106a79ee0.png)

Moreover, female and male have the same consumption patterns but male use the bicycle more than female.

![4](https://user-images.githubusercontent.com/91231253/153736190-3be39cd4-78cd-4e8a-915b-4b745812b76f.png)

The most users are subscribers. they use bicycle on Thursday and Friday more than other days.

![5](https://user-images.githubusercontent.com/91231253/153736193-a758e287-7893-472e-947f-40f5fb08149c.png)

additional analysis shows that the most users of bike are subscriber and also the most usage station is shown in the map.

you can find this analysis at the below link as well.

https://public.tableau.com/app/profile/zeinab.homayounmher/viz/tripduration-ride-gender/Story1?publish=yes
  
