# MixedBirdSoundsDataset
The idea behind compiling overlapped bird sounds into a dataset stems from the fact that when we walk through a landscape, we hear a lot of mixed sounds made by different animals, birds, insects etc. We donot necessarily see them, but their sounds can be heard clearly. These mixed sounds can be analyzed using advanced deep learning techniques to identify bird species involved and then using this information to assess the biodiversity of the area. There exist bird sound datasets available online which consist of independent sounds of specific bird species. However, in realistic environmental recordings, bird calls of different species rarely occur independently, but instead they tend to overlap with each other. This dataset consists of overlapped recordings of the calls of 10 Indian bird species. It has been constructed using data augmentation techniques utilizing the natural environment recordings of these bird species.


## How to use

### Dataset_part1, Dataset_part2, Dataset_part3
Three chunks of the dataset, can be downloaded and combined to form the complete dataset of 13,160 recordings.

### labels.csv
Contains the class labels for each file that can be used for classifcation.

### Bird Species.txt
The label to species mapping.
