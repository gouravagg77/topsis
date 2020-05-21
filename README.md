# Topsis Package
A Python package to implement topsis on a given dataset.
TOPSIS is an algorithm to determine the best choice out of candidates available in your dataset.

## Usage
Following query on terminal will provide you the best and worst decisions for the dataset.
```
python <your-file-name> <your-dataset-name.csv> <weight array>("w1,w2,w3,w4,...") <impact array>("i1,i2,i3,i4,...")
```
Example-
```
python topsis.py dataset_sample.csv 1,1,1,1 0,1,1,0
```

### Usefull Links-
Mathematics for TOPSIS - https://www.youtube.com/watch?v=aRBdrCB1K4k
