# Surfs Up Ice Cream

The purpose of this project was to analyze Hawaiian Weather data to decide if a new ice cream shop would succeed based on the weather conditions.

## Documents and Data Process

We were given a SQLlite database that included information about Hawaii and the weather throughout the year.

A jupyter notebook was used with sqlalchemy and pandas dependancies to connect to the database and extract information about the weather for both June and December as requested.

## Findings

When looking at the data and comparing June and December. We can conbclude that December is only slightly cooler than June.
 * The average temperature for June is around 75 degrees and December is 71. (Results have been rounded up to the nearest degree.)
 * It seems that more than 50% of the temperature data for June is above 75 degrees and December is very close to that with more than 50% being only one degree less at 74.
 * The maximum temperature for June registered 85 degrees while December registered 83.
 * The lows for each month is where we see the biggest drops in temperature. The June low is 64 degrees and the December low is 56 degrees.
 
 ## Conclusion
 
Based on the data given, I do think this would be a good location to start an ice cream shop as it seems the weather remains consistantly warm for most of the year. It's important to note that there was a bit less temperature data pulled for December. The count for information was 1517 in contrast with June that had 1700 datapoints. 
With that being said, I still believe it would be a good location to start this business.


