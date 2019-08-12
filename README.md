# Metis Project-02 Twitch Linear Regression

### *Primary Goals:*

In this project, we will be looking at the potential relationship between unit sales of a video game and the corresponding streaming metrics on Twitch. Specifically, we will be looking at:

- Watch Time
- Stream Time
- Peak Viewers (the highest number of concurrent watchers on a particular title)
- Peak Channels (the highest number of concurrent streamers on a particular title)
- Streamers
- Average Viewers
- Average Channels

We will be utilizing stats collected on SullyGnome (A third-party Twitch stats and analysis site) for the streaming metrics and scraping data on unit sales from VGChartz. The data collected on both sources is global. We are not limiting this study to a single country. The data available on SullyGnome is only accessible from 2016 to the present so we are limiting our study to 2016 onward.


### *Methodology:* 
 
1. Data collection: Web scraping using Beautiful Soup for VG sales information
2. Data collection: Download CSV files for Twitch streaming metrics.
3. Clean and orient the data. 
4. Look at correlations and pairplots for all years, just a single year, and then individual months.
5. Build linear regression models
6. Zoom in on the coefficients 


### *Working Steps:* 

#### Conclusions
While we didn't find a strong signal between video game sales and streaming metrics, we did find a surprisingly impactful coefficient in the form of peak_streams. Thus, we recommend that Twitch develop a platform sponsorship program to connect video game developers and advertisers with mid-tier streamers to saturate the market with streams within the first 4 months of release. 
