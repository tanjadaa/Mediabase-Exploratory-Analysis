# Mediabase: A Music Industry Exploratory Analysis
Mediabase is a music industry service that monitors radio station airplay in 180 US and Canadian markets. By using Tableau I analyzed trends and insights from "Top 40" Playlist. 

## What is "Top 40" - The Music Industry 
In the music industry, the "Yop 40" is the current, 40 most-popular songs in a particular genre. It is the best-selling or most frequently broadcast popular music. Record charts have traditionally consisted of a total of 40 songs. "Top 40" or "contemporary hit radio" is also a radio format which is what is referred to here from Mediabase.

### Pre-Processing
In this dataset each song is it's own unique entry as artist may have many entries as we'll see later on in the exploarory analysis. I came accross an instance where a handful of songs were named the same and therefore needed to clean this data to obtain the right entries for the analysis. This was done by calling the artist name in brackets after the song to distinguish between the artists and their songs.

### Analysis

Starting with the Rank of a song the current week 'This week' vs its 'Last week' which can indicate any major changes and we can cleary see that majority of the songs rank between 50-200. 

As the dataset consists of 5000+ entries, trimming it down to the top 200 to make the visualization more feasable and understandable as the bigger trends occur from ranking below 100.

![image](https://github.com/tanjadaa/Mediabase-Exploratory-Analysis/blob/main/Visualizations/This%20Week%20vs%20Last%20week.png)

Thereafter, I discovered more of the popular artists tend to have more song entries in "Top 40" and is usually also associated with a major label which we will see on a later discovery.
![image](https://github.com/tanjadaa/Mediabase-Exploratory-Analysis/blob/main/Visualizations/most%20songs.png)

An interesting finding and a contradiction to the famous saying 'The more the merrier' is that the more radio stations a song is on does not necessarily correlate with a higher ranking in terms of how many times a song is being played, hence increasing its overall popularity. 

   Examples we can see here is Post Malone "Goodbyes" f/ Young Thug which ranks #13 but has lesser stations than the 3 songs behind "Loose you to love me", "Graveyard" and "Liar". 

![image](https://github.com/tanjadaa/Mediabase-Exploratory-Analysis/blob/main/Visualizations/StationsOn.png)

## "The big 3"

Moving on to the treemap, based on the sum of the number a song has been played and we see that major labels, as incicated that are a part of "The Big 3". The big 3 record labels are Sony BMG, Universal Music Group (UMG) and Warner Music Group (WMG) which again has it's smaller internal companies under their umbrella such as Atlantic Records, Interscope and Republic etc.) 

Here we see that they make up majority of the chart and as these labels already have a well established reputation they also tend to dominate the Top 40 chart which their capabilites and resources such as marketing and PR as big driving forces. We see a high correlation with many big artists are also associated with major record labels as shown.

## What about smaller / independent record labels?

Another interesting find is although major labels dominate the market, is: 

### 1
An up and coming artist who has a collaboration with an already established artist tend to have a higher ranking as the popularity of the established artist is used as a driving force to bring attention around another emerging artist.

### 2 
A current trend is for emerging artist whom record labels believe in is either to list both record labels together or to launch a smaller label within a mjaor one.  An example of this is the song 'Truth Hurts' by the artist Lizzo. This song is released by both Atlantic Records (which is a part of Warner Music Group) and Nice Life Recordings which is a record label launched under Atlantic Records. 
![image](https://github.com/tanjadaa/Mediabase-Exploratory-Analysis/blob/main/Visualizations/Tree.png)

## Dashboards

Lastsly I've created an interactive dashboard (open TWB file if interested! 🤗 ). Here all the worksheets previously mentioned are displayed and are intertwined with each other, meaning that filtering or clicking one sheet will display the correspoding info in the other worksheets.
![image](https://github.com/tanjadaa/Mediabase-Exploratory-Analysis/blob/main/Visualizations/dashboard1.png)

Here I have filtered by the artist Post Malone and we can see the different rankings in the other worksheets, that he is signed with Republic which is one of the major record labels, he has multiple songs in Top 40 which are successful.

![image](https://github.com/tanjadaa/Mediabase-Exploratory-Analysis/blob/main/Visualizations/dashboard2.png)

Another way of filtering and gaining information through the dashboard is to click and hover over one of the songs in the lower right sheet. Here we see the Artist Name and Title (Dua Lipa, "Don't Start Now") following the rank of #25 and on 174 radio stations. We see the other sheets follow the filter of this specific song.
![image](https://github.com/tanjadaa/Mediabase-Exploratory-Analysis/blob/main/Visualizations/dashboard3.png)

Hope you enjoyed and learned something as I did! 😊 🙌🏻
