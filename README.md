# Anime Expo (AX) Attendance Forecast

![A picture of a crowd standing in front of South Hall during Anime Expo. Photo courtesy of the Anime Expo website.](ax-attendance/anime-expo.jpg)

## Key Insight

The Los Angeles Convention Center (LACC), the current location for Anime Expo, may no longer be a suitable location for Anime Expo unless the organizers find a solution to address increasing attendance.

## Business Problem

![Anime Expo](https://www.anime-expo.org/) is a large anime and manga convention hosted in Southern California every year since 1992 by the Society for Promotion of Japanese Animation (SPJA), which has attracted crowds of Japanese pop culture fans. Despite AX's notable spotlight in modern society, it historically has issues regarding crowd management, staffing, and other logistics regarding the venue (LACC) itself. The latest AX this year (2023) was no exception to this, and news articles and social media are forecasting these problems becoming worse in future years.

Two **business questions** will be addressed in this analysis:

1. What will AX attendance look like in future years?
2. What are some recommendations that can be provided to SPJA due to issues caused by AX's increasing attendance over the past few years?

## Analysis

### Data Source

Attendance data was acquired from [AnimeCons.com](https://animecons.com/events/info/19555/anime-expo-2023). 

Additional notes:

- Any years with no attendance numbers recorded were removed since a forecast will be performed later. This applies to the last four years (2019, 2020, 2021, 2022). 2023 was the most recent convention, so there has been no official confirmation on attendance yet.
- A majority of attendance records are estimates.

### Methods

Linear regression

### Tech Stack

- Excel (for extracting, cleaning, and storing attendance data)
- Tableau (for data visualization)

### Results At A Glance

### What We Learned

Attendance has increased rapidly shortly after Anime Expo moved to its current location in Downtown LA. The steepest increase occured between 2012 and 2014.

### Recommendations

These recommendations were mentioned in the dashboard, but some options SPJA could consider are moving to another (larger) convention center in Southern California and waiting for the LACC expansion to commence. 

### Limitations

- Because SPJA releases attendance numbers for AX primarily through external sources (ie. news media), there was no clean dataset that I could obtain attendance numbers from.
- There was no publicly available data that could be aggregated into smaller categorizations (ie. ticket sales for certain days vs. 4-day passes).
- It is unknown whether SPJA has the technology or capability to track attendance numbers at the convention center itself based on pass types.
- Convention center capacity is measured using the square footage of the available meeting and exhibit halls, not by an estimated maximum number of people. 

### Areas of Improvement

- One recommendation I had was to cap the amount of ticket sales for specific passes, which I wanted to show through a decision tree model with a randomly generated dataset, but I could not implement it due to lack of time. If I had time to work on my machine learning skills and build the model quickly, this model would add some interesting insights.
- I overcompensated for the lack of data and my inability to showcase my skills with LARGE amounts of text. The easy way to solve that would be to add more visuals, of course, but I felt there was nothing I could do with the little amount of data I had.

## Link to Dashboard

[Tableau Dashboard](https://public.tableau.com/views/AnimeExpoAXAttendance-InProgress/AnimeExpoEXPOnentiallycrowded?:language=en-US&:display_count=n&:origin=viz_share_link)
