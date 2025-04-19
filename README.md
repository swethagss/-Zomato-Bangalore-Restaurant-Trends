# Restaurant Data Analysis and Geospatial Visualization

## **Project Overview**

This project focuses on analyzing restaurant data from Bangalore and providing geospatial visualizations to understand restaurant density and cuisine-specific distribution. The dataset includes information about various restaurants, including their ratings, type and location. The goal is to perform exploratory data analysis (EDA) and create interactive maps that highlight restaurant density and the popularity of specific cuisines such as Italian.

## **Key Tasks**
1. **Restaurant Density Map**: 
    - Visualize the distribution of restaurants across Bangalore.
    - Highlight areas with higher restaurant density using Folium.
  
2. **Cuisine-Specific Map (Italian Restaurants)**:
    - Filter the data to focus on Italian restaurants and visualize their locations on the map.

## **Technologies Used**
- Python
- Pandas
- Matplotlib
- Seaborn
- Folium
- IPython Display (for embedding HTML in Jupyter)

## **Data Source**
The dataset contains information about restaurants in Bangalore, including the following columns:
* `online_order`: Indicates if online ordering is available (Yes/No) 
* `book_table`: Indicates if table booking is available (Yes/No)
* `rate`: Average rating (e.g., 4.1/5)
* `votes`: Number of votes received by the restaurant
* `rest_type`: Type of restaurant (e.g., Casual Dining, Quick Bites)
* `dish_liked`: Popular dishes liked by customers
* `cuisines`: Cuisines offered by the restaurant
* `approx_costfor_two_people`: Approximate cost for two people in INR
* `listed_intype`: Restaurant listing category (e.g., Buffet, Delivery)
* `listed_incity`: Local area in Bangalore where the restaurant is located

## **Steps to Run the Project**
* **Step 1**: Import necessary libraries and load the dataset.
* **Step 2**: Clean and preprocess the data (remove null values, filter specific cuisines).
* **Step 3**: Perform Exploratory Data Analysis (EDA) to understand restaurant ratings, types, and costs.
* **Step 4**: Create an interactive map for restaurant density across Bangalore using Folium.
* **Step 5**: Filter the data for Italian restaurants and plot their locations on a separate map.
* **Step 6**: Save the final interactive maps as HTML files for easy viewing.

## **Map Visualizations**
### 1. Restaurant Density Map
* A map is created to visualize the concentration of restaurants across Bangalore. The density of restaurants is represented using clustered markers.
### Cuisine-Specific Map (Italian Restaurants)
* A separate map shows the distribution of Italian restaurants across the city. This allows for insights into the popularity and geographical concentration of Italian cuisine in Bangalore.

## Results

### 1.Restaurant Density: 
* The interactive map clearly shows the concentration of restaurants across Bangalore, with areas like MG Road, Koramangala, and Indiranagar standing out for their high restaurant density.
### 2.Cuisine-Specific Map (Italian): 
* The map reveals which neighborhoods in Bangalore have a high concentration of Italian restaurants. It helps identify regions with a preference for Italian cuisine.

<img width="803" alt="Image" src="https://github.com/user-attachments/assets/8433089c-3ff5-4d48-afa4-6dc8fd921351" />

<img width="808" alt="Image" src="https://github.com/user-attachments/assets/c92f0a45-c1d7-434a-b0c0-724fcc1c72c3" />

## Conclusions

### Restaurant Density: 
* High-density areas like MG Road and Koramangala indicate thriving restaurant cultures, with a high number of eateries.
### Cuisine Popularity: 
* Italian cuisine is more concentrated in areas such as Koramangala and Indiranagar, reflecting a preference for international cuisines in trendy neighborhoods.

## Future Work

* Additional Cuisines: Expand the analysis to include more cuisines
* Customer Reviews: Incorporate customer reviews and ratings into the visualization for a more comprehensive analysis.
* Geospatial Clustering: Use clustering algorithms (e.g., K-means) to identify zones with similar types of restaurants.

