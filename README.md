# Egypt Internet Speed and Performance Q4 2023 Dataset

This repository contains a dataset on internet speed and performance in Egypt for the fourth quarter of 2023, along with the code used to generate and analyze the data.

## Dataset Description

The dataset includes various metrics related to internet performance, including:

* Download speed
* Upload speed
* Latency
* City
* GPS coordinates

The data is sourced from:

* **WorldCities dataset by Simple Maps:** Provided city information and geographical coordinates.
* **Speedtest by Ookla Global Fixed and Mobile Network Performance Map Tiles:** Provided internet performance data.

## Project Overview

This project aimed to create a comprehensive dataset offering insights into internet speeds across different cities in Egypt. 

The key steps involved:

1. **Data Acquisition:** Gathering data from the mentioned sources.
2. **Data Cleaning and Preprocessing:**
    * Calculating centroid points from Ookla's data.
    * Associating city information based on geographical coordinates.
    * Applying location filters to specifically include Egyptian cities.
    * Utilizing the Haversine function to measure distances and determine the nearest city to each data point.
3. **Exploratory Analysis:**
    * Identifying initial insights, such as faster internet speeds in specific areas.
    * Observing potential biases in data distribution.
4. **Visualization:**
    * Creating a heatmap to visually represent the findings.

## Data Access

The dataset is publicly available on Kaggle: [https://www.kaggle.com/datasets/mohamedtag04/egypt-network-performance-data-q4-2023](https://www.kaggle.com/datasets/mohamedtag04/egypt-network-performance-data-q4-2023)

This repository includes:

* **Jupyter notebook:** Documents the data processing and analysis steps
* **Heatmap:** Visualizes the initial findings on internet speed distribution.
* **Code:** Scripts used for data processing and analysis.

## Further Exploration

This dataset is intended to be a springboard for further exploration and analysis of internet performance in Egypt. You are encouraged to:

* Conduct your own analysis to uncover deeper insights.
* Merge this dataset with others for a more comprehensive understanding.
* Contribute to the project by improving the code or analysis.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
