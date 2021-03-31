# Geo tagged US tweets
#### The goal of this project is to practice using API's and in this case figure out how to process data from twitter's website into a format that can be used on a common GIS platform. The code can be viewed in the geosearch.ipynb file, as I used Jupyter Notebooks to accomplish the task.
#### My python code collected a CSV file using Twitter's API the recorded locations of every tweet for a 60 second time interval.
#### The result was a map of geo-tagged tweets across the US collected on January 25th, 2021. 
#### I collected every tweet by filtering them to contain the word "Biden", which should contain ample of data in reference to the recent inauguration. I then used QGIS to map the CSV file and style the results.

#### The distribution of tweets throughout the map is logical, as clusters of tweets were found near major US population centers such as Los Angeles and New York. Additionally, there were little to no tweets coming from sparsely populated places such as middle America and Alaska. Overall I think that the longer we collect tweets, the more the map will look exactly like the population distribution of the United States.


![](img/tweet_map.png)
![](img/map.png)


