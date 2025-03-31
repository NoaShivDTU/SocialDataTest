---
layout: post
title:  "How Drug and Alcohol Offenses Intersect with Crimes Against Families and Children"
#date:   2025-03-31 11:01:26 +0100
categories: jekyll update
---


<p>
This analysis explores the geographical and time-pattern overlap between drug-related offences, alcohol-related incidents, and crimes against families and children in recent years. The analysis uses data from police reports in the San Francisco area ( <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783/about_data">Police Department Incident Reports: 2018 to Present</a> ), to create data visualization and draw parallels in the specific crimes. The years under investigation are from 2018 to 2024. The main objective of this article is to find tendencies on when and where these crimes happen.
</p>


The polar bar chart below in <a href="#fig1">Figure 1</a> helps identify how patterns during hours of the day, to get an understanding of when these crimes happen.

<figure>
  <img src="/SocialData_assignment2/plots/polar_subplots.png" width="100%" height="300" alt="Polar Subplots" style="border:none;">
  <figcaption style="text-align: center; font-style: italic; margin-top: 10px;"><strong>Figure 1:</strong>
Polar bar chart of each crime type for each hour of the day.
  </figcaption>
</figure>

<p>
The chart shows that drug and narcotic-related crimes mostly occur during the afternoon and follow a somewhat similar pattern compared to the other two crime types. Reports of offences against the family and children are almost evenly distributed throughout the day, with noticeable spikes around noon and midnight. These same spikes are also observed for drunkenness, although many of the reported cases of drunkenness primarily occur during the middle of the day and afternoon. These spikes in drunkenness and offences against the family and children occurring during the same time of day could indicate that a correlation between those two could be investigated.  According to the <a href="https://bjs.ojp.gov/content/pub/pdf/ac.pdf">U.S. Department of Justice</a> 3/4 of domestic violence happens when the offender is influenced by drinking, describing a tendency that violence in homes is heavily overlapping with drunkenness. 
</p>


The animated map in <a href="#fig2">Figure 2</a> displays the location of each reported crime within the categories of drug and alcohol offences and offences against family and children, which portrays where these crimes happen.

<figure id="fig2">
 {% include crime_animation_map.html %}
  <figcaption style="text-align: center; font-style: italic; margin-top: 10px;">
   <strong>Figure 2:</strong> Animated map of San Francisco showing the location of each reported crime within the categories from 2018 to 2024.
  </figcaption>
</figure>

<p>
 The map shows no systematic geographical pattern changes over time. Each year shows a high density of reported crimes in one area, namely around the Mission district (the top right of the mainland) and a more scattered pattern throughout the rest of the city and in the suburbs. The pattern displayed on the map overlaps with the analysis performed by <a href="https://www.wesanfrancisco.org/data/2023-neighborhood-crime">WE San Fransisco</a>, where the dense area on the map also is reported to be some of the most reports of violence and drug crimes. 
</p>

<p>
This map indicates that the crimes within the three categories often occur within the same area, but since all incidents are reported by mapping to the nearest intersect, as described in <a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-2018-to-Present/wg3w-h783/about_data">Police Department Incident Reports: 2018 to Present</a>, the exact location of the crimes are not shown. 
</p>

<p>
To further investigate how much these crimes overlap in terms of location, the bar chart below in <a href="#fig3">Figure 3</a> shows neighbourhoods where there is an overlap of these crime occurrences.
<p>

<figure id="fig3">
 {% include bokeh_overlay_plot.html %}
  <figcaption style="text-align: center; font-style: italic; margin-top: 10px;">
    <strong>Figure 3:</strong> Bar chart displaying the top 10 locations where drug and alcohol offences and offences against family and children overlap.
  </figcaption>
</figure>

<p>
From this it can be seen that a few locations have persistently high incident counts across the years, most significant the locations: 

- (37.78259,-122.41569) and (37.78352,-122.41588), which are the intersects between Hyde St. and Eddy St. and between Turk St. and Hyde St. These intersect are described as hot spots for open sales of illegal drugs, shootings and crimes in general (<a href="https://beyondchron.org/san-francisco-must-stop-drugs-and-violence-at-turk-and-hyde/">increase</a>)

- (37.77999,-122.41349), which is the UN Skate Plaza described as an area of  <a href="https://abc7news.com/sf-un-plaza-skate-park-drugs-homeless/14373671/">"chaos with people overdosing and illegal activity throughout the plaza"</a>. 
</p>

<p>
Many of the locations have a spike in counts in 2020, which could be related to COVID-19, where families were forced to stay home and family crime worldwide saw an <a href="https://www.sciencedirect.com/science/article/pii/S2665910720300384">increase</a>. In 2024 there is a significant decrease in the overlap of the crime reports, this could be due to several things, but most importantly according to <a href="https://www.sfchronicle.com/crime/article/san-francisco-2024-data-20020378.php">San Fransisco Chronicle</a> crime has dropped to a two-decade low in 2024.
</p>

<p>
Overall there seems to be a geographical and time-pattern overlap between drug-related offences, alcohol-related incidents, and crimes against families and children, however, to draw any socio-economic conclusions or recommendations on bringing down these crime types, further analysis is necessary. 
</p>
