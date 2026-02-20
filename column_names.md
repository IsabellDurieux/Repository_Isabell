# Column Names and descriptions for King County Data Set
#Task
# 2 Hypothesen
# 3 insights about the overall data
# 3 recommendations for your client - like pick 3 houses or choose an area where the houses are cheap und where is a flucture
# Erin Robinson	Buyer - Invest in poor neighborhood, buying & selling, costs back + little profit, socially responsible

#Hypotheses
# 1. The lower the grade and condition, the cheaper the houses
# 2. Houses at the waterfront are more expensive compared to houses wo a waterfront
# 3. Cheap houses are accumulated in a specific area (clustered together)

#Whats important to me
# Low price, bad condition, bad grade
# Look 

#Vorgehen
# Ich schaue mir erstmal die condition an, berechne den Preis, mean, mode, median


- **id** - unique identified for a house
- **dateDate** - house was sold
                - We changed the type of the column to date
- **pricePrice** - is prediction target
- **bedroomsNumber** - # of bedrooms
- **bathroomsNumber** - # of bathrooms
                        - Changed type to integer
- **sqft_livingsquare** - footage of the home
- **sqft_lotsquare** - footage of the lot
- **floorsTotal** - floors (levels) in house
- **waterfront** - House which has a view to a waterfront
- **view** - quality of view
- **condition** - How good the condition is ( Overall )
- **grade** - overall grade given to the housing unit, based on King County grading system
- **sqft_above** - square footage of house apart from basement
- **sqft_basement** - square footage of the basement
- **yr_built** - Built Year
- **yr_renovated** - Year when house was renovated
                    - 19910.0 - was divided by 10 to get 1991 for example
- **zipcode** - zip
- **lat** - Latitude coordinate
- **long** - Longitude coordinate
- **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
- **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors
