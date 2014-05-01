
#### You will need a version of python with necessary packages
install anaconda
https://store.continuum.io/cshop/anaconda/

###Install dependencies with pip
(pip is installed with anaconda)

#### We need the code to talk to Instagram
```bash
pip install python-instagram
```
#### Install ipythonblocks

We need this module to use ipythonblocks to show examples of indexing

install ipythonblocks (pip install)

```bash
pip install ipythonblocks
```

You will need to make a directory and grab the workshop materials from github

https://github.com/cindeem/pydatasv-wit2014/

```bash
git clone https://github.com/cindeem/pydatasv-wit2014/
```

Alternatively, you can grab the workbooks through wakari

	https://www.wakari.io/sharing/bundle/rgrrl/pydata_wit2014

	You can also create a wakari.io account, and run the notebooks in wakari


#### Start IPython
If you are running this on your machine, after installing all the dependencies and downloading the workshop materials, you can then start playing with the notebooks

ipython is installed with anaconda. You need to be in the directory where you saved the ipython notebooks (*.ipynb). When you start ipython notebook, it will open a web browser and you will have access to your notebooks

```bash
ipython notebook 
```

### make your ipython notebook prettier (optional)

	* create an ipython profile

	```bash
	ipython profile create pydata
	```
	
	* find location of your profiles
	
	```bash
	ipython locate 
	```
	
	* cd to the profile directory
		``` 
		cd /Users/<username>/.ipython/profile_pydata
		```
	* make directory to hold our custom css
		```bash
		mkdir static
		mkdir static/custom
		```
	* copy custom.css from git repo to new directory
		```bash
		cp /path/to/gitrepo/pydatasv-wit2014/custom.css  /<userdir>/.ipython/profile_pydata/static/custom
		```
	
	### Start IPython with the nice profile you just created

	```bash
	ipython notebook --profile pydata
	```


