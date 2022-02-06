---
layout: post
title:  "The US Railroad Map has a New Home!"
date:   2021-5-23
categories: TheRailMap
---
![](https://miro.medium.com/max/1400/1*LLBF2zyPd9zUKt5b0CHtuQ.png)

Over these past few months, I’ve been working to move the Us Rail Map from Manual Data (Satellites) over to a more reliable source (FRA and OpenRailwayMap). Well, I’ve finally figured out a way to import this data into MapBox, and so I present, [US Rail Map 1.0!](http://map.eliothertenstein.com)

Some of the biggest changes to this release come in the design. We’ve moved from MapHub.net (A smaller online GIS made for non-power users) to MapBox.com, a larger map creator with a better API, and support for larger datasets. What this has allowed us to do is directly import railroad data from HIFLD Open Data, the US repository for “National foundation-level geospatial data within the open public domain”. This way, we’re sure that nothing is being missed.

![](https://cdn-images-1.medium.com/max/2752/1*RWdkzkKuedDGnhDHyjQkwA.png)

Working with MapBox also allowed us to create custom designs for each railroad marker, depending on the data provided by the Railroads, and the Crossings. So now, you can see information about each element, right above the element!

![Street Labels along with Line Labels are included on the Map](https://cdn-images-1.medium.com/max/2402/1*TblGt9TMwq38kiMrnkevCg.png)*Street Labels along with Line Labels are included on the Map*

Finally, I would like to say a quick thanks to [Arun Ganesh](https://medium.com/u/1c969b196654), who created the basemap and the more stylistic elements of the map. I took a lot of inspiration from [his map](https://api.mapbox.com/styles/v1/planemad/ck7p3wxmp0q571imu99elwqs1.html?fresh=true&title=view&access_token=pk.eyJ1IjoicGxhbmVtYWQiLCJhIjoiemdYSVVLRSJ9.g3lbg_eN0kztmsfIPxa9MQ#10.29/19.0979/73.1439/80/82), and I suggest you check that out if you’re looking for a cleaner experience!

You can access the map at [map.eliothertenstein.com](http://map.eliothertenstein.com)!