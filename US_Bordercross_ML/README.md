# US_Bordercross_ML

## Features Overview

- Value (Number of Crossings) → Represents the number of trucks, buses, personal vehicles, or pedestrians crossing the   border. Can predict traffic volume at a port based on factors like location, port type, and time. Helps in forecasting 
  future traffic trends at various ports.

- Independent Variables : You can use the following features to predict the number of crossings (Value):

- Port Name (Categorical) – Some ports have higher traffic than others.

- State (Categorical) – Some states have more border crossings.

- Port Code (Numerical) – Can be used as a unique identifier.

- Border (Categorical) – US-Canada vs. US-Mexico, as crossing patterns differ.

- Date (Time-based) – To capture seasonal trends in traffic.

- Measure (Categorical) – Type of crossing (trucks, buses, pedestrians, etc.).

- Latitude & Longitude (Numerical) – Location-based impact.


## EDA
### Conclusion & Key Insights for Government Stakeholders
#### 🚦 US-Mexico Border Needs Greater Attention

- Traffic across the US-Mexico border is ~1.67 times higher than the US-Canada border.

- This indicates a heavier load on infrastructure and border personnel in southern ports, warranting higher investment and staffing.

#### 📍 High-Pressure States and Ports

- Texas dominates in total crossings, followed by New York and Michigan.

- Laredo, El Paso, and Hidalgo (TX) are top contributors to border movement. These locations may benefit from expanded lanes, automated checks, and surveillance upgrades.

#### 📅 Seasonal Surges in Traffic

- Crossings peak in March, July, and August, likely due to spring/summer travel and trade seasons.

- Planning resources seasonally (e.g., temp staffing, lane management) can optimize wait times and service delivery.

#### 🚶‍♂️ Measure Type Distribution

- Most crossings involve personal vehicle passengers, vehicles, and pedestrians, which suggests a high volume of non-commercial traffic.

- Policies may need to differentiate commercial and non-commercial lanes, and invest in pedestrian infrastructure at key ports.

#### 📌 Geolocation-Based Planning

- Ports like Laredo, Detroit, and El Paso serve as strategic entry points.

- Geospatial data can guide placement of new checkpoints, technology (e.g., scanners, ANPR), and maintenance priorities.
  
