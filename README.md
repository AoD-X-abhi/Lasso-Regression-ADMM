# ** Lasso Regression ADMM **
## Overview
This repository includes an examination of the Alternating Direction Method of Multipliers (ADMM) algorithm as well as a Lasso Regression implementation. A distributed variant of ADMM is one of the optimization strategies that are investigated in this work. The objective is to present a thorough explanation of the Lasso Regression model and evaluate its performance in different situations. The project comprises experiments, results, and implementations on real-world datasets.

## Project Composition
This project is organized into the following sections:

- *** Lasso: ***

    - Jupyter Notebooks implementing Lasso Regression may be found in the lasso folder.

    - Examine the code and proceed with the Lasso Regression as  directed in the notebooks.

- *** Data: ***
    - Real Dataset:
        - This contains the Dstaset that has been used in this project
        - The original dataset can be used [here](https://archive.ics.uci.edu/dataset/165/concrete+compressive+strength).

- *** Image: ***
    - The images used in this project are stored in the images folder.
    - Basically it contains all the visualization and plottings. 

## Trials and Outcomes

This section contains the specifics of the three different Lasso Regression versions that were tested. Gradient Descent (GD), Distributed ADMM split by examples, and Alternating Direction Method of Multipliers (ADMM) are some of these implementations. Both a real-world dataset and artificial datasets created in the notebook were used to test the models.

### Lasso Regressions Versions

- *** Gradient Descent (GD) ***
A traditional method for Lasso Regression is the GD model. In order to investigate their effects on convergence, execution times, iteration counts, and performance indicators, it was tested with different step sizes and L1 penalties.

- *** Alternating Direction Method of Multipliers (ADMM) ***
The Lasso problem can be effectively solved with the help of the optimization approach ADMM. It was put into practice with various parameter combinations to see how they affected performance metrics, execution times, iteration counts, and convergence.

- *** Disributed ADMM ***
The distributed version of ADMM involves parallelizing the optimization process among multiple agents. This model was tested with varying numbers of agents to assess its performance in a distributed setting.

## Prerequisites

- ![Python Logo](https://www.python.org/static/community_logos/python-logo.png)
- ![NumPy Logo](https://numpy.org/images/logo.svg)
- ![Pandas Logo](https://pandas.pydata.org/static/img/pandas_white.svg)
- ![Matplotlib Logo](https://matplotlib.org/_static/images/logo2.svg)
- ![Seaborn Logo](https://seaborn.pydata.org/_static/logo-wide-lightbg.svg)
- ![Scikit-learn Logo](https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png)


