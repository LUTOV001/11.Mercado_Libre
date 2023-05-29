# **UCB FinTech Bootcamp Module 11 Challenge**
# *Mercado Libre Traffic*
## **Introduction**
### The Bootcamp Module 11 Challenge - "[Mercado Libre](https://mercadolibre.com/)" Traffic Analysis requires the preparation of a strategy to help the company grow by using search traffic predictions as an indicator for stock trading opportunities.
---
## **Goals and Objectives**
### *Part I.*  x
### *Part II.*  y 
### *Part III.*  z
### *Part IV.*  a 
### *Part V.*  b 
---
## **Technologies and Tools**
### The following list includes the main technologies and tools using during the preparation and deployment of the solution:
### 1. *Python* - Programming language used to code the solution. Version 3.7.13 was used. Required libraries and frames listed in the Installation section below
### 2. *GitHub* - Reposotory for code deployment, version management and documentation of the presented solution
### 3. *Jupyter Labs* - IDE tool for coding, code testing/debugging and solution documentation. Version V3.4.4 was used
### 4. *Git Bash console* - Local console used to test the coded solution and sync wiht GitHub Version 2.40.0.windows.1 was utilized
### 5. *Slack* - Collaboration tool to communicate and brainstorm with other FinTech Bootcamp participants
### 6. *Operative System* - This solution was prepared in a PC running Windows 11 v H22
### For additional details, please refer to the watermark output at the bottom of the Jupyter Notebook
---
## **Installation Guide**

### 1. [prophet](https://facebook.github.io/prophet/) : Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well. Prophet is open source software released by Facebook’s Core Data Science team. It is available for download on CRAN and PyPI. Install in your environment following the steps below:
#### 1.1. Open the GitBash terminal
#### 1.2 Type the following command and press Enter:
```python 
pip install prophet
```
### *Note: The above installation instructions are for the Prophet to work locally in a Windows computer; if Prophet does not work locally, virtual environment options, such as [Google Colab](https://colab.research.google.com/) can be utilized.*

### 2. [hvplot](https://hvplot.holoviz.org/) : hvplot is a Python library that provides a high-level interface for creating interactive and visually appealing visualizations. It is built on top of HoloViews and provides a simplified API for generating plots directly from Pandas DataFrames, GeoPandas DataFrames, xarray datasets, and other data structures commonly used in the PyData ecosystem. To install, follow these steps:
#### 2.1. Open the GitBash terminal
#### 2.2 Type the following command and press Enter:
```python 
pip install hvplot
```
---
## **Solution Structure**

### The **[11.Mercado_Libre](https://github.com/LUTOV001/11.Mercado_Libre)** repository in GitHub contains the solution components. The repository consists of the following folders, subfolders and contents as described below:
 
###   1. Resource : Includes the .csv files containing the crypto token price data in which the analysis is based. 
###   2. gitignore : Instructions for which files/file types to exclude from the sync process between GitHub and the local environment.
###   3. README.md : The present file containing this outline of the challenge and its components.
###   4. *mercado_libre_forecasting_prophet.ipynb* : This is the Jupyter Notebook with the code for the core challenge solution.
###    
---
## **User Instructions**
### 1. Launch the Jupyter Lab from the GitBash terminal using the following command line:
```python 
jupyter lab
```
### 2. From the Jupyter Lab terminal, navigate to where the ***mercado_libre_forecasting_prophet.ipynb*** notebook is located and open it
### 3. Reset the Kernel and
### 4. Run the steps in sequence and verify the results as per the comments in the notebook, including outputs on the screen such as dataframe listing/on screen pring and generated graphs/plots (e.g. plot images for the Elbow and Clustering results)
####
---
## **Credits**

### Prepared by Luis Torres 
### [LUTOV001](https://github.com/LUTOV001)
### May 2023
