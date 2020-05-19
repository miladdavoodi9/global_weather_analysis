# OpenWeather API analysis

Challenge:
  - Use citipy to randomly generate coordinates
  - Match coordinates to unique cities
  - Use OpenWeatherMap API to perform weather check on each city and analyze weather differences
  
 Objective:
  - Find correlation between weather specifics to geographic locations
       - Northern Hemisphere - Temperature (F) vs. Latitude
       - Southern Hemisphere - Temperature (F) vs. Latitude
       - Northern Hemisphere - Humidity (%) vs. Latitude
       - Southern Hemisphere - Humidity (%) vs. Latitude
       - Northern Hemisphere - Cloudiness (%) vs. Latitude
       - Southern Hemisphere - Cloudiness (%) vs. Latitude
       - Northern Hemisphere - Wind Speed (mph) vs. Latitude
       - Southern Hemisphere - Wind Speed (mph) vs. Latitude
       
   - Utilize weather API data/findings to narrow down ideal weather conditions for a vacation location
       - Temperature 70 >< 80
       - Wind speed less than 10 mph
       - Minimal cloudiness
       - Used Google Places API to find lodging locations within filtered cities
