## Description
This repository contains an analysis concerning the failed orders for Gett, the Isreali-based GTM technology platform.

For background context on the problem we're investigating and information about the data schemas, check out the project link below:
* *https://platform.stratascratch.com/data-projects/insights-failed-orders


## Deliverables
In this analysis, we will investigate the following questions:

1. Build up distribution of orders according to reasons for failure: cancellations before and after driver assignment, and reasons for order rejection. Analyse the resulting plot. Which category has the highest number of orders?
2. Plot the distribution of failed orders by hours. Is there a trend that certain hours have an abnormally high proportion of one category or another? What hours are the biggest fails? How can this be explained?
3. Plot the average time to cancellation with and without driver, by the hour. If there are any outliers in the data, it would be better to remove them. Can we draw any conclusions from this plot?
4. Plot the distribution of average ETA by hours. How can this plot be explained?
5. BONUS Hexagons. Using the h3 and folium packages, calculate how many sizes 8 hexes contain 80% of all orders from the original data sets and visualise the hexes, colouring them by the number of fails on the map.


## Environment Setup & Program Execution**
This project was developed using Python 3.10. However, you should be able to run these notebooks with any version of Python 3.

The required dependencies for this project are listed in requirements.txt. For more information on creating an environment from a requirements file, check out the following:
* https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/

