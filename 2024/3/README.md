# Swazure: Swarm Measurement of Pose for Flying Light Specks

**Author:** Hamed Alimohammadzadeh, Shahram Ghandeharizadeh

[PDF](./Swazure.pdf)

The Second International Conference on Holodecks, December 19 2024, Pages 17-25, https://doi.org/10.61981/ZFSH2403

Published:  19 December 2024

# Abstract
One may construct a 3D multimedia display using miniature drones configured with light sources, Flying Light Specks (FLSs).  Swarms of FLSs localize to illuminate complex 3D shapes and animated sequences consistent with the coordinates of points in a point cloud.  This requires FLSs to accurately measure their pose relative to one another using sensors such as cameras. Such sensors have a sweet range in which they provide the highest accuracy.  A challenge is how an FLS tracks another FLS outside its sensor's sweet range, dictated by the point cloud data We address this challenge by proposing a novel technique called Swazure that solves the missing sensor data using cooperation among FLSs.  It implements {\em physical data independence} by abstracting the physical characteristics of the sensors, making point cloud data independent of the sensor hardware.  The size of an FLS relative to the minimum distance between points of a point cloud is an important parameter. With medium-sized FLSs, Swazure is able to position 100% of the FLS's neighbors. Larger FLS sizes may result in potential obstructions that prevent Swazure from quantifying relative pose. We present two heuristics, Move Obstructing and Move Source, to address this limitation.  Our experimental results show the superiority of the Move Obstructing heuristic which resolves approximately 30% of obstructions in the worst case scenario. 

# Citation

1. Hamed Alimohammadzadeh and Shahram Ghandeharizadeh.  Swazure: Swarm Measurement of Pose for Flying Light Specks.  In the Proceedings of the Second International Conference on Holodecks (Holodecks '24), December 19 2024, Los Angeles, California, USA, 17-25.  https://doi.org/10.61981/ZFSH2403

BibTex:
```
@inproceedings{10.61981/ZFSH2403,
author = {Alimohammadzadeh, Hamed and Ghandeharizadeh, Shahram},
title = {{Swazure: Swarm Measurement of Pose for Flying Light Specks}},
year = {2024}, 
publisher = {Mitra LLC}, 
address = {Los Angeles, CA, USA}, 
url = {https://doi.org/10.61981/ZFSH2403}, 
doi = {10.61981/ZFSH2403}, 
abstract = {One may construct a 3D multimedia display using miniature drones configured with light sources, Flying Light Specks (FLSs).  Swarms of FLSs localize to illuminate complex 3D shapes and animated sequences consistent with the coordinates of points in a point cloud.  This requires FLSs to accurately measure their pose relative to one another using sensors such as cameras. Such sensors have a sweet range in which they provide the highest accuracy.  A challenge is how an FLS tracks another FLS outside its sensor's sweet range, dictated by the point cloud data We address this challenge by proposing a novel technique called Swazure that solves the missing sensor data using cooperation among FLSs.  It implements {\em physical data independence} by abstracting the physical characteristics of the sensors, making point cloud data independent of the sensor hardware.  The size of an FLS relative to the minimum distance between points of a point cloud is an important parameter. With medium-sized FLSs, Swazure is able to position 100% of the FLS's neighbors. Larger FLS sizes may result in potential obstructions that prevent Swazure from quantifying relative pose. We present two heuristics, Move Obstructing and Move Source, to address this limitation.  Our experimental results show the superiority of the Move Obstructing heuristic which resolves approximately 30% of obstructions in the worst case scenario.},
booktitle = {The Second International Conference on Holodecks}, 
numpages = {8}, 
pages = {17--25},
location = {Los Angeles, California}, 
series = {Holodecks '24} 
}
```
