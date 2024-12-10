# Electricity Usage Analysis in Morocco

## Objective
This project focused on analyzing seasonality in electricity consumption in Morocco, to help identify peak load periods across hours of the day and days of the week, to help make investments to prevent outages during these times. The project aimed to uncover weekly trends and patterns in power consumption, providing actionable insights into usage behaviors. This analysis involved time series visualization, statistical modeling, and trend identification to support energy optimization strategies.

## Data
We will explore data provided by Maven Analytics - Guided Project.

## Importance of understanding trends and patterns in Electricity Usage
The insights of electricity usage are relevant because it bridges data analysis, energy management, and sustainability. Understanding the data empowers stakeholders to make informed data-driven decisions, optimize energy usage, and contribute to a greener, more efficient and sustainable future. By understanding the insights of electricity usage, organizations can implement:

### 1. Data-Driven Decision Making
- Identification of peak consumption periods: organizations can determine when electricity usage is highest, specifically in certain hours or days which can be utilized to optimize operations and manage demand
- Identification of low consumption periods: organizations can determine when electricity usage is lowest, which can assist with cost savings by improving maintenance plans and equipment upgrades
- Detection of inefficiencies such as high usage in off-periods would be more apparent, as well as seasonal differences, for example, more electricity is used during hotter and colder periods
  
### 2. Energy Management and Cost Savings
- Energy optimization: organizations and energy providers can reduce electricity costs by shifting usage away from peak hours
- Plan load distribution: utilities can use consumption patterns to balance energy load distribution across zones or even timeframes to reduce stress on the grid

### 3. Environmental Impact
- Sustainable practices: by identifying areas of high power consumption, organizations can implement sustainable alternatives, such as switching to renewable energy
- Reduction in energy waste: organizations can help promote public awareness on wasteful energy practices which can help reduce energy consumption

### 4. Demand Planning/Forecasting for Resource Allocation
- Forecasting: using historical data to predict future demand and prepare resources based on consumption trends and patterns
- Planning: energy providers can plan production and infrastructure development
- Infrastructure Optimization: insights into usage by time and zone can guide decision-making for infrastructure investments, such as installing new equipment to help with shortages

## Data Dictionary
- Datetime: The date and time of the recording
- Temperature:	The Temperature in Celsius
- Humidity:	The concentration of water vapor in the air
- WindSpeed:	The speed of the wind in kilometers per hour
- GeneralDiffuseFlows:	The measurement of how much emissions gases diffuse into the broader atmosphere
- DiffuseFlows: The measurement of how much emissions gases diffuse into the local atmosphere
- PowerConsumption_Zone1: The power consumption in Kilowatt-Hours in Power Zone 1
- PowerConsumption_Zone2: The power consumption in Kilowatt-Hours in Power Zone 2
- PowerConsumption_Zone3: The power consumption in Kilowatt-Hours in Power Zone 3

## Steps
### 1. Data Preparation
Objective: 
- Read in the csv. file and convert the Datetime column to datetime datatype
- Aggregate consumption for each zone by summing each to get total consumption
- Add hour and day of week columns to dataset

  ### 2. Data Visualization of consumption over time
  Objective: 
  - The data was resampled from 10-minute intervals to 1-hour intervals
  - The data was filtered for January 2017
  - A stacked line chart was created to visualize the total consumption by zone for January 2017.

### 3. Data Visualization of seasonal consumption
Objective:
- A pivot table was created to see average hourly total consumption by days of the week
- A heatmap was created from the pivot table for a better visualization of the data


## Findings
