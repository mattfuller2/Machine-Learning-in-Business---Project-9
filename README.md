# Machine-Learning-in-Business---Project-9

# OilyGiant Oil Well Prediction Project

### Description
This project is aimed at helping the OilyGiant mining company determine the best location for a new oil well. The goal is to use machine learning models to predict the volume of oil reserves in different regions based on geological data, and ultimately select the region with the highest potential profit.

### Project Overview
We are provided with geological data from three different regions, which include features that describe the characteristics of each oil well. Using this data, we build a linear regression model to predict the volume of oil reserves and evaluate the potential profitability of each region.

### Project Structure
- **notebook.ipynb**: This notebook contains all the steps for data preparation, model building, evaluation, and final analysis.
- **/datasets/**: Contains the datasets with geological data used for model training and testing.
- **/output/**: Contains the outputs such as predictions, evaluation metrics, and final results.

### Objective
The objective of this project is to develop a machine learning model (linear regression) to predict oil reserves for new oil wells based on the geological features of each well. The model is used to analyze three different regions and determine the best location for drilling, maximizing the potential profit for OilyGiant.

### Key Steps
1. **Data Preparation**:
   - Load and clean the data for analysis.
   - Prepare features and target variables for model training.
   
2. **Model Training and Testing**:
   - Train a linear regression model to predict oil reserves based on geological data.
   - Split the data into training and testing sets.
   - Evaluate the model's performance using metrics like RMSE and R-squared.
   
3. **Profit Calculation**:
   - Calculate the potential profit for each region using predicted oil volumes.
   - Determine the region with the highest expected profit and the lowest risk.

### Installation
To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/oilygiant-oil-well-prediction.git
2. Install the required dependencies
   pip install -r requirements.txt
3. Launch Jupyter Notebook
   jupyter notebook
