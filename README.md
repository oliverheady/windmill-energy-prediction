# windmill-energy-prediction
A data-driven analysis of wind speeds to optimize the site selection for wind farms. Using wind speed data from a reference site to predict the wind speed at a candidate site.

Wind Speed Prediction

Overview

This project aims to leverage wind speed data from reference sites to make informed decisions about potential wind farm locations. By analyzing the correlation between wind speeds at a candidate site and a nearby reference site, we can predict the energy output and, in turn, the feasibility of establishing a new wind farm.

Motivation

Building a wind farm is a significant investment. The success of such an investment heavily relies on the site's wind speed. A miscalculation or poor site selection can lead to inadequate energy production, rendering the investment less fruitful or even loss-making. By accurately predicting wind speeds, we can mitigate this risk.

Dataset

The Windmill.txt dataset contains measurements of wind speed at a candidate site (CSpd) and an accompanying reference site (RSpd) for 1,116 areas.

Analysis Highlights:

The correlation coefficient between the wind speed at the reference site and the candidate site is 0.7556, indicating a strong positive relationship.
A simple linear regression model was fitted, which can be represented by the equation 
CSpd=3.14+0.76×RSpd.
This model suggests that for every 1 m/s increase in wind speed at the reference site, we can expect a 0.76 m/s increase at the candidate site.
The average wind speed at the candidate site when the wind speed at the reference site is 12 m/s is approximately 12.26 m/s.
Key Takeaways for Business Managers:

Predictive Power: Our analysis provides a robust tool to predict wind speeds at a potential new site based on data from a nearby reference site. This predictive power is vital for making informed decisions about where to build new wind farms.
Accuracy: The wind speeds at the new site will be similar to the reference site approximately 76% of the time. This accuracy level can significantly reduce the risk associated with multi-million dollar investments in new wind farms.
