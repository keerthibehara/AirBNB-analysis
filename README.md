# AirBNB-analysis

# Summary
We have started with loading the data so far, we have done EDA, null values treatment, and bringing out the conclusions from our analysis

# Objective
There are a large number of listings available throughout the year. Our objective is to perform analysis on these listings so that we get meaningful insights.
We try to draw conclusions from our dataset by performing various operations on the various parameters given to us. We have performed:

Visualization of the different neighbourhood groups based on latitudes and longitudes

Correlation of price with other independent variables

Comparing the average prices of different neighbourhood groups

Comparing the average prices of different neighbourhoods and finding the top 10 neighbourhoods

Comparing different room types with the prices based on the neighbourhood groups

Relationship between hosts and areas

Hosts that have maximum listing

Finding the busiest hosts

Most reviewed hosts

Neighbourhood Groups and their availability

Room Types and their availability

Average stay in each room types


# Introduction
Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analyzed and used for security, business decisions, understanding of customers' and implementation of innovative services.In this project we have presented exploratory data analysis, visualization and interesting insights of the data based on Airbnb booking.

# Dataset
This dataset has around 49,000 observations in it with 16 columns and it is a mix between categorical and numeric values.
Id : Every listing has a unique id.
Host_id : Every host has a unique id which will remain the same for every listing for a particular host.
Host_name : Name of the host.
Neighbourhood_group: The different neighbourhood groups present in our data. Here, there are 5 groups, namely, Manhattan, Brooklyn, Staten Island, Bronx and Queens.
Neighbourhood: The different neighbourhoods in which our hosts are listed.
Latitude : Latitudes of the area
Longitude: Longitudes of the area
Room_type: The type of the room listed
Price: The price of the listing
Minimum_nights: Numbers of nights stayed.
Number_of_reviews: Reviews given to the listing
Reviews_per_month: Reviews given per month
Calculated_host_listings_count: Count of the host listings
Availability_365 : Availability for the year

# Approach
In order to load the data, we have to mount the drive. After mounting the drive, we have imported the important libraries such as NumPy, pandas, seaborn, matplotlib which are useful for our analysisAfter the exploration of our data we have found that some columns have null values and they were treated.We have used the bar charts, pie charts, correlation heatmaps, box plots and scatter plots.We have drawn comparisons between various parameters like prices in various neighbourhood groups, prices in various neighbourhoods, and prices of various room types that are available

# Result
The following are conclusions drawn from the Exploratory Data Analysis:

Manhattan is the predominant neighbourhood group of them all as it is the most  expensive and the busiest of them all.

Fort Wadsworth that belongs to Staten Island is the costliest neighbourhood with a whopping average price of 800 dollars. This could because it might be located far 
away from the buzz making it the most ideal location for a calm vacation.

The most preferred room type is Entire home/apartment, that might be because people might want a homely atmosphere.

Brooklyn and Manhattan have the highest number of hosts. These two neighbourhoods might have people commuting for mostly work and vacations.

Bronx and Queens are two neighbourhoods that stand as mediocre.

Sonder (NYC) has the greatest number of listings

Row (NYC) is the most reviewed host

Staten Island is the neighbourhood that is most available of all the others. This makes Manhattan and Brooklyn the busiest.

Shared rooms have the most availability, probably because people prefer their privacy and prefer staying in entire homes or private rooms.

The average stay in an entire home is 8 nights and private rooms is around 5 to 6 nights.




