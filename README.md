# Python Final Year Project

This repository contains the code and datasets for my Python final year project. The project involves analyzing and comparing datasets using various Python libraries.

## Datasets

They are stored in CSV format and are divided into two categories: alcohol and control.

To import the datasets, follow these steps:

1. Download the CSV files from the respective folders: "alcohol" and "control".
2. Place the downloaded CSV files in your project directory.

## Code

The project code is organized as follows:

- `main.py`: This is the main Python script that performs the data analysis and visualization tasks.
- `utils.py`: This file contains utility functions used in the main script.

To run the project, make sure you have the required Python libraries installed. You can install them using the following command:
```shell
pip install pandas numpy matplotlib seaborn
```
Then, run the `main.py` script using the following command:
```shell
python main.py
```

The script will import the datasets, analyze the data, and generate visualizations.

## Results

The project performs the following tasks:

1. Comparing Columns: It compares all the columns of the alcohol and control datasets for 10 trials to identify differences or similarities.

2. Merging Datasets: It merges the alcohol and control datasets for each of the 10 trials to facilitate combined analysis.

3. Calculating Average Reaction Time: It extracts the "signalnum" column between 75 and 130, representing the typical reaction time of a human, and calculates the average reaction time from this subset of data.

4. Boxplot Visualization: It creates boxplots to compare the distribution of reaction times between the alcohol and control datasets.

For more details, refer to the code in the `main.py` script.

---
