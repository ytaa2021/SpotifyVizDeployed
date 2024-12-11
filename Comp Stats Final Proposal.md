1. Group Members: List the members of your group. For the revised proposal, add additional information about each person’s role. Each member of the group should have two jobs: (1) a group dynamic role, (2) a project role. See [Group Roles](https://m154-comp-stats.netlify.app/roles) for more information on allocating tasks. **\- The members of our group are Yotam Twersky and Priya Julian.  Since there are only two of us, we are planning to split group dynamic roles equally.  For the project roles, Yotam will be the director of computation, Priya will be the director of research, and we will split the role of reporter.**  
2. Title: **How To Write A Global Hit Song\!**  
3. Purpose: Describe the general topic/phenomenon you want to explore, as well some carefully considered questions that you hope to address. You should make an argument motivating your work. Why should someone be interested in what you are doing? What do you hope people will learn from your project? **\- We are interested in learning about and visualizing what has made songs successful in various countries over time.  For the purposes of this project, we define a “successful” song as a top charting song for a given year.  Are there trends in the audio features of top songs across countries and time? Are there specific aspects of a song that are consistent across all successful songs? Can we use these features to write songs that are more likely to be successful?**  
4. Data: As best you can, describe where you will find your data, and what kind of data it is. Will you be working with spatial data in shapefiles? Do the data come from json files? Will you be accessing an API to a live data source? Be as specific as you can, listing URLs and file formats if possible. **\- First, we found a dataset that tells us what the top songs were in different countries by year ([https://www.kaggle.com/datasets/hkapoor/spotify-top-songs-by-country-may-2020](https://www.kaggle.com/datasets/hkapoor/spotify-top-songs-by-country-may-2020) ).  Our plan is to collect these songs and then call the Spotify API on each song to learn about their audio features ([https://developer.spotify.com/documentation/web-api/reference/get-audio-features](https://developer.spotify.com/documentation/web-api/reference/get-audio-features)).  Additionally, we will use Python NLTK (Natural Language ToolKit) to analyze the lyrics of each song and classify them by topic/emotion.**  
5. Variables: As much as possible, list, and briefly describe, each variable that you plan to incorporate. If you can, be specific about units, scale, etc. **\- The variables we will consider for each top song will be rank, year, country, audio feature data from spotify: *acousticness, analysis\_url, danceability, duration\_ms, energy, id, instrumentalness, key, liveness, loudness, mode, speechiness, tempo, time\_signature, track\_href, type, uri, valence*, and variables from our lyrical analysis**  
6. End Product: Describe what you hope to deliver as a final product. Will it be a Shiny application that will be posted on the Internet? Will it be a GoogleMaps mash-up? Will it be a package that provides an API to a live data source (e.g., twitteR)? Will it be a method that draws some statistical conclusions? Will it be a predictive model that forecasts future values of some quantity? \- **Our goal is to create a data visualization tool where you can view analytics on what constitutes a top song in a given country for a given year. The interface will be on a map, and it will be a tool where users can obtain insights about what makes music great, and the similarities and differences across countries.** 