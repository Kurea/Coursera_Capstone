# Paris

## The problem
More than 3000 companies are created each month in Paris[^1].
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
<iframe src="https://opendata.paris.fr/explore/embed/dataset/quartier_paris/map/?location=11,48.82921,2.41219&basemap=jawg.streets&static=false&datasetcard=false&scrollWheelZoom=false" width="400" height="300" frameborder="0"></iframe>
### Venues neerby
Foursquare API will help us understand what kind of venues you have in all Paris Neighborhoods.
### Companies list
Companies premises data will be used to list companies with their size, location and business field.
Those data are avilable as open data from here : https://www.data.gouv.fr/fr/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret/
### Building prices
Price of premises to rent is not available easily.
However, buying transactions are available as open data and are a good proxy for renting prices, so we'll use this.
Multiple datasets are available but we'll prefer this dataset which contain latitude and logitude instead of address : https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres-geolocalisees/



[^1]: source infogreffe https://www.infogreffe.com/greffe-tribunal/greffe-paris/statistiques-greffe-paris.html
