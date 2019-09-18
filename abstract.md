Tyssue: from an open-source epithelium modeling library to a tissue
engineering CAD software

Guillaume Gay,

Morphogénie Logiciels SAS,

lieu dit Maquet,

32110 St Martin d'Armagnac

Abstract

In this talk, I will present the `tyssue` library, used to model
epithelium at the cell level.

`tyssue` was first designed to understand how single cell behaviors interact with tissue level mechanisms to shape an epithelium. Our initial focus was the description of the apical mesh-work of a columnar epithelium to show how apoptotic cells actively contribute to fold formation. From this issue, the library has evolved to encompass multiple geometries and physical engines.

Drosophila imaginal disks and colon organoids share many traits, for example, the interaction between the actin cytoskeleton and the adhesion complexes are among the key actors of morphogenesis. It is thus natural to adapt the methods and models used to study morphogenesis in drosophila to organoids.

Such model can then be used as standalone tool used to examine key dynamical aspects of the epithelium self-renewal dynamics and their mechanical consequences. But it can also be *integrated* in the biologists tool-chain. We will discuss how image segmentation and force inference strategies can be used to automate information extraction from 3D fluorescence and phase contrast images. This data can then feed 3D dynamical models of the organoid, which bring many benefits, stemming from the much compact (memory efficient) and explicit data representation. I will show how tyssue is used with this objective.
