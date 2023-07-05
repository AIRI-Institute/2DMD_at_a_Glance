# 2DMD at a Glance: An easy access, manipulation, visualization, and analysis of dataset

## Introduction
The rational design of new materials, as well as materials with desired and remarkable properties, is one of the central problems in modern computational chemistry and theoretical materials science. 
In turn, two-dimensional (2D) materials constitute an important subset of the whole library of all possible materials.
The 2D Material Defect (2DMD) [dataset](https://rolos.com/open/2d-materials-point-defects/)  was created using density functional theory (DFT) calculations to facilitate the application of machine learning methods and the development of new efficient data-driven approaches in the study and design of new 2D materials.
For more detailed information, the users are referred to the original [paper](https://www.nature.com/articles/s41699-023-00369-1).
The dataset contains thermodynamic and electronic properties of point defects in monolayers (bases) of MoS<sub>2</sub>, WSe<sub>2</sub>, hBN, GaSe, InSe, and black phosphorus.
For the broad scientific community and non-specialists/beginners in the field of machine learning, we present ready-made solutions for accessing DFT-derived data, visual and numerical analysis, and data manipulation tools.

## How to use
The '2DMD at a Glance' Jupyter Notebook is designed in a functional programming paradigm to make it easier for non-programmers to interact with it. 
The archive in the open data of the 2DMD dataset (without prior unzipping) is used to prepare data in the dataframe form. 
Thus, we move from the original data to data that provides easy access through various fields (boolean masks).

## Library Requirements
The developed tools do not require any proprietary software. 
In addition to the Python standard library, the [NumPy](https://numpy.org/) and [Pandas](https://pandas.pydata.org/) libraries are used to process and store data and provide quick and easy access. 
For plotting and statistical data visualization, the [Matplotlib](https://matplotlib.org/) and [Seaborn](https://seaborn.pydata.org/) libraries are required. 
To handle crystal structures, the [Pymatgen](https://pymatgen.org/) open-source Python library for materials analysis is used.

