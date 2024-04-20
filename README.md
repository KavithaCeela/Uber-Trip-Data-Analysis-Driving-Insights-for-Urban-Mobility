# Uber-Trip-Data-Analysis-Driving-Insights-for-Urban-Mobility

## Description
<div align="justify">
  This project aims to predict CO2 emissions from various vehicles using the 'Car Fuel & Emissions 2000-2013' dataset. The primary objectives are to develop a machine learning model that accurately predicts CO2 emissions based on vehicle data, identify key factors that significantly influence vehicle emissions, determine how engine capacity correlates with CO2 emission, analyze if certain manufacturers and models have better emission standards, predict noise level based on engine capacity, fuel type, and transmission type, evaluate if engine capacity, transmission type, and fuel type can be used to predict fuel efficiency, and evaluate CO2 emissions based on vehicles' model year. The dataset encompasses diverse vehicle specifications, including emissions (CO2, NOx, CO) and noise levels, linked to engine size, fuel type, and compliance standards. The project leverages machine learning techniques to predict emissions and fuel efficiency, contributing to sustainable environmental strategies and better environmental management. The final model selected is the Bagged Decision Trees Regressor, which has the highest R^2 and lowest MSE and MAE, indicating excellent model fit and superior predictive accuracy.
</div>

## Installation Instructions

- **Install Anaconda**:
  - Download Anaconda from [Anaconda's website](https://www.anaconda.com/products/distribution).
  - Follow the installation instructions for your operating system.

- **Create a Conda Environment**:
  - Open a terminal or Anaconda prompt.
  - Execute: `conda create --name myenv python=3.8`
  - Replace `myenv` with your preferred environment name.

- **Activate the Environment**:
  - In the terminal or Anaconda prompt, run: `conda activate myenv`

- **Install Jupyter Notebook**:
  - Install Jupyter Notebook using conda:
    ```bash
    conda install -c conda-forge notebook
    ```

- **Install Dependencies**:
  - Navigate to the directory containing your `.ipynb` file.
  - Install dependencies using pip:
    ```bash
    pip install -r requirements.txt
    ```
  - Replace `requirements.txt` with the name of your requirements file, if applicable.

- **Start Jupyter Notebook**:
  - Launch the Jupyter Notebook server:
    ```bash
    jupyter notebook
    ```
  - This will open a new tab in your default web browser.
  - Navigate to the directory containing your `.ipynb` file and open it.
  - And Execute all the cells
