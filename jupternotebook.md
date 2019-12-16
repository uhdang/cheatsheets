## Installing Jupyter Notebook
```
(in virtual env)
$ conda install jupyter notebook
or
$ pip install jupyter notebook
```

## Launching the notebook server
```
$ jupyter notebook

* Install Notebook Conda - manage conda environment from notebook
$ conda install nb_conda
```

## Magic keyWords

```
* Timing code
$ %timeit       # measure how long a function runs
$ %%timeit      # measure how long a whole cell runs
```

```
* Embedding visualizations in notebooks
$ %matplotlib

i.e. %metplotlib inline
```


```
* Debugging in the Notebook
%pdb
```

## Converting notebooks
```
$ jupyter nbconvert --to [FORMAT] [filename.ipynb]

i.e.
$ jupyter nbconvert --to html notebook.ipyb
```

## Creating a slideshow
```
* Running the slideshow
$ jupyter nbconvert notebook.ipynb --to slides

* Convert and immediately see
$ jupyter nbconvert notebook.ipynb --to slides --post serve
```





