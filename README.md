# Design-of-Nanoplasmonic-structure-using-machine-learning
This project is still under process. The above code file is just a very small fraction of my work. The final work contails DL model with varying more parameters.
The nanoplasmonic structure design is predicted using ML

The geometry taken into consideration is height H of the nanoplasmonic structure and Grating period.
The training data is the transmission spectrum of the nanoplasmonic structure of one layer with substrate as SiO2 and the medium as water with Silver as the nanoplasmonic material.
The H of this one layered structure is varied from 20 to 70 nm. The grating period is varied from 1000 to 1700 nm in steps of 2.
The width is maintained at 500 nm.
The models used are multioutput regressor, chained and unchained with Gradient Boosting Decision Tree, Random Forest, MLP regressor.
The file H_20_70.ipynb has all the code. This file has been made in IBM cloud notebooks. So relative changes are required to use in google colab or other ways.
