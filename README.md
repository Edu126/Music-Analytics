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
  ![image](https://github.com/Edu126/Music-Analytics/assets/97917696/4264df13-9c47-4d3a-b2b0-eb16d3d78e14)


**Songs**
- "Despacito" is a worldwide case study as it has a melodic composition that plays interestingly with our brains. It is lively, simple, repetitive, and has a catchy rhythm.
  ![image](https://github.com/Edu126/Music-Analytics/assets/97917696/71bd91ac-84c9-416d-9236-9ecbc4a3bf62)


**Factors that seem to make songs more or less popular**
In this part of the exercise, I like to use a [table](#Quick-table-view-by-popularity-cluster) to identify values and complement the analysis with a [radar diagram](#3.2.-Multi-variate-Analysis) that provides a more standardized and comparative visual (inspired by video games)(I'm checking why sometimes it's displayed and sometimes is not).

- Instrumentalness decreases as the popularity group increases, indicating that popular songs tend to have more vocal elements.
- Loudness levels decrease as the popularity group increases, suggesting a more balanced volume in popular songs.
- Danceability shows a notable trend, indicating that more popular songs tend to have higher danceability, potentially appealing to a larger audience.

![image](https://github.com/Edu126/Music-Analytics/assets/97917696/7dc2da7d-105d-49af-8831-f690987bdfe2)
![image](https://github.com/Edu126/Music-Analytics/assets/97917696/26b27496-2f1b-4826-be58-970014207baa)



**And the predictions?**
This exercise gives us a visual understanding of the probability of a song's popularity and provides initial insights on how current songs can work on strategies to "increase" their popularity tier.

- Duration_ms, Loudness, and Tempo are among our model's top 3 representative variables to identify which popularity group a song could belong to.
![image](https://github.com/Edu126/Music-Analytics/assets/97917696/04b8f73a-0d2e-4bc8-97f2-296a7b6c2ceb)


- If we zoom out of the exercise and recognize that more variables are involved in popularizing a song that we might not be considering,  we could still take this [top 10 songs]() and implement a boosting marketing strategy.
![image](https://github.com/Edu126/Music-Analytics/assets/97917696/2873b74f-c2cb-430b-9e2e-1e282827a3ef)


- If you're an artist looking to release a new song, how about first looking at existing songs with a similar flow and creating playlists with the most popular ones to enter the market?

**What other strategies can you think of?** Post them in the comments.

### Limitations and Considerations:
This analysis may include certain biases and uncertainties as we do not know what other factors may be influencing the popularity of these songs. Let's consider factors such as language, wording of the lyrics, the music producer, and other elements like undersampling or oversampling of certain popular songs.
