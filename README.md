
### Our Data Science Project:
1. **Our Data**: We are using a data set we got off of Kaggle, called "Spotify Most Streamed Songs". The data set has 26 variables, with information such as artist, streams, BPM, "danceability", ect...
2. **Project Goal**: Our goal is to create and analyze a correlation matrix to help us understand the relationship between different variables within our data set. We aim to look at the correlation between danceability and number of streams, as well as BPM and number of streams.
3. **How We Will Use Our Data**: First we will clean our data. Some of the song entries within the file are not real words, and so we will need to find a way to isolate these rows and delete them. From there we will also take out columns that are not relevant to our analysis, such as artist count, released month, released day, in spotify playlists, and other variables that are unnecessary to make the data frame smaller. Within our code there are comments regarding other steps we took to manipulate our data.  
4. **Challenges Faced**: Some of our challenges include that there are song titles that are not real words, and so we will have to find a way to differentiate and remove those. The values under streams were also strings, so we had to convert them to numeric. Additionally, we wanted to group the songs into bins dependent on their number of streams, with bin titles such as "Low, Medium, High, Very High", to better categorize the data. However, it is difficult to get an idea of the range of streams, and so this area of the project needs to be worked through. 

