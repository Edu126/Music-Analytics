# Music-Analytics


This notebook serves as an academic endeavour to analyze data obtained from the Spotify API and YouTube. The primary
objective is to construct a predictive model for assessing the popularity of songs based on their inherent characteristics. As a work-in-progress project, constructive feedback is warmly encouraged and greatly appreciated. The intention is to develop insights into song
popularity prediction through data-driven exploration and modelling.

## About the Data & Output

Music is beautiful; it has the power to transport us to different moments and places. It plays an important role alongside our sense of hearing and long-term memory.

**Artist**
- Ed Sheeran really knows how to make good music!
- Two out of the top 10 artists are Hispanic performers.
- CoComelon is a reference in children's music, worth exploring if you want to delve into this genre.

**Songs**
- "Despacito" is a worldwide case study as it has a melodic composition that plays interestingly with our brains. It is lively, simple, repetitive, and has a catchy rhythm.

**Factors that seem to make songs more or less popular**
In this part of the exercise, I like to use a [table](#Quick-table-view-by-popularity-cluster) to identify values and complement the analysis with a [radar diagram](#3.2.-Multi-variate-Analysis) that provides a more standardized and comparative visual (inspired by video games)(I'm checking why sometimes it's displayed and sometimes is not).

- Instrumentalness decreases as the popularity group increases, indicating that popular songs tend to have more vocal elements.
- Loudness levels decrease as the popularity group increases, suggesting a more balanced volume in popular songs.
- Danceability shows a notable trend, indicating that more popular songs tend to have higher danceability, potentially appealing to a larger audience.

**And the predictions?**
This exercise not only gives us a visual understanding of the probability of a song's popularity but also provides initial insights on how current songs can work on strategies to "increase" their popularity tier.

- Duration_ms, Loudness, and Tempo are among the top 3 representative variables for our model to identify which popularity group a song could belong to.

- If we zoom out of the exercise and recognize that there are more variables involved in the process of popularizing a song that we might not be considering, we could take this [top 10 songs](#Top-10-Mid-popularity-songs-with-a-popability-to-be-High-popular) and implement a boosting marketing strategy.

- If you're an artist looking to release a new song, how about first looking at existing songs with a similar flow and creating playlists with the most popular ones to enter the market?

**What other strategies can you think of?** Post them in the comments.

### Limitations and Considerations:
This analysis may include certain biases and uncertainties as we do not know what other factors may be influencing the popularity of these songs. Let's consider factors such as language, wording of the lyrics, the music producer, as well as other elements like undersampling or oversampling of certain types of popular songs.
