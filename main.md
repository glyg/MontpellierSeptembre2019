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

$$ E = \sum_c \frac{K}{2}(A - A_0)^2 + \Gamma P^2 + \sum_{ij} \Lambda \ell_{ij} $$

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

> Modeling completes in vivo experiments


# The `tyssue` library

## Design and architecture

![](images/data_model.png)

. . .


> Modular design widens the range of applications

## Good practices

![](images/tyssue_gh.png)

. . .

> Open source, easy maintenance

## A gallery

![Gracia et al 2019](images/ellipsoid.png)

##


![Sophie Theis](images/fold_ellipsoid.gif){width=800}

##

![E. Moisdon & C. Gay](images/rheology.gif){width=600}


##

![E. Hannezo](images/organoid.png)

##

![](images/fails.png)

##

![](images/comp_silico_vivo.png)

# Force inference and model fitting


##

![](images/data2model.png)


## 2D segementation

![](images/segmentation.png)


## Force inference and model fitting

![F. Quinton](images/segmented.png)


. . .


> Actin / tension correlation



# Computer Assisted Tissue Engineering

## Perspectives

* Towards 3D with Julien Laussu


* Data enrichment with Deep learning


##

* Models as parameter spaces
* Models as virtual experiments


## Thank you!

:::::::::::::: {.columns}
::: {.column width="50%"}
* Sophie Theis
* Magali Suzanne & team
* Audrey Ferrand & team
* Florian Bugarin & team
:::
::: {.column width="50%"}
* Cyprien Gay
* Étienne Moisdon
* Édouard Hannezo
* Maxime Bouchard
:::
::::::::::::::
