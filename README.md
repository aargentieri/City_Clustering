# City Clustering
The aim of this project is classify all of the Italian cities districts applying a clustering algorithm in order to identify possible similarities or differences.

## Clustering algorithm and dynamic maps using R

Moving to another city could be a tough task; especially if you do not know very well the new town, finding the right area to live is not easy. 
Some people love young and lively neighborhoods, others prefer quieter and more residential ones: thanks to machine learning techniques and open data, we discovered similarities and differences among districts of all Italian cities. 

This project classify Italian districts (ACE - cfr. ISTAT) of the biggest Italian cities (with more than 100.000 inhabitants) according to the variables (source: 2011 census survey ISTAT):

* Children (age < 9)
* Young people (20 < age < 34)
* Retired (age > 65)
* People with a degree
* People unemployed
* Foreigners
* Rent houses
* Historical buildings (built before 1945)
* Tourism activities (hotels, restaurants and other cultural activities related to tourism)
* Business activities (notary, lawyers, architects, engineers and other related offices)
* Commercial activities (shops and commercial activities) 


A k-means clustering algorithm has been applied, we obtained as result 5 categories of areas:

1.	__Cluster 1__: Residential districts, suitable for young families
2.	__Cluster 2__: Very quiet neighborhoods, old people and few commercial activities
3.	__Cluster 3__: Centre of the city, very lively neighborhoods with a lot of leisure activities
4.	__Cluster 4__: Outskirt of the city, popular districts with many services,  
5.	__Cluster 5__: Business districts, many offices but no leisure activities 

Check on the map the clustering results.
