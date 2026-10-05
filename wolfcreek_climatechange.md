---
layout: page
title: "Temperature changes on Wolf Creek Pass, Mineral County, CO"
permalink: /wolfcreek_climate/
---

### How is climate change impacting Mineral County, CO, specifically Wolf Creek?    
* The region is receiving less snowfall and snow is melting earlier. Median SWE (snow water equivalent) at the Wolf Creek Summit since 1990 is 35.1" - peak SWE for the 2025-2026 winter was 15.2". SWE peaked on March 6, over a month earlier than usual. <https://snowpack.report/resort/wolf-creek/history>
* More extreme storms are occurring in the region - while snowpack was historically low in 2025, Southwestern Colorado saw extreme rainfall in October 2025. The Wolf Creek Pass climate station recorded over 10 inches of rain during one week in October. <https://www.cpr.org/2025/12/21/2025-weather-one-of-colorados-warmest-years/>
* Metal concentrations are increasing in high-elevation streams in Mineral County - warming temperatures are leading to melting permafrost, in turn driving increases in weathering and acid rock drainage. <https://aspenjournalism.org/climate-change-causing-increase-in-metals-concentrations-in-streams-study-finds/>

### Study site: Wolf Creek Pass, Mineral County, CO  
<embed type="text/html" src="{{ '/img/wolfcreek_map.html' | relative_url }}" width="800" height="800">    
Wolf Creek Pass (summit denoted by white triangle) is a high mountain pass in the San Juan Mountains of Colorado, located in Mineral County (blue border). It is named for Wolf Creek, a stream in Mineral County which starts near the top of the pass and flows down the Western side of the pass where it joins with the West Fork San Juan River. The region has a subarctic climate and receives precipitation year-round. Average annual snowfall is 391.1 inches, making it one of the snowiest areas in Colorado.   

### Yearly average temperature
<embed type="text/html" src="{{ '/img/ann_temp_wolfcreek_plot.html' | relative_url }}" width="800" height="300">
The above graph shows annual average temperatures (in ºC) over time on the Wolf Creek Pass Summit. The maximum mean annual temperature recorded was 1.169ºC (in 2020), and the minimum mean annual temperature recorded was -4.129ºC (in 1986). Note that monitoring began in 1986, so it is possible that only winter temperatures were recorded that year. The next-lowest mean annual temperature was -3.356ºC, recorded in 1987. The above graph is interactive - you can check out the average annual temperature in other years, too. 

### So how much is the temperature changing over time? 
To quantify how much the temperature has changed over the past 40 years on Wolf Creek Pass, we used linear OLS (ordinary least squares) regression to fit a trendline to the data and determine how quickly temperatures are rising on average. It is worth noting that linear OLS regression assumes the following: 
* Random error: all variation (apart from that variation driven by what we are measuring, in this case, climate change) is random
* Normally distributed data: the data are normally distributed, and are not skewed in any way
* Linearity: temperature is changing at a constant rate over time
* Stationarity: variation in temperature caused by factors apart from climate change behaves the same over time

We should note that our data do not perfectly meet these assumptions - variation is driven by other non-random change (such as La Niña/El Niño climate cycles), the data are slightly skewed toward cooler temperatures, temperature is not changing at a constant rate over time (warming seems to have accelerated in the past 20 years), and there is more variation between some years than others.   

With that being said, we probably want to be careful with how we apply this analysis and in what context. If we were to be publishing this, it might be a good idea to find an analysis that is a slightly better fit for our data. However, linear OLS regression fits our data well enough and is certainly adequate for a preliminary analysis. 

<img
  src="/img/wolfcreek_temperature_trend.png"
  alt="wolfcreek temperature trend"
  width="75%">
#### Wolf Creek Pass Summit temperatures have been rising over the past 40 years, and continue to rise
The above figure shows the mean annual temperature over time on the Wolf Creek Pass Summit with a trendline fit via linear OLS regression. The slope of the trendline is 0.10886904, indicating that **temperatures on Wolf Creek Pass are rising by roughly 0.0109ºC per year.** This is greater than the global average yearly temperature increase of ~0.03ºC. 











