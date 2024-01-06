# Grading Rubric for Assignment #4

Please include your name at the top of the submitted notebook.

**Important:** Your notebooks should be a polished finished product. For example:

- please remove any extra or unnecessary code.
- please try to use markdown cells with section headers to mark different sections of the analysis.

## Rubric

**Part 1: Visualizing crash data in Philadelphia (20 points)**

- 1.1 Load the geometry for the region being analyzed (2 points)
- 1.2 Get the street network graph (2 points)
- 1.3 Convert your network graph edges to a GeoDataFrame (2 points)
- 1.4 Load PennDOT crash data (1 point)
- 1.5 Convert the crash data to a GeoDataFrame (1 point)
- 1.6 Trim the crash data to Center City (2 points)
- 1.7 Find the nearest edge for each crash (2 points)
- 1.8 Calculate the total number of crashes per street (2 points)
- 1.9 Merge your edges GeoDataFrame and crash count DataFrame (2 points)
- 1.10 Calculate a "Crash Index" (2 points)
- 1.11 Plot a histogram of the crash index values (1 point)
- 1.12 Plot an interactive map of the street network, colored by the crash index (1 point)

**Part 2: Scraping Craigslist (20 points)**

- 2.1: Initialize a selenium driver and open Craigslist (1 point)
- 2.2: Initialize your "soup" (1 point)
- 2.3: Parsing the HTML (2 points)
- 2.4 Find the relevant pieces of information (4 points)
- 2.5 Functions to format the results (4 points)
- 2.6: Putting it all together (4 points)
- 2.7: Plotting rental prices (2 points)
- 2.8: Comparing prices for different sizes (2 points)


**Total points: 40 points**
