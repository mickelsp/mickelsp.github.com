---
name: india-air-quality
layout: post
title: "Coal and Air Quality in India"
data: 2015-06-01
author: Pascal Mickelson
category : coal
tags : [climate change, air quality, carbon, sources, coal, india]
---
{% include JB/setup %}

Given how frequently we read about China's poor air quality in the news, it rather surprises me that only one city in China--and it's not Beijing--falls in the 50-worst cities for air pollution. Instead, India has more cities on this unfortunate list than any other country. New Delhi--the largest of these cities--was ["featured" in a New York Times article][nytimesarticle] about the negative consequences of poor air quality, and that was when I learned that so many Indian cities are choked with air pollution.

To visualize the 50-worst cities in terms of air quality, I mapped them using [some data from the World Health Organization][WHOdata]:

<div align="center">
<img src="/images/map_top50cities_airpollution.png" alt="Map showing 50-worst cities for air pollution with particle size below 10 micrometers" width="400" height="200"><br>
<small>Map showing 50-worst cities for air pollution with particle size below 10 micrometers (<a href="http://www.epa.gov/airtrends/aqtrnd95/pm10.html">PM10 standard</a>). Larger circles represent more heavily polluted cities. Peshawar, Pakistan has the highest PM10 levels in the world. Data from the <a href="http://www.who.int/phe/health_topics/outdoorair/databases/cities-2011/en/">World Health Organization Database of Outdoor Pollution</a>.</small>
</div><br>

First, it's striking that not a single city outside of Asia and Africa--and only one city outside of Asia--falls within the 50 cities with the worst air quality. From this, it is clear that the developing world has an outsized share of air pollution--more on this in a moment. Second, I wonder how much the sources of air pollution contribute to poor air quality compared to the geography which may trap air pollution in place. The following is only speculation, as I am not familiar with the atmospheric science, but it wouldn't surprise me if the Himalayas make it difficult for polluted air to be carried away from its source.

There are multiple reasons why the developing world has a large share of global air pollution and, unfortunately, these make for a bleak outlook on improving air quality and controlling global greenhouse-gas emissions. One is that regulations are frequently more relaxed than in developed countries, making it easier for industries to pollute the air without consequence. Partly because of this reduced regulation, the developed world has essentially exported a significant amout of pollution to third world countries, an idea Jared Diamond discusses [in his book, "Collapse"][collapseBook]. But in India, the natural abundance of coal and the desire to improve its citizens' standard of living [leads to the uncomfortable conclusion][carbonInIndia] that coal is going to be a key part of India's energy portfolio for a long time to come.

On the positive side, solar energy in India is quite feasible given its [high levels of solar irradiance][indiaIrradiance], and with proper investment and manufacturing prowess (perhaps with help from China), solar power could become a more significant part of India's energy mix. For the Indian people, however, it is a sad reality that, even with increased solar energy, still-heavy reliance on coal means they will face the detrimental effects of air quality for a long time to come.

<div align="left">
<small>Are you interested in the data and the code used to generate the map above? Check out <a href="https://github.com/mickelsp/PollutedCities">my Github repository</a> for the gory details.</small>
</div><br>

[nytimesarticle]: http://nyti.ms/1FRG0oY
[WHOdata]: http://www.who.int/phe/health_topics/outdoorair/databases/cities-2011/en/
[ghginventory]: http://www.epa.gov/climatechange/ghgemissions/usinventoryreport.html
[collapseBook]: http://amzn.com/0143117009
[carbonInIndia]: http://www.theguardian.com/news/2015/may/27/why-india-is-captured-by-carbon
[solarIndia]: http://www.reuters.com/article/2015/01/02/india-solar-idUSL3N0UG13H20150102
[indiaIrradiance]: http://www.nrel.gov/international/images/india_dni_annual.jpg