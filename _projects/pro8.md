---
name: Data Analysis of Energy Sources - Why US isn’t ready for Clean Energy
image: https://i.pinimg.com/736x/9c/c3/63/9cc3630eb374546457b147737d5e1e66.jpg
description: Analysis of different energy resources and distribution of energy plants in US
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

<div class="right">
{% include elements/button.html link="https://airquality.cpcb.gov.in/AQI_India/" text="Link to Data Source" %}
</div>

Tools used: Python, Alteryx, Qliksense

Energy is the power or capacity to do work. Electric Energy is caused by the movement of electric charges called electrons. The energy resources fall into two main categories, often called renewable and non-renewable energy resources We intend to do a deep analysis of how are we performing in minimizing our usage of non-renewable energy v/s to increased usage and popularity of renewable energy. We later on delve deep into one single region and show(through visualizations) the prospect places to harness renewable energy.

To conduct an analysis of the energy dataset, We first collected data from multiple sources that contained information on the amount of terawatt hours (TWH) consumed. Using the data integration and transformation capabilities of Alteryx, we then successfully merged the individual datasets into a single, comprehensive dataset for analysis.
<img src="../assets/images/fig31.png" alt="image"/>
In the above figure, first we have selected desired columns using the select tool. Next, joining the datasets using multiple join tool. As seen the output is then filtered just to get the USA records only and saved into an output excel file. Once the data has been properly prepared, various analysis techniques can be applied to identify trends and patterns in energy consumption. Common approaches include time series analysis which is shown below. 

<img src="../assets/images/fig32.png" alt="image"/>
<img src="../assets/images/fig29.png" alt="image"/>
<img src="../assets/images/fig30.png" alt="image"/>

In the above workflow created using Alteryx, first the power plant dataset was loaded. After the preprocessing, we have simply used group by tool to find number of plants for each state and technology. The output can be seen as shown above, we see that California has the most number of energy plants and most widely used technology is Solar.

<img src="../assets/images/x3.png" alt="image"/>
The trend of energy resources consumption can be seen as shown above. We clearly see that coal consumption falls down.

<img src="../assets/images/fig33.png" alt="image"/>
<img src="../assets/images/x4.png" alt="image"/>
A lot of powerplants are located near the river areas, as seen Mississipi river has most number of plants.

<img src="../assets/images/x1.png" alt="image"/>
<img src="../assets/images/x2.png" alt="image"/>
The above graph created using QlikSense shows the population density across different regions in the US...with major cities across California, Texas, New York, Chicago etc.
The below graph shows the major power plants across US, So they tend to be were majority of people are. Take the example of Champaign Urbana, where I live... the electricity comes from various sources from Illinois and other neighboring states, so the electricity travels 100s of miles with interconnected transmission lines before reaching us. 
But we simply, cannot build a renewable power plant at any place, there needs to be a proper strategic location to maximize efficiency. 
To build a clean energy future transmitting energy from potential regions to cities will be the biggest challenge



