---
layout: default
modal-id: 2
date: 2017-18-04
img: cake.png
alt: image-alt
project-date: July 2014
client: AltoCom Ltd
client_url: http://altocom.kz/
category: Android
description: Kurs Tenge is a simple application which shows up-to-the-minute exchange rates, historical charts and includes a rates calculator. This app was the first application which I shipped to the market.
<h4> Technical description </h4>
<p>  This application was written in 1 day as part of company's internal hackathon. </p>
<p> It parses rss feed(in xml) provided by api , writes new rates to file and finally present them to user. </p>
<p> At the time when I was developing this app I had no idea that magical tools like reactive programming(rxJava) and retrofit with GSONs are exist(forgive me this please I was early-junior), but I remember that I tried to follow MVC pattern. So, an activity is my controller, rates are models and views are fragments.</p>
<p> To show smooth history rates diagram all calculations are done in AsynkTask(now I know that there are better ways for this).  </p>
url_market: https://play.google.com/store/apps/details?id=kz.altocom.kurs_tenge
url_title: Play Market
using: java 7
---
