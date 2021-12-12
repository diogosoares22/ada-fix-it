
![image](/assets/images/american-gov.jpg)

# Introduction

## Abstract

In the 21st century *media coverage* is a crucial factor for political figures. The public is “meant” to believe everything they are told and not question it, so that people are easily convinced by what they read on newspapers, news websites or social media. Therefore it could be of primarly interest to study and understand *media interest* in different politicians over a specific time period since this interest is capable of influencing the thoughts of billions of people.

## Methods

We could have a rough measure of the above mentioned interest by studying the number of quotes published on newspapers or news websites referred to a given politician on a given period.
In our analysis we will focus on the years 2015-2017 and we will:
* discuss and analyze the evolution of the number of quotes referred to two of the main politicians of the American scene over the past few years: Donald Trump and Hillary Clinton.
* tell the story of the American political scene of these years by comparing it to the evolution of the number of quotes referring to the two politicians; we will identify which factors caused the peaks in the number of quotes or a lack of them.
* compare the media popularity of the two politicians over the years 2015-2017.
* compare our results with Google Trends to see if the conventional media outlets capture the online interest as well.
* try to understand which are the main differences between the speakers whose quotes refer to Trump and the one whose quotes refer to Clinton. 

## Data in numbers

For our analysis we used Quotebank dataset containing 178 million unique, speaker-attributed quotations that were extracted from 196 million English news articles crawled from over 377 thousand web domains between 2015-2020. After a careful selection of the quotes we could be able to collect the following data for our analysis.
<style>
.tablelines table, .tablelines td, .tablelines th {
        border: 1px solid black;
        }
</style>
| Politicians      | Data |
| :---        |    :----:   |
| Donald Trump     | More than 450000 quotes referred to him from more than 30000 different speakers |
| Hillary Clinton   | More than 60000 quotes referred to her from more than 8000 different speakers |
{: .tablelines}

## Analysis of the evolution of the number of quotes

First of all, let's take a look at the general trend of the number of quotes of the two political opponents over the years 2015-2017, feel free to interact with the plot to discover useful information. The first question which might arise spontanously is the following: who has the bigger number of quotes ? Does it relate to the politician popularity ?
<head>
     <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta3/dist/css/bootstrap.min.css" rel="stylesheet"
         integrity="sha384-eOJMYsd53ii+scO/bJGFsiCZc+5NDVN2yr8+0RDqr0Ql0h+rP48ckxlpbzKgwra6" crossorigin="anonymous">
<title>1st Analysis</title>
      <link rel="shortcut icon" type="image/jpg" href="python-logo.png"/>
   </head>
<iframe src="General_timeseries_comparison.html" width="100%" height="500" style="border:1px solid black;">  </iframe>



As we can observe, generally speaking the number of quotes related to Trump is bigger than the number of quotes related to Cliton, but there are some periods in which this is not the case (for example at the beginning of 2015). In addition, as a general trend, we can observe that Clinton number of quotes has decreased a lot from September 2016 until the end of 2017 while the opposite is true for Trump. Which factors are related to this trends ? We will answer this question by describing the main political events in the life  of the two opponents during the years 2015-2017 understanding how these events influenced their media popularity.

### Year 2015: The rise of Trump consent

At the beginning of 2015 Hillary Clinton was very well known in the United States since she had already covered several political positions such as being the first lady of the United States (1993-2001), being an US senator from New York (2001-2009) and serving as the United States Secretary of State (2009-2013). On the other hand, Donald Trump was mostly known at the beginning of 2015 as a business man and it was not until June 2015 that he announced  his entrance into the race for the White House. But 2015 has been a year often considered a turning point in the recent American political scene since we assist to a rapid increase in Trump popularity and consent.
We will have a look at the number of quotes referring to the two politicians over the course of the year 2015.

<iframe src="both_timeseries_2015.html" width="120%" height="500" style="border:1px solid black;">  </iframe>



The number of quotes at the beginning of 2015 reflects perfectly the popularity of the two politicians, Trump has very few quotes referring to him until the half of May while Clinton has a much more consistent number of quotes referred to her from the beginning of 2015. Apparently, until the summer a very small visibility was given to Trump in media while Clinton visibility was quite high during that period, with some small peaks at the beginning of March and at the beginning of April. The two small peaks are probably caused by the controversy arisen in March 2015 when the State Department's inspector general revealed that Clinton had used personal email accounts on a non-government, privately maintained server exclusively, instead of email accounts maintained on federal government servers when conducting official business during her tenure as secretary of state. This event will mark the political carreer of Hillary and will be one of the main discussion points during the debates for the 2016 elections. Despite the initial lack of quotes referring to Trump, he succeeded to capture an increasing media attention from the beginning of July this is why this period has been often called the summer of Trump. Indeed, Trump announced he was going to candidate as the president of the United States the 15th June 2015 (small peak in the timeseries) and from that moment his consent started to rise. According to researches, his approval rating spiked on 12 July 2015, when he accused Mexicans of "killing us at the border" at a mass rally in Phoenix.
Eight days later, he overtook Mr Bush, his polling average climbing to 16.8% (slightly before the first detected peaks in the timeseries).

