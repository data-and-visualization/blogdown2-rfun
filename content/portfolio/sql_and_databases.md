+++
description = "Use dplyr verbs to query remote databases e.g. Google BigQuery public databases"
thumbnail = "images/sql_374x260.svg"
image = "images/sql_dbi_bigquery_2_1200x222.svg"
title = "remote SQL queries with R"
weight = 450
slug = "sql_and_databases"
author = "John Little"
draft = false
+++  

This case study uses library(DBI) and library(bigrquery) to introduce the dBplyr package.  `dbplyr` enables Tidyverse users to leverage `dplyr` functions, rather than composing SQL queries because basic `dplyr` verbs are transformed into SQL.  Additionaly, the DBI package is used to broker database connections (such as ODBC.)

#### SQL database queries using dplyr and DBI

<iframe width="560" height="315" src="https://www.youtube.com/embed/6j27h_17C1Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>  

**Prerequisite:**  Intro to R.  All attendees are expected to have a familiarity with R, RStudio, and the Tidyverse. 

<!-- 
### Register

This semester the **Dashboards, slides, and R Markdown** workshop combines elements of this workshop with the [Interactive Dashboards](/portfolio/dashboard_workshop) workshop  

<a href="https://duke.libcal.com/event/7300231" class="button">Register:<br>Slides with Rmarkdown (Xaringan)<br>April 6, 2021</a> 

-->

### Code Repository and packages used

GitHub code: https://github.com/libjohn/casestudy_bigquery_dbplyr 


> `install.packages(c("tidyverse", "DBI", "dbplyr", "bigrquery"))`

<br>

<!-- badges: start -->
[![Launch Rstudio
Binder](https://mybinder.org/badge_logo.svg "Launch RStudio Binder/Container")](https://mybinder.org/v2/gh/libjohn/casestudy_bigquery_dbplyr/master?urlpath=rstudio)

[![Creative Commons CC
BY-NC](https://img.shields.io/badge/Creative%20Commons-BY--NC-EF9421?logo=creative%20commons&logoColor=EF9421 "CC BY-NC")](https://creativecommons.org/licenses/by-nc-nd/4.0/)
<!-- badges: end -->








