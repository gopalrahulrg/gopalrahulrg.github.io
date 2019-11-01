---
title: "Bangalore: The Battle of Neighborhoods"
date: 2019-11-01
tags: [data science, machine learning, unsupervised learning, clustering] 
header:
excerpt: "Clustering, Machine Learning, Data Science"
---

<img src="{{ site.url }}{{ site.baseurl }}/_resources/cnbr/Bangalore_Neighborhoods_Mapping.JPG">

## Restaurant Densities in Bangalore

</html>

<font size="5"><h3>Background</h3></font>

<font size="4"><div style="text-align: justify"><p> Bangalore is the capital of the Indian state of Karnataka with a population of over <b>10 million</b> (density of over <b>4000 per sq. km</b>) [1][2], making it the third most populous city in India.</p>
  
<div style="text-align: justify"><p>As a result of the high population density, owners of shops end up sharing places. From the point of view of investors, they would prefer to set up businesses in neighborhoods where the competition is less intense.
  
<div style="text-align: justify"><p>For both residents and travelers, exploring various neighborhoods and venues is a good way to relax during weekends and holidays. The diversity of the cuisine available is reflective of the social and economic diversity of Bangalore. Bangalore has a wide and varied mix of restaurant types and cuisines and Bangaloreans deem eating out as an intrinsic part of their culture. Roadside vendors, South Indian, North Indian, Chinese and Western fast food are all very popular in the city [1].</p></div>

<div style="text-align: justify"><p>Considering the above points, creating a map of Bangalore with districts grouped together with the help of clustering according to the venue, specifically restaurant density would be helpful.</p>

<font size="5"><h3>Data Description</h3></font>

<font size="4"><p>The data needed to solve the problem includes</p>

<ul>
  <li>A list of neighborhoods in Bangalore, the capital city of the state of Karnataka in India which defines the scope of the project </li>
  <li>Latitude and longitude coordinates of those neighborhoods to get the venue data and for mapping and visualization;</li>
  <li>And finally, venue data, particularly data related to venues to perform clustering on the neighborhoods.</li>
</ul>

<p>Wikipedia contains a list of neighborhoods in Banaglore (with a total of <b>128</b>) [3]. Web scraping techniques were used to extract the data from Wikipedia. Foursquare API was used to get the venue data for those neighborhoods.</p>

Unfortunately, public data related to demographic and social parameters for all the neighborhoods in the city of Bangalore was not readily available and hence could not be used to refine the study further.

<font size="5"><h3>Methodology</h3></font>







 