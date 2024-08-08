# Breast-Cancer-Data-Analysis
Python script that installs Apache Spark, sets up the environment and uses PySpark to perform various data analysis tasks, such as loading a dataset, visualizing data, and applying a KMeans clustering model.

# Part 1: Environment Setup
Updates the package list and installs OpenJDK 8.

Downloads and extracts Apache Spark.

Sets environment variables to link the Spark and Java installations.

Installs the 'findspark' package to help locate Spark on your system.

# Part 2:Spark Session Creation:
Initializes Spark using 'findspark'.

Creates a Spark session using 'SparkSession.builder'.

# Part 3: Data Loading and Schema Display:
Loads a CSV file named 'Breastcancer.csv' into a Spark DataFrame.

Displays the first five rows and the schema of the DataFrame.



# Part 4: Data Visualization:
Converts the Spark DataFrame to a Pandas DataFrame for visualization with Seaborn.

Creates a box plot of radius_mean by condition.
![image](https://github.com/user-attachments/assets/f0cf0772-d9a5-4ef6-9f29-67ebe8cc0bf0)

Generates a correlation heatmap.
![image](https://github.com/user-attachments/assets/b0cd7dd1-2b5a-4c1b-bc22-916e79ddc2f5)

# Part 5:KMeans Clustering:

Reads the Breastcancer.csv file again.

Assembles selected features into a feature vector.

Scales the features using 'StandardScaler'.

Fits a KMeans clustering model to the data.

Visualizes the resulting clusters using a pairplot.
![image](https://github.com/user-attachments/assets/9c069f5f-21d5-45f8-93da-8193f4dde068)


# Run
Run this on Google Collab.
