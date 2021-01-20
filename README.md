# bootstrap- econometrics
Simple bootstrap function in Python. It resample data and plot a graph with median and mean line.

## Plot original distribuition and resampled distribution
Blue: Original data
Red: Resampled data

```python 
Bootstrap(serie_dados,graph=True)
```

<img src="boot_plot.png" width="50%" height="50%">


## Return mean, standard deviation and error form original and resampled data
```python 
Bootstrap(serie_dados,stats=True)
```
<img src="stats.png" width="50%" height="50%">


## Return resampled data as a list
```python 
new_series=Bootstrap(serie_dados,serie=True)
```
<img src="serie.png" width="20%" height="20%">


## To Do:
* Improve graph options
* Write comments and parameters properly
* Any sugestions?
