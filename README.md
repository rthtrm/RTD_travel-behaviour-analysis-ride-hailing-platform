# Travel Behavior Analysis for Ride-Hailing Platform 🚖

## Project Overview

This project presents an analysis of passenger preferences and the impact of external factors on travel behavior for the ride-hailing company "Z." With the recent launch of Z's new ride-sharing service, understanding passenger behavior patterns under varying weather conditions is crucial for effective product development and evaluation. The analysis combines data from the company's internal database and external sources, such as weather records, to uncover insights into travel patterns and enhance service optimization.

## Key Objectives

- **Analyze Passenger Travel Patterns Under Different Weather Conditions**  
  By examining how weather influences ride-hailing behavior, this analysis provides insights that can guide strategic planning for the new service. Understanding patterns such as destination popularity and travel frequency under specific conditions can help the company anticipate demand and manage resources more effectively.
  
- **Evaluate Popular Destinations and Usage Trends**  
  Identify the most frequently visited districts and examine the factors contributing to their popularity, allowing Z to align its service offerings with customer preferences and demand hotspots.

## Methodology

### Data Collection and Preprocessing
1. **Multi-Source Data Integration:**  
   Collected and combined data from the company’s database and an external weather website, overcoming the challenge of consolidating interrelated information from multiple sources.

2. **Data Transformation:**  
   Extracted and reformatted data into an analyzable structure, including converting competitor trip data to a daily summary and categorizing entries based on weather conditions at the trip start time.

3. **Feature Engineering:**  
   Created a comprehensive dataset with relevant features necessary for hypothesis testing, including fields such as company name, pickup location, destination, date, time, and corresponding weather conditions.

### Exploratory Data Analysis (EDA)
Conducted EDA to visualize passenger patterns across various conditions and identify significant trends in destination popularity, trip frequency, and travel durations under specific weather scenarios.

## Tools & Libraries Used

- **Python Libraries:** pandas, numpy, scipy, seaborn, matplotlib
- **Data Collection:** HTTP requests, BeautifulSoup for web scraping of weather data

## Key Findings

1. **Most Popular Destinations:**  
   The central business district "L" ranks as the top destination, followed by entertainment and recreational areas "RN" and "WL," and the residential area "S." These locations are the most visited, each with unique appeal that drives high passenger traffic.

2. **Airport Destination Insights:**  
   Contrary to preliminary assumptions, O’Hare Airport was the fifth most popular destination, likely due to the availability of alternative transportation options in the city.

3. **Competitor Analysis:**  
   The competitor with the highest number of trips was "FC." However, it should be noted that this data was collected primarily in non-rainy weather, suggesting that weather might influence trip volumes for this competitor.

4. **Impact of Weather on Trip Duration:**  
   A significant difference in trip durations was observed between rainy and non-rainy weather conditions, as validated by the Mann-Whitney U test (α = 0.05). This finding highlights the influence of adverse weather on travel time, which could inform pricing and wait-time estimations under different weather conditions.

## Conclusion

The insights gained from this analysis could inform "Z" in refining its service offerings by adjusting strategies based on popular destinations, weather-driven demand, and competitor performance. This data-driven approach allows Z to enhance user satisfaction through more accurate predictions of demand patterns.

## How to Run the Notebook

1. Clone the repository: `git clone https://github.com/rthtrm/RTD_travel-behaviour-analysis-ride-hailing-platform.git`
2. Install the required libraries: `pip install -r requirements.txt`
3. Open Jupyter Notebook: `jupyter notebook`

## Contact

If you have any questions or feedback, feel free to reach out to me on LinkedIn.
