# 🚲 Bay Wheels (Ford GoBike) Data Exploration and Visualization

Bay Wheels, previously known as **Ford GoBike**, is a bike-sharing system operating in California's San Francisco Bay Area. Launched on **August 29, 2013**, and currently owned by **Lyft**, it is one of the largest regional bike-sharing programs, providing over 262 stations for convenient and sustainable city travel.

This project involves an extensive **exploration and visualization** of public data provided by Bay Wheels, covering trips from **January 2018 to December 2019**. The aim is to uncover insights into user behavior, travel patterns, and operational dynamics using Python data analysis libraries.

---

## 📊 Dataset Overview

- **Rows**: 4,370,704  
- **Columns**: 15  
- **Timeframe**: January 2018 – December 2019  

Each record in the dataset represents a single trip and includes the following features:

- `trip_duration`: Duration of the ride (in seconds)
- `start_time`, `end_time`: Date and time of trip start and end
- `start_station_id`, `end_station_id`: Unique identifiers for stations
- `start_station_name`, `end_station_name`: Names of the stations
- `start_station_latitude`, `start_station_longitude`: GPS location of start station
- `end_station_latitude`, `end_station_longitude`: GPS location of end station
- `bike_id`: Identifier of the bike used
- `user_type`: Subscriber (member) or Customer (casual user)
- `bike_share_for_all_trip`: Indicates if the bike share program applies
- `rental_access_method`: Access method used for bike rental (e.g., app, card)

---

## 🎯 Project Objectives

- Perform data cleaning and wrangling for accurate analysis
- Explore temporal trends in ride frequency and duration
- Identify peak usage times by day, hour, and season
- Compare behavior between subscribers and customers
- Map geospatial patterns of trip starts and ends
- Visualize key insights with clear and effective plots

---

## 🛠️ Tools Used

- **Python**  
- **Pandas** for data manipulation  
- **NumPy** for numerical operations  
- **Matplotlib** and **Seaborn** for static visualizations  
- **Plotly** and **Folium** (optional) for interactive plots and maps

---

## 🧹 Data Preparation

- Converted date/time columns to appropriate datetime format
- Filtered and corrected anomalies in trip duration and location data
- Handled missing and duplicate entries
- Created new features: ride hour, day of week, user type categorization

---

## 📍 Key Insights (Examples)

- **Subscribers** take significantly more rides than casual customers
- **Weekdays** see higher ride volume, especially during **commute hours**
- **Weekends** show a higher proportion of casual customers
- **Downtown San Francisco** is the most active zone for ride starts and ends
- Short trips (<15 mins) dominate, aligning with commuter usage patterns

---

## 📬 Contact

**Waqar Ahmed**  
📧 Email: [waqar.nu@gmail.com](mailto:waqar.nu@gmail.com)  
🔗 GitHub: [waqar-ahmed91](https://github.com/waqar-ahmed91)

---

> This project is conducted for educational purposes and is based on publicly available data from the Bay Wheels system. All analysis is done with the intention of learning and improving data analysis and storytelling skills.
