# sst-examples
Examples on how to use Subsurface Toolbox packages in workflows. Each example is located in a folder that contain a Jupyter Notebook and a subfolder with any resources/data if applicable. 

## How to run the examples
This repository can best be used with the [Pixi](https://prefix.dev/) package manager:

With pixi installed, navigate to the folder of the cloned repository and run the following to install all dependencies required for the various examples:

    pixi install


## Examples index
**predict_sand_thickness** 
> Demonstrates the use of [GeoST](https://pypi.org/project/geost/) 

Example of using GeoST in combination with scikit-learn to use borehole data in conjunction with elevation, geological map and geomorphological map data to train a gradient boost regressor that is capable of predicting the total thickness of sand within the first 4 m below the surface in a complex area of channel belts and floodplains.

