#  NYC Yellow Taxi Trip Data Analysis (2023)

##  Project Overview  
This repository contains an Exploratory Data Analysis (EDA) of the 2023 New York City Yellow Taxi Trip dataset. The goal is to uncover demand patterns, fare trends, operational inefficiencies, and passenger behaviors to support strategic decision-making in taxi operations.

##  Key Objectives  
- Load and sample over 1.8M taxi trip records (reduced to 300K for performance).
- Clean and preprocess data (handle missing values, combine duplicate columns, remove outliers).
- Analyze trends by time, location, fare, and passenger behavior.
- Provide visual insights and data-driven recommendations.

##  Core Analysis  
- **Temporal Trends**: Identify peak hours (5–7 PM), high-demand days, and seasonal spikes.
- **Geospatial Analysis**: Map demand across NYC zones using shapefiles (JFK, Midtown, etc.).
- **Fare Insights**: Explore relationships between fare, distance, and trip time.
- **Passenger Behavior**: Analyze tip amounts, payment methods, and trip counts.
- **Operational Metrics**: Identify slowest routes, busiest pickup/drop-off locations, and weekday vs weekend patterns.

##  Key Findings  
- JFK Airport is the top pickup zone.
- Credit cards are the most used payment method.
- Majority of trips are solo passengers.
- Some routes consistently show traffic-related delays.

##  Recommendations  
- Position more cabs in high-demand areas before peak hours.
- Use slow-route data to improve traffic flow and routing.
- Introduce dynamic pricing for peak/off-peak travel.
- Offer loyalty programs for credit card users and frequent riders.

##  Tech Stack  
- Python (Pandas, NumPy, Matplotlib, Seaborn, GeoPandas)  
- Jupyter Notebook  
- NYC Taxi Zone shapefiles  
- Parquet & CSV file handling

Author
- Manish Atwal
