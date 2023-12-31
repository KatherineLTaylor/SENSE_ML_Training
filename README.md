[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jnhansen/sense_week2/master)

# SENSE Training Week 2

Welcome to week 2 of the SENSE CDT training.

During this week's practicals we will be looking at some regression, classification, and filtering examples, applied to Earth Observation data.

To get started, please clone this repository:

```
git clone https://github.com/jnhansen/sense_week2
```

This may take a moment because the repository includes a few sample data sets (~450MB).

Next, you should setup your anaconda environment.
If you already have an environment that you are working in
just make sure to have the following packages installed:
- `jupyter`
- `numpy`
- `xarray`
- `netcdf4`
- `matplotlib`
- `scikit-learn`

Alternatively, you can install a new environment using the provided environment configuration file:

```
conda env create -f environment.yml
```

Finally, activate your environment and launch jupyter notebook (make sure you are in the directory of this git repository).

On Linux and Mac:
```
conda activate sense
jupyter notebook
```
Note: Use `source activate sense` if your version of conda is < 4.4.


On Windows:
```
activate sense
jupyter notebook
```


---
## License


[![Creative Commons
License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
This work is licensed under a
[Creative Commons Attribution 4.0 International
License](http://creativecommons.org/licenses/by/4.0/).