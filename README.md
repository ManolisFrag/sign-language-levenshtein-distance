# Levenshtein distance for sign language datasets

This repository contains two Jupyter notebooks to allow the calculation of Levenshtein distances between two sign language datasets.

[![Open Notebook 1 In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1OaYfsLkTOdgQ-BXaYJnmWs2H_twZKXgM?usp=sharing)

## Instructions

Before using the notebooks make sure that your excel files contain all the necessary information like here:

![Alt text](/pics/initial_file_format.png?raw=true "Title")

There is no limit on how many parameters your files can have but make sure that your annotations are consistent.

In the scripts you must specify which column contains the glosses and which columns contain the annotations.

### Prerequisites

You need to install the following python libraries in order to use the notebooks

```
pandas
csv
numpy
os
glob
```

## Usage

### Levenshtein distances for all signs
The notebook "Levenshtein_distances_all_signs.ipynb" will calculate how similar each gloss is in comparison to **all** the glosses of the second dataset. 

1.0 means that the signs are identical and 0.0 completely different. 

Its output will be like:

![Alt text](pics/all_signs_output.png?raw=true "Title")

### Levenshtein distances for same gloss signs
The notebook "Levenshtein_distances_only_same_glosses.ipynb" will calculate how similar each gloss is in comparison to **only the same glosses** of the second dataset. 

Its output will be like:

![Alt text](pics/same_glosses_output.png?raw=true "Title")

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.