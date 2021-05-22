# 3D Artery Visualization

3D Artery visualization project was developed as a tool to compare 3D represenation and the novel 2D [CerebroVis](https://arxiv.org/pdf/1907.12663.pdf) representation.

See Live Demo: https://aditeyapandey.github.io/3DArteryVisualization/

![Screen Shot 2021-05-22 at 11 06 52 AM](https://user-images.githubusercontent.com/8208255/119231240-d47e6200-baed-11eb-839c-34a5fba4d56f.png)

3D Artery Visualization is built using [three.js](https://threejs.org/).

## Related Github Repos

CererbroVis: https://github.com/aditeyapandey/Cerebrovis

## How to Use With Your Own Data

To use 3D Artery Visualization, you will need the topology and anatomical properties cerebral arteries as a swc file. In this application, we have included, segemented scans from a public dataset. You can learn more about the segmentation process and access the public dataset on the [Brava](http://cng.gmu.edu/brava/home.php?s=1&name_browser=false) project website.

## Dataset Included
After you clone the repo, you can also locally use the dataset we have included in this repo.

path: data -> allscans -> `<foldername>` ->`<filename>`records.swc
  

## Interaction
 ![Screen Shot 2021-05-22 at 11 30 45 AM](https://user-images.githubusercontent.com/8208255/119231928-28d71100-baf1-11eb-9295-4c604776654c.png)
 
Radiologists often use tools that allows them to analyze a 3D brain scan with a set of interaction
techniques.

Conventional method is a scan from left to right along the center of the brain. Currently our visualization supports a left to right rotation.

However, you can stop the rotation, reverse its direction or rotate the scan in a step wise manner.


## Acknowledgements
