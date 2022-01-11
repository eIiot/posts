---
layout: post
title:  "Resurrecting Weather Timeline"
date:   2022-01-09
categories: JS Weather
---

## Intro

It's been over three years since [Weather Timeline was bought by the owners of MyRadar](https://www.androidpolice.com/2018/11/21/sam-rustons-weather-timeline-new-developer-listed-play-store/), a company who's weather prediction algorithms are some of the worst in the business. While there are many competitors to Weather Timeline, there's still no weather app that manages to replicate it's style, usability, and feature-set. However, there's still hope - ACME AtronOmatic's first (and final) update moved Weather Timeline to their own weather APIs, meaning it's possible to host our own "fake" weather api, and use OpenWeatherMap data. Let's patch!

## Which API?

While there are a surplus of weather APIs to choose from, this tutorial uses [OpenWeatherMap](https://openweathermap.org) because (1) it's free and (2) the syntax is easy enough to understand. If you plan on using a different API, note that the code below won't work unless you rename many (or all) elements.

## Creating the Backend

Once you've [generated an OpenWeatherMap API Key](https://home.openweathermap.org/api_keys), clone the template repo using 