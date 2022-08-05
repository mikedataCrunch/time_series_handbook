# Time Series Handbook

*Note: This version is forked from the original handbook. My contribution is the addition of discussion on hierarchical data forecast reconciliation approaches and its implementation by way of an entry on the M5 competition (see `time_series_handbook/08_WinningestMethods/README.md`). All of the contributors to this handbook are listed below. -Michael Dorosan*

This handbook extensively covers time series analysis and forecasting, delving from the most fundamental methods to the state-of-the-art. The handbook was made in Python and is designed such that readers can both learn the theory and apply them to real-world problems. Although chapters were made to be stand alone, it is recommended that readers go through the first few chapters to be able to fully appreciate the latter chapters. Moreover, the 
[Jena climate dataset](https://www.kaggle.com/stytch16/jena-climate-2009-2016) is used across several chapters, with a summary of the performance of the models used at the end.

The handbook is structured as follows: in the first part, classical forecasting methods are discussed in detail. The middle part is then dedicated to dynamical forecasting methods and as well as causality and correlations, topics that are particularly essential in understanding the intricacies of time series forecasting. Finally, the last part shows a glimpse into the current trends and open problems in time series forecasting and modeling.

The aim of this handbook is to serve as a practitioner’s guide to forecasting, enabling them to better understand relationships in signals. It is made for an audience with a solid background in Statistics and Mathematics, as well as a basic knowledge of Python. Familiarity with Machine Learning methods is a plus, especially for the later chapters. 


## Outline 
This handbook contains a variety of techniques that you can use for time series analysis -- from simple statistical models to some of the state-of-the-art algorithms as of writing. Here are the items that are covered in this material:
- Chapter 0: [Introduction to Time Series Analysis](00_Introduction)
- Chapter 1: [Autoregressive integrated moving average](01_AutoRegressiveIntegratedMovingAverage)
- Chapter 2: [Linear Trend and Momentum Forecasting](02_LinearForecastingTrendandMomentumForecasting)
- Chapter 3: [Vector Autoregressive Methods](03_VectorAutoregressiveModels)
- Chapter 4: [Granger Causality](04_GrangerCausality)
- Chapter 5: [Simplex and S-map Projections](05_SimplexandSmapProjections)
- Chapter 6: [Convergent Cross Mapping and Sugihara Causality](06_ConvergentCrossMappingandSugiharaCausality)
- Chapter 7: [Cross-Correlations, Fourier Transform and Wavelet Transform](07_CrosscorrelationsFourierTransformandWaveletTransform)
- Chapter 8: [Winningest Methods](08_WinningestMethods)
    

# How to use this reference
Each of the chapters mentioned above includes Jupyter notebook/s that contain/s the discussion of each topic (background, limitations, applications). Most of the datasets used in the handbook are included in this repository, and the details of each are described in the [data folder](data). 

## Setting up your virtual environment
To be able to run the contents of this repository, it is advised that you setup a virtual environment. You can install one via Anaconda or via Python's native `venv` module. 

##### Anaconda 
To set up a virtual environment called `atsa`, run the following in your terminal:

```bash
# this will create an anaconda environment
# called atsa in 'path/to/anaconda3/envs/'
conda create -n atsa
```

To activate and enter the environment, run `conda activate atsa`. To deactivate the environment, either run `conda deactivate atsa` or exit the terminal. For more information on setting up your virtual evironment using Anaconda, please visit [this page](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html).

##### Python venv
To set up a virtual environment called `atsa`, run the following in your terminal:

```bash
# this will create a virtual environment
# called atsa in your home directory
python3 -m venv ~/atsa
```

To activate and enter the environment, run `source ~/atsa/bin/activate`. To deactivate the environment, either run `deactivate` or exit the terminal. Note that every time you want to work on the assignment, you should rerun `source ~/atsa/bin/activate`.

## Rendering the notebooks
To view the individual notebooks outside of Github without setting up a repository or installing any software, you may use [The Jupyter Notebook Viewer](https://nbviewer.jupyter.org/).  
- Open `https://nbviewer.jupyter.org/`
- Paste the link to the notebook. 

When a notebook rendered in nbviewer appears differently from the one rendered github, just append `?flush_cache=true` to the end of the nbviewer URL to force it to rerender.

## Jupyterbook
To view all the chapters of this handbook, please visit this link: [Time Series Analysis Handbook](https://phdinds-aim.github.io/time_series_handbook/)

![Screenshot](jupyterbook_handbook.png)


# Contributors
- Benjur Emmanuel Borja
- Gilbert Michael G. Chua
- Francis James Corpuz
- Carlo Vincienzo Dajac
- Sebastian C. Ibañez
- Prince Joseph Erneszer Javier
- Marissa P. Liponhay
- Maria Eloisa M. Ventura
- Michael Dorosan
- Leo Lorenzo
- Ianne Villanueva
- Joseph Noel
- Antonio Briza
- Millicent Singson
