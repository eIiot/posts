---
layout: post
title:  "Rail Map: New Railroads!"
date:   2021-3-8
categories: TheRailMap
---
It’s been a while :)

I’ve been pretty busy the past few months, but the rail map has slowly continued to fill up :)

This past week, I’ve worked on adding G&W’s [120 Railroads](https://en.wikipedia.org/wiki/List_of_railroads_owned_by_Genesee_%26_Wyoming#Other) to the map. Although most railroads have data publicly available through Wikipedia or [HIFLD open data](https://hifld-geoplatform.opendata.arcgis.com/), there was not any KML data available for G&W. The only map source I had was an [embedded google map](https://gwrr.com/about_us/maps#north-america) on their website.

![G&W’s Map](https://cdn-images-1.medium.com/max/2000/1*JJ4FaGvNNT1q2MRwyWcj9Q.png)*G&W’s Map*

My first plan of action was trying to find a way to get the KML source for the embed. I tried looking through the Inspect code for the website, but was only able to find an api link, which was no help. However, there was one thing that I didn’t try: checking the network.

In most browsers, you are able to see what webpages the website that you are on queries. By looking through this data, I was able to find a JSON file, with the coordinate data for each of the 120 railroads. However, these were all separate files. What that required, was manually typing in the address, followed by the mark for each railroad, and then downloading the associated JSON file. This took about an hour, and while I could have automated it somehow, it was easier just to brute-force it.

![The network tab for the G&W website](https://cdn-images-1.medium.com/max/3774/1*8MDm7e9R_bqIZys6MVFtIw.png)*The network tab for the G&W website*

Once I had the files, it was time to sort them. Due to MapHub’s limits on data, you are only allowed 50k points on a single map, so my map of the US is divided into four regions. Since the railroads that I was importing were not major US railroads, they had to be sorted into each map, before importing. This consisted of much of the same work; Google the name of the railroad, see where it was located, put into the correct folder. This process took the longest out of the three, since there was no possible way to automate it. After 5 or so hours, every small file was in the correct folder.

![The South folder](https://cdn-images-1.medium.com/max/2542/1*l_Pvb1yfU8WwHf2O-GIHIg.png)*The South folder*

The last step was just to import the data into MapHub. After doing a batch rename of the files using command prompt, I was ready to drag them over. This process was very simple. Since the files were so small, the processing time was almost nonexistent, and I just had to drag each one over to the MapHub window. And although the naming is still a little messed up, the process is finished!

You can view the final product at [map.eliothertenstein.com](http://map.eliothertenstein.com).

And as a final note, I just want to say thanks for all the amazing support, on my [YouTube](https://www.youtube.com/channel/UCMgxeBL7wpBOjhVHBluvTrQ), [Patreon](http://patreon.com/eliothertenstein), and just on the website in general. I absolutely love this community, and I hope to work more with all of you in the future!

To request a location, please visit my P[atreon](http://patreon.com/eliothertenstein).