# Semantic-Segmentation-of-Hyperspectral-Images

This dataset comprises cloud masks for 513 1022-by-1022 pixel subscenes, at 20m resolution, sampled random from the 2018 Level-1C Sentinel-2 archive.
### You can find the dataset [here](https://zenodo.org/record/4172871#.ZBqL8XZBxD-)

The Notebook use UNet Model to perform Semantic Segmentation using K-fold cross validation Technique.

![image](https://user-images.githubusercontent.com/86932331/226808269-a7e93bed-05b7-404a-bb16-43acc1612171.png)

To enhance the quality of model, the concept of tiling images with a sufficient overlap is used. Finally The model was converted to **ONNX** format for smooth deployment.

