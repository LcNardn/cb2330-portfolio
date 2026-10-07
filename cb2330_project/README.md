# cb2330_project
The repository contains group 19's project for the course *"CB2330-Fondations of scientific computing for life science"*, compulsory course of the first year of TMBBM, KTH 2026.

The project consist in the backword and forwards modeling of an article of choice.

In this case the article was the suggested *B44*, with title *Most ornamental plants on sale in garden centres are unattractive to flower-visiting insects*. Link to the article [here](https://pmc.ncbi.nlm.nih.gov/articles/PMC5344017/#sec17).

Based on the dataset provided in the article the chosen distribution for the modeling was the negative binomial.

$$ \mathrm{X} \sim \mathcal{NB}(c,p) $$

<br>
<br>

The repository contains 4 elements: this file(*README*), *ProjectCB2330.ipynb*, *data/* and *data/README*.

<br>

#### **ProjectCB2330.ipynb**
An already run colab notebook containing the actual project.

The file contains:
1.    Project card;
2.   Model's choice;
3.   Paper summary/abstract;
4.   Monte Carlo simulation;
5.   Parametirazation, with assessment of the uncertainty;
6.   Conclusions;
7.   Model's limits.

Every step is explained in its own section through text cells and followed by the code.

It is possible to re-run the file by opening in it in colab or copying the code in any python intepreter.

<br>

#### **data/**
A folder containing all the data files extrapolated from the articles and used in *ProjectCB2330.ipynb*.

<br>

#### **data/README**
README of the data folder, a guide for the understanding of the data.


<br>
<br>
This repository was created by Luca Nardon(github profile: Lc_Nardn) and Chiara Cappelletti(github profile: ChiaraC-12).
