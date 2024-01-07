<h1 align="center">PROGRAMMING FOR DATA ANALYSIS  - Project 2</h1>
<h1 align="center">Higher Diploma in Computer Science with Data Analytics</h1>
   <p align="center">
   Cecilia Pastore 

## Description

This repository contains Project2 for the subject "PROGRAMMING FOR DATA ANALYSIS" part of the Higher Diploma in Computer Science with Data Analytics at Atlantic Technological University.

**Project assignement:**

>1. Analyse CO2 vs Temperature Anomaly from 800kyrs – present.
>2. Examine one other (paleo/modern) features (e.g. CH4 or polar ice-coverage)
>3. Examine Irish context:
>    o Climate change signals: (see Maynooth study: The emergence of a climate change signal in long-term Irish >meteorological observations - ScienceDirect)
>4. Fuse and analyse data from various data sources and format fused data set as a pandas dataframe and export to csv and json formats
>5. For all of the above variables, analyse the data, the trends and the relationships between them (temporal leads/lags frequency analysis).
>6. Predict global temperature anomaly over next few decades (synthesise data) and compare to published climate models if atmospheric CO2 trends continue
>7. Comment on accelerated warming based on very latest features (e.g. temperature/polar-icecoverage)
>
>Use a Jupyter notebook for your analysis and track your progress using GitHub.
>
>Use an academic referencing style


## Repository Structure

It consists of two main files:

The project is contained and explained in the Jupyter notebook **pfda_project2.ipynb** while the dataset that have been used for his developement are contained in the folder **Data**.

All the dataset exported, as csv and json, have been included in the folder **export**.

## Technology used 

This project have been writen using python 3.11.4 and structurate in a Jupyter notebook using Visual code, version 1.85.1, as an interpreter. Consequently, the file **pfda_project2.ipynb** can be run with  jupyter nootebook or can be open with VS Code. 

## Running the script.

1. Make sure python is installed on your machine. If not [Anaconda](https://www.anaconda.com/) can be installed.

2. Install Jupyter Notebook. Jupyter notebook [can be installed in a terminal](https://jupyter.org/install) tapying on the terminal:

```python
pip install notebook
```
3. I advice also to install a specific extension of jupyter notebook: [jupyter-contrib-nbextensions ](https://pypi.org/project/jupyter-contrib-nbextensions/). This can be done typing on the terminal:

```python
pip install jupyter_contrib_nbextensions
```

3. Install the  needed libraries.

The script use several python package and library and those need to be installed on the system.

The library needed are:
- pandas
- numpy
- seaborn 
- matplotlib
- plotly
- scikit-learn
- statsmodels
- tabulate
- datetime

To install them you can use pip install in a terminal, or command prompt, followed by the librarys:

```python
pip install pandas
pip install numpy
pip install matplotlib 
pip install seaborn
pip install plotly
pip install scikit-learn
pip install statsmodels
pip install tabulate
pip install datetime

```
4. Clone the repository in a local machine using [git clone](https://robots.net/how-to-guide/how-to-download-a-github-repository/).

5. Open the files **tasks.ipynb**/**project.ipynb** in VS Code or, in a terminal, navigate to the directory where the file is saved and run jupyter notebook with the following code:

```python
jupyter notebook
```
---