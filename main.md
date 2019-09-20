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

![Gettings, Monier et al. 2015](images/leg_joint.png)


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

<table>
    <tr>
        <td> <img data-src="images/3cells_type1.gif" alt="Type 1 transition in 3 cells" /></td>
        <td> <img data-src="images/rheology.gif" alt="2D tissue rheology" /> </td>
    </tr>
    <tr>
        <td><img data-src="images/ellipsoid.png" alt="Ellipsoid" /></td>
        <td><img data-src="images/organoid.png" alt="Organoid" /></td>
    </tr>
</table>


## Open questions

![](images/pseudo_strat_and_basalcomplex.png)

. . .

> There's still work to do!

# Force inference and model fitting

## 2D segementation

* Detection method
* Model reconstruction

> Pretty standard methods

## Force inference and model fitting

* Method
* First results

>

## Perspectives

* Towards 3D


# a tool for tissue engineering

##

* Microscopy data to models
* Models as virtual experiments
* Models as parameter spaces
