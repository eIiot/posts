---
layout: post
title: "The Rail Map v2!"
date: 2022-4-4
image: "/assets/images/2022-4-4-therailmap-v2/v2-full.png"
---

![A screenshot of The Rail Map v2]({{'/assets/images/2022-4-4-therailmap-v2/v2-full.png' | relative_url}})
It's that time again!

While this was originally supposed to be a post about bringing The Rail Map to [Vite](vitejs.dev/), I got a little in over by head. I'm happy to announce that the next version of The Rail Map is v2-Next!

Yep, so I decided to port the entirety of The Rail Map over to Next.js, including (but not limited to) [/amtrak](https://therailmap.com/amtrak), [/vrf](https://therailmap.com/vrf), [/data](https://therailmap.com/data), and more. Along the way, I completely reworked the preview experience, and made it easier to add more cool content in the future. While we'll get into that later, let's take a look at what's new...

### Completely New Feature Sidebar

![The revamped sidebar]({{'/assets/images/2022-4-4-therailmap-v2/sidebar-default.png' | relative_url}})

The sidebar has been fully redesigned to display more information, and also look a whole lot nicer! Trains have a two tab system, with the default information on one tab, and the stations on the other (That's right, there's now station support). For some values (mainly time related ones), the rings are dynamic, meaning the color changes depending on how early or late they are (and let's face it, Amtrak isn't known for being early).

![Stations displayed on the sidebar]({{'/assets/images/2022-4-4-therailmap-v2/sidebar-train-stations.png' | relative_url}})

As for the stations, each stop has it's own box with a color coded ring. You can see the stations coming up, and those behind, all with estimates from Amtrak.

![A railroad crossing displayed on the sidebar]({{'/assets/images/2022-4-4-therailmap-v2/sidebar-crossing.png' | relative_url}})

Crossings and bridges are also back with the new design, with lots more information (that's formatted nicely). The railroad, milepost, crossing type, quiet zone status, and even the emergency telephone number are all easy to access and view. Bridges are also supported nicely, with much of the same information available. This data is available throughout the US and Canada, with more North American countries coming soon*ish*. (Disclaimer: Please don't try to use The Rail Map for emergency services, instead call the phone number located on the ground near the crossing).

### Mobile View

![A train crossing displayed on the mobile 'sidebar']({{'/assets/images/2022-4-4-therailmap-v2/train-mobile.png' | relative_url}})

With the new sidebar comes a brand new mobile view, better supported than ever for touch devices. Links become buttons, scrolling is effortless, and everything closes with just a tap on the top bar. This works with all features that work on desktop, so you'll never be left wondering about a crossing or train.

### Live Trains & New [/amtrak](https://therailmap.com/amtrak) Page

![The /amtrak page]({{'/assets/images/2022-4-4-therailmap-v2/amtrak-page.png' | relative_url}})

Although it was never really announced, the has supported live tracking of Amtrak via [amtrak.js](https://github.com/piemadd/amtrak) since [v1.4](https://github.com/eIiot/railmap/releases/tag/v1.4). This release includes the major updates to train tracking mentioned above, along with more information about each station! You can see which trains are on their way, and when. Clicking on a train in the side panel will also bring up the relevant train information, and also move the map to the current train location.

![An Amtrak station displayed on the side panel]({{'/assets/images/2022-4-4-therailmap-v2/amtrak-station-information.png' | relative_url}})

### Visit the site!

All these brand new features are now live at [https://www.therailmap.com/](https://www.therailmap.com/).

### Thank You!

And finally, a thanks to everyone who's used the map! When I originally started this project 3 years ago (by manually plotting every railroad crossing from Emeryville to Chicago), I never thought anyone else would find it, nevertheless use it. It's so cool to see people find their own uses for some dumb thing I made when I didn't know anything about programming. (While I still don't know anything about programming, at least I can say I know Next.js 😎)

For any issues, bugs, or suggestions, you can find my contact info on my [website](https://eliothertenstein.com) (which was not built with Next.js, sadly). As always, the project is open source [here](https://github.com/eIiot/railmap/). Please feel free to give me tips on what I'm doing wrong, because I'm sure there are a lot of things.

Thanks again,

Eliot
