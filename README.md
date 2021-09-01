# Levenshtein distance for sign language datasets

This repository contains two Jupyter notebooks to allow the calculation of Levenshtein distances between two sign language datasets.

## Instructions

Before using the notebooks make sure that your excel files contain all the necessary information.
![Alt text](/pics/initial_file_format.png?raw=true "Title")

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
The notebook "Levenshtein_distances_all_signs.ipynb" will calculate how similar each gloss is in comparison to all the glosses of the second dataset. Its output will be like:
![Alt text](pics/all_signs_output.png?raw=true "Title")

### Levenshtein distances for same gloss signs
The notebook "Levenshtein_distances_only_same_glosses.ipynb" will calculate how similar each gloss is in comparison to only the same glosses of the second dataset. Its output will be like:
![Alt text](pics/same_glosses_output.png?raw=true "Title")

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)