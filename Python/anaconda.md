## Anaconda

##### 🔵  Environments info.

**List environments.**
```
conda env list
```

**List packages in environment.**
```
conda list
```


##### 🔵  Create new environment.

**Create new environment.**
```
conda create --name env_name python=3.7
```

**Activate this environment.**
```
conda activate env_name
```

**Create the environment from requirements.txt**
```
conda create --name env_name --file requirements.txt
```

**Create the environment from environment.yml**
```
conda env create --file environment.yml
```

##### 🔵  Remove environment.

**Remove the environment.**
```
conda remove --name env_name --all
```

**Deactivate the active environment.**
```
conda deactivate
```

##### 🔵  Export the environment to a file. 

**Create Anaconda requirements file.**
```
conda list -e > requirements.txt
```

**Export active environment to a file.**
```
conda env export > environment.yml
```
