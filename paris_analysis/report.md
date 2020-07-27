# Paris

## Table of content
**[The problem](#the-problem)**
**[The data](#the-data)**
 - [Paris shape](#paris-shape)
 - [Venues nearby](#venues-nearby)
 - [Companies list](#companies-list)
 - [Building prices](#building-prices)

## The problem
More than 3000 companies are created each month in Paris<sup>1</sup>.  
And what are the 3 most important elements of sucess when you start a business ?
Location, location, and location !  
So, where is the best place for you to locate the premises of your brand new blockchain banking startup ?  
Not an easy task...  
Transportation is (hopefully) not really an issue in Paris. You will always be near a subway and not (so) far from your employees.
But everything else is important : venues nearby, other companies from the same business field... and of course price !  
In this capstone project we will study Paris by neighborhood to help you choose where to start your researchs

## The Data
*Note: data set descriptions are in french, sorry for that*
### Paris shape
Since 1860, Paris is made of 20 arrondissements. Each one contains 4 neighborhoods. It makes 80 neighborhoods. Each one has a name and a police station :)  
The neighborhoods list and GeoJSON files will mostly be used to split data set by neighborhood and visualize results.  
They are available here as open data : https://opendata.paris.fr/explore/dataset/quartier_paris/
![Paris neightborhoods](https://upload.wikimedia.org/wikipedia/commons/e/e8/Les_quartiers_de_paris.png)
### Venues neerby
Foursquare API will help us understand what kind of venues you have in all Paris Neighborhoods.
### Companies list
Companies premises data will be used to list companies with their size, location and business field.  
Those data are avilable as open data from here : https://www.data.gouv.fr/fr/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret/
### Building prices
Price of premises to rent is not available easily.  
However, buying transactions are available as open data and are a good proxy for renting prices, so we'll use this.  
Multiple datasets are available but we'll prefer this dataset which contain latitude and logitude instead of address : https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres-geolocalisees/


---
<sup>1</sup>: source infogreffe https://www.infogreffe.com/greffe-tribunal/greffe-paris/statistiques-greffe-paris.html
