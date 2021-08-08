# Fixed Income and Credit

Docs: TODO: add GithubPages link

This repository represents group project work for course in `Fixed Income and Credit` for advanced degree [Masters in Computational Finance, Union University](http://mcf.raf.edu.rs/).

## Introduction

The objective of this project is to develop understanding of the concept of time value of money, fixed income securities and markets as well as interest rate derivatives.
We study valuation and hedging using these instruments and discuss how these methods are used in practice. Furthermore, we demonstrate how to
apply different models for construction of yield curves, and valuation and hedging using interest rate derivatives and estimating expected bond returns.

Starting point for analysis of all the previously mention things is the dataset that contains:
- Yield_Curve sheet: `monthly yield data`, for period from `1/31/2005 - 5/31/2021`, containing yields, for bonds from `4m tenor up to 30y`.
- PCA sheet: `montly sport rates for ZBCs (zero-coupon bonds)`, for period from `1/31/2000 - 5/31/2021`, for bonds of `1y, 2y, 3y, 4, and 5y maturities`.
- Fama_Bliss sheet: `montly prices of coupon-bearing bonds`, for period from `1/31/1964 - 12/31/2020`, for bonds of `1y, 2y, 3y, 4, and 5y maturities`.


## Project phases

Each of the project phases has been logically separated based on things we're analysing and modeling. Every phase has a detailed description of all the steps,
implementation details, intuition for modeling, interpretation of data analysis, modeling and evaluation that was performed.

For each project phase there is a separate Jupyter Notebook file. You can view the nodebook directhly here on the github (some cells might not be rendered correctly), under `/notebooks` folder,
or you can use the following links to view them with [Jupyter nbviewer](https://nbviewer.jupyter.org/):
- [Assignment 3 (Principal Component Analysis).ipynb](https://nbviewer.jupyter.org/github/mcf-long-short/fixed-income-and-credit/blob/main/notebooks/Assignment%203%20%28Principal%20Component%20Analysis%29.ipynb)
- [Assignment 4 (Bond Returns Predictability).ipynb](https://nbviewer.jupyter.org/github/mcf-long-short/fixed-income-and-credit/blob/main/notebooks/Assignment%204%20%28Bond%20Returns%20Predictability%29.ipynb)

`Note`: Jupyter's nbviewer will render output much better than the Github, but for both of them 3D plots and some other things won't be rendered. It's better to download the notebook
files and open them with Google Collab

## Running Jupyter Notebook
We recommend viewing and running notebook files with [Google Collab](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index),
so you won't have to manage any of the python requirements compared with running them locally. 
