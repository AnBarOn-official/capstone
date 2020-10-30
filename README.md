# Capstone Project
## By AnBan_Official

### First Assignment: Create Git and Notebook

#### Link to Notebook: https://eu-de.dataplatform.cloud.ibm.com/analytics/notebooks/v2/ed3a1bdd-62cd-4116-82a6-d5c44f400645/view?access_token=60be8a0f8622364bcb732af4eb9615783bb1202751839510f2e8511ecdf3bba0


#### Link to Notebook for Segmenting and Clustering Neighborhoods in the city of Toronto: https://eu-de.dataplatform.cloud.ibm.com/analytics/notebooks/v2/a6e4f868-c54e-4402-a9f7-65e74d86782b/view?access_token=2613b3faab739418ccb160ee909feb763a33e9d2c13186a62dc3a4cf121a633d

#### This file is also uploaded to the repository under the name: "Pre Final Assignment"


### First Final Assignment: Description of the Problem and Data

1. Description of the problem and a discussion of the background

I want to consider the following situation: I am planning to open a restaurant for french cuisine with medium to high price range in Frankfurt am Main/ Germany. Frankfurt is a city with many different kinds of cuisine: local and international. I have been living here for almost 10 years and I noticed, that french cuisine is hardly available, atleast not in the quality I prefer it. Therefore my plan is to open a restaurant myself to fill the gap. In order to find the perfect place for my restaurant I will need to factor in some considerations:

I need an area where...
... people frequent restaurants
... restaurants of a certain standard are located, so people who are willing to spend the money necessary for my restaurant will be available
... people can get easily by means of public or private transportation
... no or hardly any other french restaurant is already located

2. Description of the data and how it will be used to solve the problem

I want to use Foursquare data to locate an area to fullfill the requirements presented in the first part. I can solve the requirements like this:

 a) an area where people frequent restaurants
    I will be looking for the density of restaurants in different areas of the city. I will use districts as substitute for area. Districts with a higher density of               restaurants will be considered better.
 b) restaurants of a certain standard are located
    I will be looking for districts with higher rated restaurants.
 c) people can get easily by means of public or private transportation
    Districts closer to the central public transportation system will be considered better - let's say districts close to the main station and three main subway stations
 d) competition
    Districts with less french restaurants will be considered better

I am going to give points to each district for each factor and choose the district with the highest overall points for my restaurant.
