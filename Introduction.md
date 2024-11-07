# Python 

### Make a venv environment 
- when you install new package then install in venv environment
## conda create -p venv python==3.12
- The command conda create -p venv python==3.12 is used to create a virtual environment with a specified version of Python

```bash
A virtual environment is an isolated environment where you can install packages and 
libraries separately from the global or system-wide Python installation. 
This isolation allows you to manage dependencies for each project independently, 
preventing conflicts between packages required by different projects.

Virtual environments are especially useful when you work on multiple projects 
that may need different versions of the same library or even different Python versions.
```
## Activate the virtual environment
- conda activate venv/

##### when ever we need to install package so write in requirements.txt and in venv environment install 
- pip install -r requirements.txt

### if you want to work in jupiter notebook then you need some requirements.txt
- .ipynb jupiter Notebook  file
  
## To run the juptier Notebook install some important packages 
- 1. pip install ipykernel 

# Different way of install the virtual environment
- to make a differnet - 2 venv for different projects 

## First way to install venv with python
- python -m venv myenv  (myenv is my folder name where venv is installed)
### using these command myenv name folder automaticlly create 
- inside the myenv  Script/activate 
- so activate this just writing the path only 
- then install any package pip install numpy 

# Other way to install the package
- direct in cmd run the following command 
##### pip install virtualenv

- then run the command 
- virtualenv -p python virtual_env (virtual_env folder will be automatically created and inside the virtualenv folder or environment installation )

- then activate the virtual_env
### How to activate the virtual_env
- virtual_env/Scripts/activate (then automatically activate the virtual_env)

### Third way to install the virtual environment
- using conda create -p venv

## To activate this environment, use

- conda activate /home/sumit/Documents/complete-python-course/venv

- To deactivate an active environment, use
- conda deactivate