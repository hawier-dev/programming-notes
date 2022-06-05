# Load data from a text file.

### 🔵  Using Numpy
```python
import numpy
file_data = numpy.loadtxt('file.txt', dtype=str, delimiter='seperator', comments='#')
```

### 🔵  Using base Python
``` python
data = []
with open('file.txt', 'r') as file:
	for line in file:
		data.append(line.rstrip().split('seperator'))
```

### 🔵  Using Pandas
``` python
import pandas
file_data = pandas.read_csv('file.txt', sep='seperator')
```

# Load data from json.

### 🔵  Using json
``` python
import json
file = open('file.json')
file_data = json.load(file)
file.close()
```

### 🔵  Using Pandas
``` python
import pandas
file_data = pandas.read_json('file.json')
```
