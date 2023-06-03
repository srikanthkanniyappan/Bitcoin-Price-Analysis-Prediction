<div align="center">
  <img src="https://github.com/srikanthkanniyappan/Bitcoin-Price-Analysis-Prediction/blob/bf263033a1c1b0de4acd92e2f2590bb02b58b8c2/Images/BitcoinLogo.png" alt="Bitcoin Logo" height="150px">
</div>
<h1 align="center">Bitcoin Price Analysis 💰📈📊</h1>
<p align="center">
  <strong>Analyze historical Bitcoin prices with data cleaning, analysis, visualization, and modeling.</strong>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
  <img src="https://img.shields.io/badge/Python-3.7%2B-blue.svg" alt="Python">
  <img src="https://img.shields.io/badge/Pandas-1.3.0-blue.svg" alt="Pandas">
  <img src="https://img.shields.io/badge/NumPy-1.21.0-blue.svg" alt="NumPy">
  <img src="https://img.shields.io/badge/scikit--learn-0.24.2-blue.svg" alt="scikit-learn">
</p>

## Table of Contents 📑

- [Dataset 📁](#dataset-)
- [Project Structure 📂](#project-structure-)
- [Usage 🚀](#usage-)
- [Built With 🔧](#built-with-)
- [Screenshots 📷](#screenshots-)
- [License 📜](#license-)
- [Author 👨‍💻 ](#author-)

## Dataset 📁

The dataset used in this project is stored in a CSV file named "bitcoin_prices2.csv". It contains the following columns:
- `open`: Opening price of Bitcoin
- `high`: Highest price of Bitcoin during the day
- `low`: Lowest price of Bitcoin during the day
- `close`: Closing price of Bitcoin
- `tick_volume`: Tick volume (number of trades) for the day
- `year`: Year of the data
- `month`: Month of the data
- `day`: Day of the data

## Project Structure 📂

The project is organized into several sections:

1. Importing necessary libraries 📚: Importing the required Python libraries for data manipulation, analysis, visualization, and modeling.
2. Data Import 📥: Reading the dataset from the CSV file using the `pd.read_csv()` function and storing it in a pandas DataFrame.
3. Data Cleaning 🧹: Checking for missing values and duplicate rows in the dataset.
4. Data Analysis 📊: Performing various analyses on the dataset, such as calculating average closing prices for each month, average daily price range for a given month and year, and total tick volume for each year.
5. Data Visualization 📈: Creating visualizations to better understand the data, including bar plots for mean and median values of the "open" and "close" columns by year.
6. Model Development & Evaluation 🧪: Splitting the dataset into training and testing sets, training a linear regression model on the training data, making predictions on the testing set, and evaluating the model using mean squared error (MSE) and R-squared (coefficient of determination).

## Usage 🚀

To run the project, follow these steps:

1. Make sure you have the necessary Python libraries installed. You can install them using pip:

   ```bash
   pip install numpy pandas seaborn matplotlib scikit-learn
   
2. Download the "bitcoin_prices2.csv" file and place it in the "Dataset" directory.
3. Open the project in a Python IDE or Jupyter Notebook.
4. Run the code step by step, or execute the desired functions as needed.
5. The results will be displayed in the console or shown in the form of plots.

## Screenshots 📷
Here are some screenshots of the project:
<div align="center">
  <img src="https://github.com/srikanthkanniyappan/Bitcoin-Price-Analysis-Prediction/blob/bf263033a1c1b0de4acd92e2f2590bb02b58b8c2/Images/visualization1.png" alt="Data Visualization 1" width="400">
  <img src="https://github.com/srikanthkanniyappan/Bitcoin-Price-Analysis-Prediction/blob/bf263033a1c1b0de4acd92e2f2590bb02b58b8c2/Images/visualization2.png" alt="Data Visualization 2" width="400">
</div>

<div align="center">
  <img src="https://github.com/srikanthkanniyappan/Bitcoin-Price-Analysis-Prediction/blob/bf263033a1c1b0de4acd92e2f2590bb02b58b8c2/Images/visualization3.png" alt="Data Visualization 3" width="400">   
  <img src="https://github.com/srikanthkanniyappan/Bitcoin-Price-Analysis-Prediction/blob/bf263033a1c1b0de4acd92e2f2590bb02b58b8c2/Images/visualization4.png" alt="Data Visualization 4" width="400">
</div>

## Built With 🔧

This project is built with the following libraries:

- [Python](https://www.python.org/) 🐍
- [Pandas](https://pandas.pydata.org/) 🐼
- [NumPy](https://numpy.org/) 🔢
- [Matplotlib](https://matplotlib.org/) 📊
- [Seaborn](https://seaborn.pydata.org/) 🌊
- [scikit-learn](https://scikit-learn.org/) 🧠

## License 📜

This project is licensed under the [MIT License](LICENSE).

## Author 👨‍💻 

Srikanth Kanniyappan 👨‍💻 

- GitHub: [srikanthkanniyappan](https://github.com/srikanthkanniyappan) :octocat:
- LinkedIn: [srikanthkanniyappan](https://www.linkedin.com/in/srikanthkanniyappan) 👔
- Twitter: [@srikanniyappan](https://twitter.com/SriKanniyappan) 🐦

Feel free to explore and modify the code to suit your needs. Happy analyzing! 😄💻📈
