# IBM Data Science Capstone Project

## Business Object

<br>The main idea of the capstone project is to find out the best area for running a restaurant. That would base on the exploration of Halifax city which in an eastern province, Nova Scotia, Canada. It is not one of the biggest cities in the world, however, it is considered as one of the best cities for living in in Canada. Hence, the assumption is basically made base on this city. The reason why not choose the big city like New York, Toronto or London was that restaurants are satiate already. There is less meaningful to study into that sort of cities. Besides, Halifax is identified as one of the fastest developing cities in Canada. Consequently, studying into the areas of Halifax is the best for running a restaurant is meaningful for those who intend to running their own catering business in Halifax.

## Data Souce

<br>Data was implemented of this project is mainly the coordinates of Halifax. 
1)The first step is to find out the communities, area or neighborhood classification of Halifax. The first idea is to search in Wikipedia. Hence, the communities are found in
https://en.wikipedia.org/wiki/Communities_in_the_Halifax_Regional_Municipality. 
There are four urban communities was captured into the study: Halifax Peninsula, Mainland Halifax, Dartmouth and Bedford. The sub-communities were scraped by using the BeautifulSoup package. Also, the coordinates of each communities were captured from Wikipedia link.
2)The second step would be passing the coordinates to Foursquare database and explore the venues of the communities and transform into map and find the areas with low supply of restaurants.
3)However, during the programming section, the coordinates from Wikipedia is not completable for folium package. Therefore, geocoder package was used for obtain the coordinates for Halifax communities. This step is to pass the communities' names to geocoder and generate coordinates for mapping.

## Methodology
The main methodology to find out the area for opening a restaurant is K-means clustering, which is a unsupervised machine learning approach that grouping data base on their similarity. In the instance of this research purpose, K-means clustering was applied to group neighborhoods based on venues were searched from Foursquare database. 
## Deliverable
The best communities for starting up restaurant are found by comparing the restaurant supply with limitation that lack of consideration of local or visitor population, and result could be with bias.
<br> For detail analysis please refer to Capstone Project Report and the main code.
