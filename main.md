---
title: Tyssue, an epithelium modeling library
author: Guillaume Gay, Morphogénie Logiciels
susbtitle: 3rd Workshop Biofabrication & Cancer
date: Montpellier, 25 September 2019
logo: images/logo.png
fontsize: 11pt
width: 1080
height: 720
...


# Understanding epithelium mechanics at the cell level

## Epithelial morphogenesis

![Farhadifar et al. 2007](images/epithelium.png "Drosophila embryo ectoderm")

. . .

> Simple mechanics are often  enough

## Role of apoptosis in fold formation

:::::::::::::: {.columns}
::: {.column width="50%"}
![](images/apical_vue_in_vivo.gif "Leg joint in vivo")
:::
::: {.column width="50%"}
![](images/leg_joint.png "Modeling")
:::
::::::::::::::

##

:::::::::::::: {.columns}
::: {.column width="50%"}
![Without AB force or propagation](images/fold_00_small.gif "Without apical-basal force")
:::
::: {.column width="50%"}
![With AB force or propagation](images/fold_12_small.gif "With apical-basal force")
:::
::::::::::::::

. . .

> Single cell processes interact with tissue level mechanisms


# The `tyssue` library

## Design and architecture

![](images/data_model.png)

. . .


> Modular design widens the range of applications

## A gallery

![](images/ellipsoid.png)

##


![](images/fold_ellipsoid.gif){width=800}

##

![](images/rheology.gif){width=600}


##

![](images/organoid.png)


## Open questions

![](images/pseudo_strat_and_basalcomplex.png)

. . .

> There's still work to do!

# Force inference and model fitting

## 2D segementation

![](images/segmentation.png)


## Force inference and model fitting

![](images/segmented.png)


. . .


> Good 2D workflow

## Perspectives

* Towards 3D
* Deep learning


# Computer Assisted Tissue Engineering

##

* Microscopy data to models
* Models as virtual experiments
* Models as parameter spaces
