# README: Holographic Information Dynamics Galaxy Rotation Curves Analysis

## NOTE: This code can be run entirely in a Google Colab environment located at the following url:
https://colab.research.google.com/drive/1-2O9_3AiAD67QhIexl8kV7a6IyHLYl1q?usp=sharing

# Submission Checklist:
1. System Requirements:
- The experiments were run on Python 3.12.3 and utilized the following packages:
    requests==2.32.3
    numpy==1.26.4
    pandas==2.2.1
    matplotlib==3.8.4
    scikit-learn==1.4.2
    scipy==1.13.0
    seaborn==0.12.2
- Experiments were conducted on a standard Google Colab notebook, but verified to run on a MacBook Air 
utilizing an M2 chipset and Sonoma 14.5 as the OS.

2. Installation:
- Only the packages and a suitable version of python need to be installed. Thus, the time required is minimal, less than five minutes.

3. Demo:
- As different cell blocks are run, dataframe heads and plots will be generated, as well as general output from calculations and statistical analysis.
- The two code blocks that will take the longest to complete are the ones that generate predictions and plots both the trigonometric and wave equation methods. Each section, in Google Colab, may take about 3 minutes or so to run. Depending on local hardware, this can be expedited to 30 seconds or faster.

4. Instructions for use:
- Determine which method you wish to use to load the dataset (steps detailed below), then run the subsequent code blocks.

## Overview

This Jupyter Notebook performs an analysis of galaxy rotation curves using the trigonometric and wave equation methods. The notebook provides two methods for loading the dataset: from a local zip file included in the root directory or by pulling the data from a GitHub repository. Users can choose between these two methods by commenting out or removing the code block related to the method they do not wish to use.

## Prerequisites

Before running the notebook, ensure you have the following Python modules installed:

- requests
- numpy
- pandas
- matplotlib
- scikit-learn
- scipy
- seaborn

You can install the required modules using the following command:

pip install -r requirements.txt

Or, alternatively:

pip install requests numpy pandas matplotlib scikit-learn scipy seaborn

## Running the Notebook

### 1. Data Loading Methods

The notebook contains two code blocks for loading the dataset:

1. **Local Directory Method:** This method loads the dataset from the `Rotmod_LTG.zip` file located in the root directory of the Jupyter Notebook. By default, this method is commented out.

2. **GitHub Method:** This method pulls the dataset directly from a GitHub repository. This is the active method by default.

### 2. Switching Between Data Loading Methods

To load the data locally, uncomment the local directory code block and comment out or delete the GitHub-based code block.

### 3. Running the Notebook

Once you have chosen the data loading method, run the notebook cells sequentially to perform the analysis.

## Results

The notebook will generate a number of files containing visualizations and summary statistics for the galaxy rotation curves.