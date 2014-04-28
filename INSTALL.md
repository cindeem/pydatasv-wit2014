
#### we need a version of python with necessary packages
install anaconda
https://store.continuum.io/cshop/anaconda/

###Install dependencies with pip
#### We need the code to talk to Instagram
```bash
pip install python-instagram
```
#### we need this module to show how to index data
install ipythonblocks (pip install)
```bash
pip install ipythonblocks
```

### make your ipython notebook prett-ier
####create an ipython profile
```bash
ipython profile create pydata
```
#### find location of your profiles
```bash
ipython locate 
```
#### cd to the profile directory
eg
``` 
cd /Users/cindeem/.ipython/profile_pydata
```
#### make directory to hold our custom css
```bash
mkdir static
mkdir static/custom
```
#### copy custom.css from git repo to new directory
```bash
cp /path/to/gitrepo/pydatasv-wit2014/custom.css  /path/to/.ipython/profile_pydata/static/custom
```
#### start IPython
```bash
ipython notebook --profile pydata
```

