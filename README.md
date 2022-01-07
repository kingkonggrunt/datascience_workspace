# DATASCIENCE WORKSPACE
An alternative to anaconda as I have gotten use to `venv` and the workflow of using
`pip freeze > requirements.txt` and `pip install -r requirements.txt`    

#### Next Steps
- Setting up jupyter notebook/jupyter lab
- Setting Up Working Git Submodules for individual projects (and possibily their own `venv` setup and requirements)


### What's inside
- A `requirements.txt` file containing all the pip packages required to do data science work. Use this as a baseline when starting out on a new data science project

##### Notes
- Sometimes `pip freeze` returns `@file://` urls for packages. `pip list --format=freeze > requirements.txt` works.
