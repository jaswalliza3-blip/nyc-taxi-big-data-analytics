# NYC Taxi Big Data Analytics

## Project Overview
A big data analytics project using PySpark to clean and process NYC Yellow Taxi trip records and visualize taxi trip patterns.

## Objectives
- Load and process taxi trip data using PySpark.
- Inspect and handle missing values.
- Remove invalid fares, distances, and trip durations.
- Filter fare outliers using the IQR method.
- Explore Spark partitioning and parallel processing.
- Visualize trip frequency, fare distributions, and distance-fare relationships.

## Technologies
Python · PySpark · Pandas · Matplotlib · Google Colab

## Visualizations
1. Taxi trips by pickup hour.
2. Distribution of fare amounts.
3. Trip distance versus fare amount.
4. Average fare by distance group.

## Dataset
NYC TLC Yellow Taxi trip records for March 2016.

Download the dataset from the [NYC TLC Trip Record Data page](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page).

The dataset is not included in this repository because of its size.

## How to Run
1. Open the project in Google Colab.
2. Install PySpark using `pip install pyspark`.
3. Upload `yellow_tripdata_2016-03.csv`.
4. Run the data-loading and cleaning code.
5. Run `visualization_addon.py` after the cleaned Spark DataFrame `df` is ready.

## Notes
The histogram and scatter plot use a sample to keep visualization manageable. Run the code on the actual dataset before reporting results or conclusions.

## Future Improvements
- Compare row counts before and after cleaning.
- Analyze trips by day of the week.
- Compare processing times with different Spark partition counts.
- Add screenshots of the actual visualizations.
