# linear-logarithmic-axis-plotting

This project provides codes for plotting time-resolved data with linear-logarithmic axis in python. 

## Introduction to the problem - Why Python?

Time-resolved spectroscopy is a common method to reveal time-dependent events in nature. Depending on the method, time-axis may involve a very wide time-scale which is difficult to plot it linear. If it is plotted linear, then fast events will be invisible. If it is plotted logarithmic, then time-axis has to start from a value which is bigger than zero (0). In order to show all the time-scale in one axis, the plot has to be divided; fast time-scale would be plotted in linear, slow time-scale would be plotted in logarithmic. Initially a few softwares were used to solve this problem, then Python was selected among them due to its advantages over the others.

#### Origin. 

Disadvantages; 
  - It is not free to use, license is requried. 
  - It takes a long time to plot data. 

#### Matlab. 
 
Disadvantages; 
  - It is not free to use, license is requried.
  - No axis-divider function is available, therefore two seperate graphs needs to be created and plotted next to each other. This brings complications.

#### Python.
 
Advantages; 
  - **It is free to use.**
  - **Axis divider function is available. Less complicated code than the one in Matlab.**

### Our Specific Case

In our case, where femtosecond lasers are used, time axis starts from femtoseconds (10<sup>-15</sup> seconds) and may end in milliseconds (10<sup>-3</sup> seconds). This needs to be plotted in either logarithmic or in combination of linear-logarithmic. Since the time axis includes "time zero" which is the moment of excitation, it is not possible to draw this moment with only logarithmic scale. What we need here is the combination of linear-logarithmic scale for time-axis. 

### Prerequisites

* [Python](https://www.python.org/) (latest version if possible)
The given codes are developed in Python. For this you need to have Python in your computer. An easy way to download Python is to use [Anaconda](https://www.anaconda.com).
* [Matplotlib](https://matplotlib.org) (A plotting package for Python).
* [JupyterLab](https://jupyterlab.readthedocs.io/en/latest/). Web based user interface to run the code. It is an integrated environment. This will make the life easier for the enduser to edit/run python codes and visualize the plots. Check one of the codes with .ipynb extension in the repository. 

## Built With

* [JupyterLab](https://jupyterlab.readthedocs.io/en/latest/)

## Accessing the codes.

There is lately a bug in github that preview of the codes (with .ipynb extension) is not possible. In case you have this issue, the workaround to see the codes is using the links below;

https://nbviewer.jupyter.org/github/earik87/linear-logarithmic-axis-plotting/blob/master/Plot_linlogtrace_fromdataframe.ipynb
https://nbviewer.jupyter.org/github/earik87/linear-logarithmic-axis-plotting/blob/master/Plot_linlogtrace_frommatfile.ipynb
