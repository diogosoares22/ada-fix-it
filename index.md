
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
<iframe src="General_timeseries_comparison.html" width="100%" height="500">  </iframe>



As we can observe, generally speaking the number of quotes related to Trump is bigger than the number of quotes related to Cliton, but there are some periods in which this is not the case (for example at the beginning of 2015). In addition, as a general trend, we can observe that Clinton number of quotes has decreased a lot from September 2016 until the end of 2017 while the opposite is true for Trump. Which factors are related to this trends ? We will answer this question by describing the main political events in the life  of the two opponents during the years 2015-2017 understanding how these events influenced their media popularity.

### Year 2015: The rise of Trump consent

At the beginning of 2015 Hillary Clinton was very well known in the United States since she had already covered several political positions such as being the first lady of the United States (1993-2001), being an US senator from New York (2001-2009) and serving as the United States Secretary of State (2009-2013). On the other hand, Donald Trump was mostly known at the beginning of 2015 as a business man and it was not until June 2015 that he announced  his entrance into the race for the White House. But 2015 has been a year often considered a turning point in the recent American political scene since we assist to a rapid increase in Trump popularity and consent.
We will have a look at the number of quotes referring to the two politicians over the course of the year 2015.

<iframe src="both_timeseries_2015.html" width="100%" height="500" style="border>  </iframe>



The number of quotes at the beginning of 2015 reflects perfectly the popularity of the two politicians, Trump has very few quotes referring to him until the half of May while Clinton has a much more consistent number of quotes referred to her from the beginning of 2015.

Apparently, until the summer a very small visibility was given to Trump in media while Clinton visibility was quite high during that period, with some small peaks at the beginning of March and at the beginning of April. The two small peaks are probably caused by the controversy arisen in March 2015 when the State Department's inspector general revealed that Clinton had used personal email accounts on a non-government, privately maintained server exclusively, instead of email accounts maintained on federal government servers when conducting official business during her tenure as secretary of state. This event will mark the political carreer of Hillary and will be one of the main discussion points during the debates for the 2016 elections.

Despite the initial lack of quotes referring to Trump, he succeeded to capture an increasing media attention from the beginning of July this is why this period has often been called the summer of Trump. Indeed, Trump announced he was going to candidate as the president of the United States the 15th June 2015 (small peak in the timeseries) and from that moment his consent started to rise. According to researches, his approval rating spiked on 12 July 2015, when he accused Mexicans of "killing us at the border" at a mass rally in Phoenix.

Eight days later his polling average climbed to 16.8% (slightly before the first detected peaks in the timeseries). We also observe that the second detected and third peak for Trump and other minor peaks for Clinton are respectively in the weeks of the first and second republican debate held the 7th of August and the 17th of September. As we can observe, despite the peaks are visible for both the opponents, the Trump's one are bigger. This shows how his character captured more the interest of the media compared to Hillary Clinton. For instance the famous speech against terrorism pronounced by Clinton the 11th November 2015 (first detected peak for Clinton) grabbed some attention but the controversial want of Trump of banning all the muslim entering US (8th December 2015) did it in a way more substantial way.

### Year 2016: The year of the truth

The 2016 year was the decisive year for the future of the United States of America since the 58th presidential election was held the 8th November of 2016. Nobody had a clear answer at the question "who will win the next elections ?": even if Trump took a great advantage on the opponent during the summer of 2015, Clinton could count on the historical support of a great amount of Americans. The year 2016 and in particular the few month before elections have been a turning point in the result of the 2016 elections. Which events grabbed the most the media attention during this year ?


<iframe src="both_timeseries_2016.html" width="100%" height="500">  </iframe>


We can observe that the distribution of the number of quotes about the two politician is quite varied: there are some weeks in which the number of quotes is almost zero while in some other weeks there are peaks of thousands of quotes. Moreover we observe that the distribution is very similar for the two politicians: when one politician has very few quotes the other has very few quotes too and the same is for the peaks. Why this happens ? Which events has influenced this distribution ? How did they influence the election results ?

The media interest in Trump the week the 21th february 2016 could probably be related to the feud between Trump and pope Francis (18 February). The pope indeed pronounced the following words "A person who thinks only about building walls, wherever they may be, and not building bridges, is not Christian." and Trump responded quickly to the pontiff "No leader, especially a religious leader, has the right to question another man’s religion or faith.”. In the following months Trump continued his political campaign attacking the rival: Trump called his likely opponent "unqualified", and said she "should suffer" for her use of a private email server in the beginning of May (big peak for both Trump and Clinton). On top of that a few days after, precisely the second of May, Trump accused China of "raping" US with her trade policy and this event had also for sure grabbed media attention.

The main political events which happened in the following months were the Republican and Democratic national conventions respectively the 18th-21th of July and the 25th-28th of July (two highest peak of the year). In the Republican national convention Trump won the party’s nomination to Republicans’ disbelief,, Trump accepted the party nomination: “Nobody knows the system better than me, which is why I alone can fix it.”. During the Democratic one Clinton became the first woman to accept the nomination of a major party in the US: “Standing here as my mother’s daughter, and my daughter’s mother, I’m so happy this day has come.” She added: “When any barrier falls in America, for anyone, it clears the way for everyone.”. From that moment on the two rivals were decided and the following months, marked by public debates, have been decisive for the result of the elections. The first presidential debate was held the 26th September in New York. It was the most watched debate in American history, with at least 80m people tuning in. Clinton came prepared, Trump not so much. She baited him with charges of racism, sexism and tax avoidance and he took the bait.
After the first and the following debates everything was set up: people only had to vote and to wait for the results. Election day arrived soon (8th November 2016). With a big surprise Trump defeated the opponent Hillary Clinton despite Clinton received a slightly higher number of votes. From that moment on Clinton's popularity has decreased a lot in media quotes while Trump's one has increased drastically right after the elections with a great interest of the media on him around the 15th of December.

### Year 2017: The rise of a new discontent

After the defeat of Clinton in 2016 elections, Trump was inaugurated as the 45th president of the United States on January 20, 2017. How his early actions influenced the mediatic interest on his character ? Let's have a look at the timeseries.


<iframe src="both_timeseries_2017.html" width="100%" height="500">  </iframe>



As we can observe the mediatic popularity of Clinton measured by the number of quotes dropped drastically, on the other hand, Trump's one has generally increased with respet to the two previous years. This could be caused by the fact that the first year of presidency has been full of a variety of controversies involving Trump.

One day after being sworn in as the 45th president of United States (21th Jan), the Women’s March took place. This worldwide protest was prompted by the fact that several of Trump's statements were considered by many as anti-women or otherwise offensive to women, shortly after, the 27th of Jan, Trump signed the first travel ban executive order, halting Syrian refugees and barring citizens from seven countries for 90 days. This events, and other controversies in the first two weeks, led to the first peak(beginning of February) in the Trump timeseries. Another protest happens the 16th February the so called Day Without Immigrants 2017 protests held throughout the United States to demonstrate the importance of immigration. This other protest is probably the cause of the other spike in the Trump timeseries in the third week of February.

We continue then to assist to an increase of number of quotes referred to Trump while the one related to Clinton stays close to zero until the second week of May, indeed the 3rd of May Hillary Clinton was the featured speaker at the Women for Women International were she among other topics, blamed Russian interference in the US election for her loss and 10th the meeting of Trump and the Russian Foreign Minister Ambassador took date.

Th biggest peak in the number of quotes referred to Trump was during the third week of August, indeed in that period (the week before) the Unite the Right rally: a white supremacist rally took place in Charlottesville, Virginia. Far-right groups participated, including self-identified members of the alt-right, neo-Confederates, neo-fascists,white nationalists and neo-Nazis. Some groups chanted racist and antisemitic slogans and carried weapons, Nazi and neo-Nazi symbols. Despite Trump condamned the acts in Charlottesville, many people linked the participants of the rally to Trump supporters and the discontent started to rise.

At the end of august 2017, according to the results of the poll of NCB news:
* 39 percent of Americans approve of Trump’s job as president (compared with 59 percent who disapprove)
* 36 percent have a favorable impression of the president (versus 61 percent with an unfavorable view)
* 38 percent believe immigration hurts the country more than it helps (versus 57 percent who think it helps more than it hurts)

Therefore, despite the number of quotes referring to Trump in 2017 is high, most of them are due to the fact that some controvertial facts happened in the United States during that period. This shows that having a great mediatic interest does not always mean that the character is appreciated by the population.

### Google Trends comparison

According to recent studies of Pew Research center about half (48%) of U.S. adults say they get news from social media “often” or “sometimes”. As a consequence, nowadays, it is not sufficient anymore to study the popularity of a given character on media but it could be useful to study his popularity also in social medias and more in general online. Therefore, a question which might arise spontanously is the following: is the mediatic interest linked to the online interest ? To answer this question we will use Google Trends data. Google Trends is a website by Google that analyzes the popularity of top search queries in Google Search across various regions and languages. The website uses graphs to compare the search volume of different queries over time.


![image](/assets/images/google_trends.png)

We will compare the evolution of the number of quotes during the years 2015-2017 for both Clinton and Trump with Google Trends number of searches in Google of the two politicians in the United States area. For the sake of simplicity we will consider only Trump quotes and Trump trends.


<p align="center"><iframe src="google_trends_comparison_Trump.html" width="100%" height="1550"> </iframe></p>


As we can observe, in 2015 the two curves behave in a similar way. However the same is not true for the years 2016-2017. This is probably caused by the fact that the years 2016 and 2017 are quite special when it comes to Trump. For example in 2016 we observe a great amount of quotes before election periods and a few quotes during election period while the opposite is true when it comes to Google Trends plot. The reason which could explain the behaviour of the two distributions could lie on the fact that even if linked, the mediatic interest and the number of queries are not totally related. For instance, in that case, mediatic attention rose more for previous debates than for election while online interest rose more right after the elections. A similar resoning apply to 2017: events such that the Women’s March are able to attract more the online attention (also thanks to social media) while often this is not the case for newspapers or news websites.
