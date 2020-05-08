# Advanced Financial Econometrics - Trinity Term 2020

## Course Website

You can find the [course website here](https://www.kevinsheppard.com/teaching/mfe/advanced-financial-econometrics-forecasting/).

## Pre-recorded Lectures

The prerecorded lectures are [available on YouTube](https://www.youtube.com/playlist?list=PLVR_rJLcetzmES8tqjgqlQw1Vx2IKMVot).

## Notebooks

The notebook illustrate the use of the forecasting methods detailed in the course.

## Data
The data files `assignment-data-train` contain the data for the assignment. 

You can load the data in the HDF5 file using

```python
import pandas as pd
data = pd.read_hdf("assignment-data-train.h5", "assignment_data")
```

You can load the data in MATLAB using `open("assignment-data-train.mat")`.

The `monthly-data` files contain the the full set of monthly series from the M4 dataset.
