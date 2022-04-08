# Introduction

This is a tool for the course Data Challenge 2, made by group 15.
The tool consists of a single Jupter Notebook, called `FINAL_NOTEBOOK.ipynb`. This tool was tested with the Greater Manchester Area policing data, the added statistical data was not available to the main author of the notebook at the time of publishing, this is thus untested. Therefore the created `pickle` file of this process was used for testing. However, the data should now be available via the Data folder specified in the technical report.

(Data storage: https://drive.google.com/drive/folders/1g9vBUoFBM4AHI1X_lwOVg6Xyj6NVSguh?usp=sharing)

# Dependencies

The program uses the following python libraries, the version at which the tool was written will be displayed in brackets e.g. `Python` (== 3.9.11)):

- `Pandas`    (==1.4.1)
- `Numpy`     (==1.22.3)
- `sklearn`   (==1.0.2)
- `k-means-constrained (no version implied)`
- `xgboost`   (==1.5.2)

If these are not available or are not up to date, it is suggested to create an environment with these versions for optimal use.

# How to run

Specify the correct paths for the dataset in the `Data` folder. If the is statistical data in excel sheets is provided, use these in the `Adding Extra Features` part of the the notebook, thus uncomment all the cells in this section so they will run, and change the `raw_data` command to `df.copy()` instead of loading the pickle. (CTRL+A, CTRL+/; in a cell, this should work best as there are extra comments) I'm sorry for the incovience to not test this thoroughly.

## note
Due to compatibility issues the data shader plots are omitted from the end result. As well as the visualizations that were created in the course, they are however still present in the archive of the GitHub repository.