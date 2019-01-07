# Swire Dataset and Application Notebooks

This repository contains instructions to access to Swire dataset, and notebooks for applications described in Swire.

## Dataset

Please download the dataset from [here](https://storage.googleapis.com/crowdstf-rico-uiuc-4540/swire_dataset_v0.1/sketches.zip).
You should be able to obtain the sketches after unzipping the downloaded zip file. The dataset is named with the convention: 
```
<ui_id>_<sketcher_id>.jpg
```
Where the ui_id corresponds to the ids from the [Rico](http://interactionmining.org/rico) dataset, and sketcher_id are anonymized ids of the creators of the sketches from 1-4.

Please note that the image files of the sketches are inverted greyscale files (to better fit of purpose of training neural networks), such that artist strokes are denoted by values towards white, and background are denoted by values towards black. 

## UI Application Code

Please see the file [sketch_applications.ipynb](sketch_applications.ipynb) for details.

## Paper
Coming soon.

