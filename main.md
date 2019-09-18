---
title: Tyssue, an epithelium modeling library
author: Guillaume Gay, Morphogénie Logiciels SAS
susbtitle: 3rd Workshop Biofabrication & Cancer
date: Montpellier, 25 September 2019
logo: images/logo.png
fontsize: 11pt
...


# Understanding epithelium mechanics at the cell level

## Epithelial morphogenesis

![Farhadifar et al. 2007](images/epithelium.png "Drosophila embryo ectoderm")

> Simple mechanics are often  enough

## Role of apoptosis in fold formation

![Gettings, Monier et al. 2015](images/leg_joint.png)


## Role of apoptosis in fold formation

<table>
    <tr>
        <td>Without AB force or propagation</td>
        <td>With AB force and propagation</td>
    </tr>
    <tr>
        <td><img data-src="images/fold_00_small.gif" alt="Without apical-basal force" /></td>
        <td><img data-src="images/fold_12_small.gif" alt="Without apical-basal force" /></td>
    </tr>
</table>

> Single cell processes interact with tissue level mechanisms


# The `tyssue` library

## Design and architecture

![](images/data_model.png)


> Modular design widens the range of applications

## A gallery

* Fold formation
* Mesoderm invagination
* Rheology
* Organoid

## Open questions

* Pseudo stratified
* Role of the ECM?
* Mesenchymal cells

> Still work to do to capture a lot of biology

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



# Tyssue

* Microscopy data to models
* Models as virtual experiments
* Models as parameter spaces
