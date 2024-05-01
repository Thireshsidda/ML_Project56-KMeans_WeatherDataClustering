# ML_Project56-KMeans_WeatherDataClustering

### Kmeans Weather Data Clustering Project README
### Overview
This project focuses on performing k-means clustering using scikit-learn in Python to cluster minute-level weather data collected from a weather station in San Diego, California. The objective is to generate clusters that capture different weather patterns based on sensor measurements such as air pressure, temperature, wind speed, and humidity.

### Project Structure
The project follows the below structure:
##### Data Preparation:
The minute weather data is loaded from a CSV file (minute_weather.csv).

Data cleaning is performed to remove irrelevant columns and null values.
##### Data Description:
The minute weather dataset contains raw sensor measurements captured at one-minute intervals.

Each row represents weather data captured for a one-minute interval.
##### Data Sampling:
Due to the large size of the dataset, sampling is performed to reduce the number of rows.

##### Data Statistics:
Descriptive statistics are calculated to gain insights into the dataset.

Rows with empty rain duration and rain accumulation are dropped.
##### Feature Selection:
Relevant features (e.g., air pressure, temperature, wind speed, humidity) are selected for clustering.

##### Feature Scaling:
The selected features are scaled using the StandardScaler to ensure uniformity in the feature values.

##### K-means Clustering:
The k-means clustering algorithm is applied to the scaled feature data to generate clusters.

The number of clusters is set to 12.

##### Visualization:
Utility functions are defined to visualize the cluster centers and clusters using parallel coordinate plots.

Different weather patterns such as dry days, warm days, and cool days are visualized based on cluster characteristics.

### How to Run
Clone Repository: Clone this repository to your local machine.

Install Dependencies: Ensure all dependencies mentioned in the requirements.txt file are installed.

Download Dataset: Download the minute weather dataset file (minute_weather.csv) and place it in the project directory.

Run Notebook: Open and run the kmeans_weather_clustering.ipynb notebook using Jupyter Notebook or any compatible platform.

Review Results: After running the notebook, review the generated clusters and visualizations to understand different weather patterns.

### Notes
Experiment with different values of k (number of clusters) to explore different weather patterns.

Adjust the feature selection and scaling techniques based on the specific requirements of your analysis.

Customize the visualization functions to include additional features or enhance visualization aesthetics.

Feel free to reach out for any questions or assistance.

### Acknowledgements
This project utilizes minute-level weather data collected from a weather station located in San Diego, California.

The dataset is sourced from an undisclosed weather data provider.

Special thanks to the scikit-learn library for providing efficient clustering algorithms and tools.
