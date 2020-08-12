# Data Analysis and Visulization of What Trends on Youtube India

## Data Preprocessing  
* Handing datetime and Timestamp data.  

* Map category ID of each video to the category it was tredning in.  

* Creating new variable *Number of Words in Title* to analyse how title length effects trending as people prefer concise titles.  

* Creating new variable *External links in video discription*.  
  * We have heard that youtube algorithm favoures videos with no external links. Lets see its effects on trending.  
  
* Dislike Fraction - How many of the assesments were dislikes.  
  * *Note - Some of the trending vidoes had 0 likes and 0 dislikes. To overcome this we use weighted laplance moving instead of actual ratio of dislikes/(dislikes +            likes).*  
  
* Handing missing values.  
  
* Creating new variable *Days before trending*.  
  
* Creating new variable *average views per day*.  
  
**Preprocessed Data is available in [__preprocessed_vids.csv__](https://github.com/PrakarshBhardwaj/Youtube-India-Data-Analysis/blob/master/preprocessed_vids.csv)**  
  
  
## Data Visulization  
### Views, Comments, Dislikes and Likes Distributions  
<img src="imgs/firstvisual.png">  
  
  
### Trending v/s Time published  
<img src="imgs/trendingvtime.png">  
  
  
### Feature Correlation - Spearman  
We use *spearman correlation* to account for non-linear corelations as well.
<img src="imgs/featurecorr.png">  
  
  
### Title Word Count v/s Trending  
<img src="imgs/titleword.png">  
  
  
### External Links in Video Discription v/s Trending  
<img src="imgs/ext_links.png">  
  
  
### Most trending channels  
Channels which made it to trending most.
<img src="imgs/trending_channels.png">  
  
  
### Most trending topics  
Topics under which most vidoes made it to trending.
<img src="imgs/trending_channels.png">  
  
  
### Days before trending  
<img src="imgs/days_taken.png">  
  
  
### Most Hated Videos  
<img src="imgs/hated.png">  
  
  
### Tags  
Lets create a workcloud to a picture of most popular tags.  
<img src="imgs/wordcloud.png">  
  
