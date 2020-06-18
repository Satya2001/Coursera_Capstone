# Exploring Biryani Venues in Hyderabad
This project explores various biryani venues in Hyderabad. We will be using the help of Foursqaure API and Zomato API to extract data regarding the restaurants.

## Table of Contents
1.[Installation](#installation)
2.[Data](#data)
3.[Exploratory Data Analysis](#exploratorydataanalysis)
4.[Clustering](#clustering)
4.[Results](#results)
5.[License](#license)

## Installation
The following libraries and tools are used in this project.
1. **Numpy**
2. **Pandas**
3. **Seaborn**
4. **Matplotlib**
5. **BeautifulSoup**
6. **Folium**
7. **KMeans**
8. **pgeocode**

## Data
We need data regarding the neighborhoods of Hyderabad, venue locations in each of these neighborhoods and data for each of the venues in the neighborhood.
The Hyderabad neighborhood data id collected from [Hyderabad_Neighborhoods](https://finkode.com/ap/hyderabad.html). We will be using the help of Foursqaure API to obtain details regarding the venues in the neighborhood and Zomato API to obtain details regarding the venue details.
The Hyderabad Neighborhood data contains details details regarding each of the niehborhoods along with its respective pincode. This data does not contains details regarding the location. So using the help of **`pgeocode`** library we will try to find out about the latitude and longtiude details. 
From the location details of each neighborhood we will use **Foursquare API** to find venues in each of the neighborhood. 

## Exploratory Data Analysis

We will be exploring the data to find answers to the following questions
1. What is the price range corresponding to price tier?
2. Is there any relationship between price and rating?
3. Which neighborhood has highest average price for two?
4. Which neighborhood has highest average rating?
5. Which venue category has the highest and lowest average price for two?

## Clustering
We will use `K Means` to find the optimum value of K to cluster the venues. 
From KMeans we find that the optimal value of **K** is 4. 
 

