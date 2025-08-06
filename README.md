I practice data scraping using Selenium in Python to extract information from Coles Youtube videos.
Apologize for such a long annoying warning in the code file. Please continue scroll down and ignore that.
After pulling out the data about video title, video link, published date, like count, view count, comment count and specific commenter's name and content for each, I performed some cleaning and data exploration such as overview statistics and graphs.
Some findings are : 

1) There are 1082 videos, though it is stated that Coles has around 1.2k videos on Youtube statistics so besides videos there are approx 100+ short reels.

2) Some basic statistics:

          views	    likes	    comments	  length (in seconds)
count	    1,082	    1,082	      936	             1,082
mean	   23,322	      152	        2	               132
std	     79,689	      537	        8	               107
min	        255	        0	        0	                 9
25%	      2,033	       26	        0	                58
50%	      4,252	       47	        0	               101
75%	     12,017	       96	        1	               173
max	  1,029,200	   10,000	      177	               823

Overall the Coles Youtube channel is quite low key.

3) The youtube does well at the early years 2016-2019. Most popular videos which have highest views, likes or comments fall in this period of time. 

4) There are considerable outliers in the distribution of likes, views, comments and length.

5) Through times, the video's length seems increase significantly.
