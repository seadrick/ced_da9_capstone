# ced_da9_capstone
Billboard Hot 100 Analysis
	 
Overview:
This project is a comprehensive analysis of Billboard Hot 100 chart data, spanning two distinct periods: the first decade of its existence (1958-1967) and the years from 2012 to 2021.  
Motivation: 
A huge chunk of my professional career has revolved around music in one way or another.  I spent years touring as a guitar tech and have managed a couple of different record shops.  Because of this, chart data has always been something I have had an interest in, so when the opportunity 	came to combine my passion for music and my newly acquired data analysis skillset, I jumped all over it. 
Data Question:
How have music sentiment, genre trends and tempo in Billboard-charting songs evolved over the past six decades?
Data:
-Billboard Hot 100 chart data: https://www.kaggle.com/datasets/dhruvildave/billboard-the-hot-100-songs
-Spotify API: https://developer.spotify.com/documentation/web-api
- Genius Lyrics API: https://docs.genius.com
Technologies:
	Python
•	Jupyter Notebooks
•	Pandas
•	Requests
•	TextBlob
•	Seaborn
Power BI

Analysis:
Once Spotify and Billboard data is merged, I began to pull lyrics using the Genius API.  
 
This code processes each song in data_1959 dataframe and attempts to pull its lyrics from the Genius API.  The ‘Lyrics’ column is either updated with the proper lyrics with the appropriate message should they not be discovered.
 
Once lyrics were pulled, TextBlob (https://www.topcoder.com/thrive/articles/getting-started-with-textblob-for-sentiment-analysis)was used to generate sentiment analysis. 
When all data was pulled I began to utilize seaborn to plot out my information.
Conclusion: 
 
The amount of time songs spent on the charts jumped substantially in 2012-2021.  Where song in the early days were spending about 7 weeks at the most, songs in the latter decade were staying on the charts for more than double the amount of time. 	

 
1950s-1960s: Music listeners generally liked a more mid-tempo song.  Most charting songs were right in the middle of that slow/medium tempo pocket while listeners in the 10s-20s were into a little faster paced material.

 


While songs from both decades were relatively positive, the 50s and 60s win that comparison.  The sentiment started high in the 50s and only got higher as time went on, while the next decade started strong in 2012 but dropped significantly as time went on.  

