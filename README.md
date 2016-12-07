# Alfred_Workflows
## Environment (on Mac 10.13)
* Notice: Python version is 2.7
* If "Permission denied" when pip-installing, try to use "pip install --user"
### 1. install PyObjC:
> xcode-select --install
> pip install -U pyobjc
### 2. install PIL
> pip install pillow
* Notice: Should not have 'PIL' in pip list
### 3. install zbar
> brew update && brew upgrade && brew install zbar
> download: https://github.com/npinchot/zbar and then unzip
> cd into the dir, then python setup.py install (also can use "--user")
### 4. install qrtools
> pip install qrtools
