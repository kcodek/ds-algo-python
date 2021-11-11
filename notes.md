#### Convert from python2 to python3
1. To translate a single file 
    `-w` flag: to enable writeback, which applies the changes to the file
    `-n` to disable backups
    `$ 2to3 -w -n SmallestWindow.py`
2. To translate an entire project from one directory tree to another use:
    `$ 2to3 --output-dir=python3-version/mycode -W -n python2-version/mycode`
    

#### References
1. https://docs.python.org/3/library/2to3.html