---
layout: post
title: "TheRailMap v1.3: Small Changes, Big Features!"
date: 2021-7-10
---

This week/month’s release is a good example is what my development schedule for TRM is becoming. Most large changes/features are already implemented, and so these updates tend to be lots of little quality-of-life changes. That doesn’t mean they aren’t exciting though, so here are some of the new features in TRM v1.3!

### **Amtrak Only View**

![](https://cdn-images-1.medium.com/max/6488/1*XvEH_awrK9GQEjgK3x8xAQ.png)

Previously, some users found it hard to actually find the train routes they were traveling on. Now, you can see Amtrak’s routes only, with the press of a button! We also added more station information (like a link to the transitdocs page for the station.)

![Direct Link to transitdocs](https://cdn-images-1.medium.com/max/5000/1*wBgYfz3H3m0DN_MxPm24kg.jpeg)_Direct Link to transitdocs_

### Direct Linking and Database

![](https://cdn-images-1.medium.com/max/2000/1*i0Y3xpATX0RBDUYrH5gePw.png)

You can now also directly link to a specific location on the map, using url parameters! For example, let’s say I wanted to share this crossing in Vancouver, Canada.

I can just copy the link given in the popup, and share it with a friend. When the friend clicks the link, the map will open centered around this specific crossing.

This feature is enabled for American and Canadian crossings and bridges. Sadly, we are unable to bring this to European features, as they don’t have individual popups (however this may change in the future.)

Direct links also come into play when looking at out new “database”. Simply paste in a crossing or bridge ID, select the correct country, and reload the page. This allows users to find features by ID, when they don’t know the exact location, or would like more information about the specific crossing. While the database is currently a google sheet, we are hoping to move to a custom website sooner, rather then later.

### Virtual Railfan

![VRF Camera Locations](https://cdn-images-1.medium.com/max/6488/1*KeI079QJp2wBCweUA8rOUA.png)_VRF Camera Locations_

For those who are fans of Virtual Railfan, you can now see all camera locations presented on a map! YouTube links will be added soon, along with more info about each camera.

You can visit this map [here](https://www.therailmap.com/vrf).

### Some Smaller Changes

- Added a legend in the “About” popup to help understand the map’s color scheme.

- European rail tunnels are now represented on the map.

- All previously separated are now on the main page.

- Moved /europe to ?redirect=europe

- Moved site hosting to GitHub pages, for a smoother integration with GitHub.

- Updated the site font to SF

- Moved back to using Browserify and Node.js

Thanks again for all the support, and as always, please leave any suggestions or issues on the GitHub repo [here](https://github.com/EliotHertenstein/railmap).
