# Data-augmentation-for-deep-ensembles-in-polyp-segmentation
Data augmentation for deep ensembles in polyp segmentation

Notice that in the chapter we have used all the images built by the data augmentation approaches, in further experiments we noticed that some artificial images contain only background pixels, this can be a problem with some loss functions.
To discard them we simply delete all the images where there are less than 10 pixels that belong to the class polyp.
All the datasets (training and test sets of the second testing protocoll) are available at:
https://zenodo.org/record/5579392#.YW8gAxpBw2w

