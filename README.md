# Project: Investigate a Dataset (TMDB 5000 Movie Dataset)

### By: Mohamed Refaiy

##### Jan 2021

## Table of Contents
<ul>
<li><a href="#intro">Introduction</a></li>
<li><a href="#wrangling">Data Wrangling</a></li>
<li><a href="#conclusions">Conclusions</a></li>
</ul>
<a id='intro'></a>

## Introduction  

> This work is dedicated for **Investigate a Dataset Project**. The first project in **Data Analysis Advanced Nanodegree Program**. In this report I will illustrate the steps I took to wrangle and analyze data from TMDB 5000 Movie Dataset.

> What can we say about the success of a movie before it is released? Are there certain companies (Pixar?) that have found a consistent formula? Given that major films costing over &#36;100 million to produce can still flop, this question is more important than ever to the industry. Film aficionados might have different interests. Can we predict which films will be highly rated, whether or not they are a commercial success?
This is a great place to start digging in to those questions, with data on the plot, cast, crew, budget, and revenues of several thousand films.

<a id='wrangling'></a>
## Data Wrangling
The **wrangle** part include 3 main steps: 
1. *Gathering data* - **Direct download:** tmdb-movies.csv
2. *Assessing data* - After gathering data, assess it visually and programmatically for quality and tidiness issues
3. *Cleaning data* - Clean quality and tidiness issues

### Data Cleaning 

> * delete 1 duplicated result 
> * convert release_date to date type
> * seperate genres 
> *replace 0 values in budget_adj, revenue_adj, budget and revenue with **nan** to not affect calculations 
>* drop columns: 
>    * budget 
>    * revenue
>    * original_title 
>    * cast
>    * homepage
>    * tagline
>    * keywords
>    * overview


<a id='conclusions'></a>
## Conclusions


> * **Year 1965 was the most successful year**
> * **Nowadays there is fierce competition between movies which is negative affecting revenues compared to early years in data set where movies counts through year was very low**
> * **More voting affeting negtivaley on voting average** 
> * **Drama movies category is the most successful category and most produced**
> * **Thriller movies can be good investment as it's mostly 3rd or 2nd genres every year** 
> * **Old movies has the least voting activity**
> * **Movies budget range is same since 1960 but profit margin decreased drastically** 
