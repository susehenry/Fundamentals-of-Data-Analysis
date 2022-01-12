# Fundamentals of data analysis

## Introduction

This repository contains two jupyter notebooks exploring different aspects in the fundamentals of data analysis.

## Repository Content

**CAO_Points.ipynb** – in this jupyter notebook data from the cao website is used from 2019, 2020, 2021. This data is available from  CAO Website, the data was saved to my repository and then cleaned, combined, and finally an exploration of data is carried out.

**pyplot.ipynb** – This repository contains a explanation of matplotlib.plyplot and examines ways data can be visually represented using three different plot styles.
1.	Scatterplot
2.	Timeseries Plot
3.	Stem Plot

### Data files
**CAO_Points.ipynb** – 2019 Data, Data, 2020.csv, lv18-19.xlsx

**Pyplot.ipynb**  -  BTC-USD.cv 

### Required Packages
camelot_py == 0.9.0

matplotlib == 3.3.4

numpy == 1.20.1

pandas == 1.2.4

requests == 2.25.1

## View in nbviewer

To view the **pyplot.ipynb** notebook in static format click here: https://nbviewer.org/github/susehenry/Fundamentals-of-Data-Analysis/blob/main/pyplot.ipynb

To view most recent **cao_points.ipynb** in static format clickk here:https://nbviewer.org/github/susehenry/Fundamentals-of-Data-Analysis/blob/main/CAO_Points.ipynb



## How to install and run the project on your local machine

-To run this repository on your on your local machine you will need to install python this can be done using Anaconda3 please check website Installation — Anaconda documentation to check system requirements and installation instructions. 

-Clone this repository in your terminal using the command 
git clone https://github.com/susehenry/Fundamentals-of-Data-Analysis.git

-Install JupyterLab by running the following command in your terminal – 
```python
conda install -c conda-forge jupyterlab
```

-Access the Jupyter notebooks by navigating to the project_notebooks folder using the following command:
```python
cd FUNDAMENTALS-OF-DATA-ANALYSIS
```

Run the notebooks by inputting the following command:
```python
jupyter-lab
```
This will open a browser window where the notebooks can be accessed

## To Use Excalibur - to extract tabular data from PDFs

First you need to install ghost script, see here for dependencies and how to install -https://camelot-py.readthedocs.io/en/master/user/install-deps.html

after installing ghostscript use pip to install Excalibur
```python
pip install exalibur.py
```
And then start using the webserver

```python
excalibur webserver
```

Now you can go to http://localhost:5000 and start extracting tabular data from your PDFs.

User guide for Excalibur avaliable here - https://excalibur-py.readthedocs.io/en/master/user/intro.html


## Acknowledgements

A markdown cheatsheet used to write the README

https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet


