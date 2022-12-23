---
name: CHICAGO VEHICLE CRASH ANALYSIS | Final Project Part 3.1
image: https://user-images.githubusercontent.com/98044494/205228244-231c2043-aa79-4f71-8f1f-6252b16057a6.png
description: This is our Final Project consisting of 3 dashboards.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---


# CHICAGO VEHICLE CRASH ANALYSIS
------------------------------------------------------------------------------------

#### Project done by Akshant Churi, Samruddhi Choudhari and Smit Malik

------------------------------------------------------------------------------------

### Link to Python file: 
------------------------------------------------------------------------------------
<div class="right">
{% include elements/button.html link="https://github.com/achuri2/achuri2.github.io/blob/main/main%20analysis.ipynb" text="Python Jupyter Notebook" %}
</div>

### BACKGROUND

The Chicago city vehicle crash count is on the rise as always and it is really important to analyse the pain points and see what is going wrong. So, this project helps the users as well as the chicago government to see various factors like red light, speed violations, weather, car models and other factors affecting crashes in the city.The project has 3 interactive dashboards that helps the user analyze these aspects. The dashboard is also easy to use and has appropriate asthetic choices that enhance it even further.

### DASHBOARD 1: Drag and Select Bars on 1st Area Plot to Interact With the rest 3 charts

This dashboard gives the user an idea on how the chicago crashes vary with the age, gender and time of the year. This dashboard has 4 interactive charts in it:
1. Area chart - Age of people involved in crash
2. Pie chart - Male Vs Female involved in crash
3. Chicago basemap - Highlights red light, speed violations, crashes in the city of Chicago
4. Line Chart - Shows monthly change in the number fo crashes

Chart 1 here is interactive and the user can easily select any range of age that the user is interested in and simultaneously the other three charts will get updated. Based on chart 1 we can see that crashes are the maximum for ages 25-30 and after selecting this particular area we can see that crashes were more for male than female with slightly more numbers. Here in chart 3 we can see that most of the crashes are associated in downtown region and some of them are spread out in south region as well. It also has a lot of red light and speed violations. In chart 4 we can see that crashes are less in Jan, Feb, March, December and maximum in the month of october. The main reason behind this can be that end and start of the year there is a lot of snow due to which people do not travel a lot with their vehicles. And october being holiday season people use a lot of vehicles leading to more crashes. 

The chart 4 line chart uses categorical data instaed of bar chart as we wanted to show trend over the year where the crashes start rising mid year, peak in oct and then drop during winters.

<vegachart schema-url="{{ site.baseurl }}/assets/json/file1.json" style="width: 100%"></vegachart>

### DASHBOARD 2: Drag and Select Bars on 1st Area Plot to Interact with the rest 2 charts

This dashboard gives the user an idea on how the chicago crashes vary with the age, gender and time of the year. This dashboard has 4 interactive charts in it:
1. Bar chart - Types of cars models involved in crashes
2. Line chart - Crash trend over years 2016-2022 
3. Bar Chart - Shows the amount of damange done(in $) (501-1500$) and (over 1500$)

This is an interactive dashboard where once the user selects the car models he is interested in the rest 2 charts get updated. Based on the charts we can see that Camry model car had the maximum number of crashes followed by accord. Maybe these are the cars that people own the most and affordable ones. After selecting camry in the furst plot we can see that it had maximum accidents in year 2017 and then it dropped during the covid years since there were less people out on roads driving. And based on chart 3 we can see that most of the damage was over 1500$ which means there were serious damage done to the car. This can be beneficial in understanding the areas these accidents happended the most while if the car models were not safe enough to drive.

The chart 2 line chart uses years 2016-2022 instead of bar chart to show trend of crashes in that time.

<vegachart schema-url="{{ site.baseurl }}/assets/json/file2.json" style="width: 100%"></vegachart>

### DASHBOARD 3: Drag and Select Bars on 1st bar plot to Interact With the rest 3 bar charts

This dashboard gives the user an idea on how the chicago crashes vary with the age, gender and time of the year. This dashboard has 4 interactive charts in it:
1. Bar Chart - Monthly crash count
2. Bar Chart - Weather crash count
3. Bar Chart - Lightening crash count
4. Bar Chart - Roadway crash count

This dashboard has 4 charts that are linked to each other. They help the user understand the monthly crash count along with the weather, lightening and roadway conditions. Based on chart 1 we can see that month of september, october had maximum crashes and followed by winter season having the least. In claer weather conditions we have had the maximum crashes while in daylight lightening condition. Also when the road was dry the accidents happened the most. Hence, we can see that weather plays an important role in crashes across Chicago.



<vegachart schema-url="{{ site.baseurl }}/assets/json/file3.json" style="width: 100%"></vegachart>
------------------------------------------------------------------------------------

###Contextual viz
<vegachart schema-url="{{ site.baseurl }}/assets/json/file4.json" style="width: 100%"></vegachart>

#### CONTEXTUAL VISUALIZATION
The 2 contextual datasets choosen are the red light and speed violations. For this project we have created our own contextual visualizations. There are 2 charts made. First one is in dashboard 1 which shows the chicago base map along with the two violations. The second line charts tells us the daily red and speed violations done in the city from monday to sunday. Saturday and sunday were the days with maximum violations. Maybe these were holidays and people went out more often.

------------------------------------------------------------------------------------

### CONCLUSION
To conclude we would like to say that this project can be of real help to the Chicago city. Lots of people everyday loose their lives due to these crashes. We can see from the dashboards that people of age 25-30 are more liekly to be involved in crashes than others. As this is the youth and more likely to be not following rules and getting involved in crashes. We also saw that mostly red light violations and speed violations were done in the chicago downtown area while most accidents happening in the month of sept, oct and least in the winter months were there is a lot of snow in chicago. Most likely people do not go out and would eventually lead to lesser crashes.

------------------------------------------------------------------------------------
### CITATION
1. crashes dataset https://data.cityofchicago.org/Transportation/Traffic-Crashes-Crashes/85ca-t3if

2. vehicle dataset
https://data.cityofchicago.org/Transportation/Traffic-Crashes-Vehicles/68nd-jvt3

3. people dataset
https://data.cityofchicago.org/Transportation/Traffic-Crashes-People/u6pd-qa9d

CONTEXTUAL DATASET LINK

4. red light camera violation
https://data.cityofchicago.org/Transportation/Red-Light-Camera-Violations/spqx-js37

5. speed camera violation
https://data.cityofchicago.org/Transportation/Speed-Camera-Violations/hhkd-xvj4



<div class="right">
{% include elements/button.html link="https://github.com/achuri2/achuri2.github.io/tree/main/project%20data" text="link to data" %}
</div>

