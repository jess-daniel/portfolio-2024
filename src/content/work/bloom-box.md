---
title: Country Events
publishDate: 2024-01-23 00:00:00
img: /assets/country_events.png
img_alt: A screenshot of the homepage of the Country Events web app.
description: |
  The Country Events web app is a React app using React Query, Tailwind, and Serverless functions that makes API reuests for country data and event data from Eventbrite.
tags:
  - Frontend
  - API's
  - Serverless
---

<a href="https://react-countries.vercel.app/" target="_blank">Link</a> |
<a href="https://github.com/jess-daniel/fm-rest-country" target="_blank">Github</a>

##### Summary

This project was developed to learn more about React Query and using Serverless functions to hide API secrets on a frontend-focused project. I'm using the [restcountries.eu](restcountries.eu) API to retrieve the country names and demographic statistics for each country. When you click on a specific country, the name of the country is then passed into the serverless function call to the Eventbrite API, which returns the events for that country and some related data.

##### Future Plans

Future plans for this project include adding a way to save events you're interested in attending and being able to click through to purchase tickets at Eventbrite. This will requrie a pretty big revamp because I wasn't intending to add a database or authentication when I started this project. I will probably do a rewrite using Remix.
