#### Convert from python2 to python3
1. To translate a single file 
    `-w` : to enable write back, which applies the changes to the file
    `-n` : to disable backups
    - e.g. - `$ python src/chapter15stringalgorithms/SmallestWindow.py`

2. To translate an entire project from one directory tree to another use:
    `$ 2to3 --output-dir=python3-version/mycode -W -n python2-version/mycode`
     - e.g. -  $ 2to3 --output-dir=./src/chapter01introduction/ -W -n ./src/chapter01introduction/ 

#### References
1. https://docs.python.org/3/library/2to3.html