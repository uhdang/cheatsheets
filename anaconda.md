## Managing Packages
```
$ conda install [package_name]
$ conda remove [package_name]
$ conda update [package_name]
$ conda update --all
$ conda list
$ conda search *search_term*
$ conda env list

i.e.
$ conda install numpy=1.10 scipy pandas
$ conda search '*beautifulsoup*'
```


## Managing Environments
```
$ conda create -n [env_name] [list of packages]
$ source activate [env_name]  # Miniconda
or 
$ conda activate [env_name]  # Anaconda
$ source(conda) deactivate
$ conda list
$ conda install [package_name]

i.e.
$ conda create -n my_env numpy python=3
```

## More environment actions
```
* Save installed packages to YAML file
$ conda env export > enironment.yaml

* Create an environment from an environment file
$ conda env create -f environment.yaml

* List environments
$ conda env list

* Remove environments
$ conda env remove -n [env_name]
```

## Best Practices
