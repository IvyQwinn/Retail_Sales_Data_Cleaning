# Retail_Sales_Data_Cleaning
Data Cleaning and Preprocessing for Retail Sales Dataset

# Retail Sales Data Cleaning and Preprocessing

## Overview
This project involves performing data cleaning and preprocessing on a retail sales dataset to prepare it for further analysis or modeling. The dataset used for this analysis includes various features related to retail sales over time.

## Dataset
The dataset used in this project is the Retail Sales dataset, which can be downloaded from [Kaggle](https://www.kaggle.com/c/demand-forecasting-kernels-only/data).

### Features
- **date**: The date of the sale
- **store**: The store number
- **item**: The item number
- **sales**: The number of items sold

## Project Structure
The repository contains the following files and directories:
- `data/`: Directory containing the dataset
  - `train.csv`: The dataset file
- `Retail_Sales_Data_Cleaning.ipynb`: Jupyter Notebook with the complete data cleaning and preprocessing process
- `README.md`: This file

## Steps and Analysis

### 1. Data Loading and Exploration
- Load the dataset and display the first few rows
- Summarize the dataset to understand the basic statistics
- Check for missing values in the dataset

### 2. Handling Missing Values
- Fill missing numerical values with the median
- Fill missing categorical values with the mode

### 3. Handling Outliers
- Plot boxplots to detect outliers in the sales data
- Remove outliers based on the IQR method

### 4. Feature Engineering
- Create new features from the date column (year, month, day)
- Convert categorical variables into dummy/indicator variables

### 5. Scaling and Normalization
- Standardize the dataset using `StandardScaler`

## How to Run the Notebook
1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/Retail_Sales_Data_Cleaning.git
    cd Retail_Sales_Data_Cleaning
    ```

2. **Install Required Libraries**:
    Ensure you have the required Python libraries installed. You can install them using pip:
    ```sh
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```

3. **Open the Jupyter Notebook**:
    Start Jupyter Notebook and open `Retail_Sales_Data_Cleaning.ipynb` to run the analysis step-by-step.

## Contributing
Contributions are welcome! If you have any improvements or suggestions, please create a pull request or open an issue to discuss.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
- The dataset used in this project is available on [Kaggle](https://www.kaggle.com/c/demand-forecasting-kernels-only/data).

## Author
- Ivy Qwinn

