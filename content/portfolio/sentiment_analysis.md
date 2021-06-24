+++
description = "A case study using library(tidytext) and practice text from library(janeaustenr)"
thumbnail = "images/emotion_card_by_luigi_mengato_374x260.jpg"
image = "images/emotion_card_by_luigi_mengato_1200x222.jpg"
title = "Sentiment Analysis"
weight = 250
slug = "sentiment_analysis"
author = "John Little"
draft = false
+++  

A brief introduction to text mining and sentiment analysis with visualization.  Analyze public domain novels by Jane Austen, wrangle text-data into submission, tokenize corpora, visualize sentiment and generate word clouds.

#### Sentiment Analysis with library(tidytext)  

<iframe width="560" height="315" src="https://www.youtube.com/embed/P5ihIzoZivc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  

<!-- 
### Register

**Prerequisite:**  Intro to R.  All attendees are expected to have a familiarity with R, RStudio, and the Tidyverse. 

This semester the **Dashboards, slides, and R Markdown** workshop combines elements of this workshop with the [Interactive Dashboards](/portfolio/dashboard_workshop) workshop  

<a href="https://duke.libcal.com/event/7300231" class="button">Register:<br>Slides with Rmarkdown (Xaringan)<br>April 6, 2021</a> 

-->

<br>

### Library packages

> `install.packages(c("tidyverse", "tidytext", "janeaustenr", "wordcloud2"))`

<br>

### Resources

<!-- badges: start -->
[![GitHub Code Repository](https://img.shields.io/badge/GitHub-Code%20Repository-lightgrey?logo=GitHub "GitHub Code Repository")](https://github.com/libjohn/workshop_textmining)
[![Creative Commons CC
BY-NC](https://img.shields.io/badge/Creative%20Commons-BY--NC-EF9421?logo=creative%20commons&logoColor=EF9421 "CC BY-NC")](https://creativecommons.org/licenses/by-nc-nd/4.0/)
[![Launch Rstudio
Binder](https://mybinder.org/badge_logo.svg "Launch RStudio Binder")](https://mybinder.org/v2/gh/libjohn/workshop_textmining/main?urlpath=rstudio)
<!-- badges: end -->

***  

<small>Image credit:  [Emotion Card](https://flickr.com/photos/luigimengato/23670146340/in/photolist-C4DFRo-27Bce9b-nHcY3-6bCrBn-5aQRgm-Y2Ja4K-Xi8M8S-nyQGP-axv1UW-CWEpFr-9wuDCa-66p863-2g6LzPp-6N9E3e-RPpNCj-nK8yLR-6vwPuf-4qC1z5-2iPQ2TC-2j31QyV-ndnRtD-REMxYK-5r6oaB-ejfNQ-bxorqT-7JCzFj-8kriXA-JTqSFZ-nyQGT-4VniCi-nyQGS-Fdorm3-6hCZAA-nzbwz-rEnBe-nzbwB-5a1w8K-2g7oRb8-Kt9oWk-t4fRBz-4wuYac-p9qBFP-p9qnTD-ku34KK-nyQGL-Cwqnbs-23s7zJA-nyQGH-4VrtNm-bSibKR) by [Luigi Mengato](https://flickr.com/photos/luigimengato/")</small>