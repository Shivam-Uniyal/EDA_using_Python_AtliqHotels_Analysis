# AtliQ Hotels Exploratory Data Analysis Project

## Project Overview
This project is an Exploratory Data Analysis (EDA) of AtliQ Hotels' data to extract insights, identify patterns, and perform basic data cleaning and transformation. The project includes tasks such as occupancy rate analysis, revenue calculation, and data visualization.

## Datasets
The following datasets are used in this project:
- **dim_date.csv**: Date-related information.
- **dim_hotels.csv**: Details about hotels, including categories and locations.
- **dim_rooms.csv**: Room-related details, such as categories.
- **fact_aggregated_bookings.csv**: Aggregated booking information.
- **fact_bookings.csv**: Detailed booking data.
- **new_data_august.csv**: Additional booking data for August.

## Key Features
1. **Data Import and Exploration**:
   - Load datasets and explore their structure.
   - Analyze booking platforms, room categories, and hotel details.

2. **Data Cleaning**:
   - Handle invalid guest counts and revenue outliers.
   - Fill missing values in capacity columns with medians.
   - Remove records with bookings exceeding capacity.

3. **Data Transformation**:
   - Create new columns like occupancy percentage.
   - Normalize data and merge datasets.

4. **Insights Generation**:
   - Average occupancy by room category and city.
   - Weekday vs. weekend occupancy trends.
   - Month-by-month revenue analysis.
   - City-wise and hotel-type revenue breakdown.

5. **Visualizations**:
   - Bar charts for occupancy trends.
   - Pie chart for revenue distribution by booking platform.

## Sample Visualizations

Include some sample charts, such as:

Occupancy rate bar chart.
Revenue distribution pie chart.

## Libraries Used:

pandas

