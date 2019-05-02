## Sorter :
Is a program that classifies files, and determine which one are configuration files or not (in Linux).

### How-to-use:
To predict :
~~~~
python3 sorter.py -p "absolute/path/to/file"
~~~~
To fit a directory of configuration files :
~~~~
python3 sorter.py -f "absolute/path/to/directory"
~~~~ 

### Extractor:
A simple script to extract all configuration files stored in /etc  to prepare a big dataset for a classifier of categorizable texts 


### How-to-use:
~~~~
git clone && cd Extractor-Etc && sudo python3 extract.py
~~~~ 
