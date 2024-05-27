## MLFlow tutorial

It is a tutorial for understanding MLFlow

### Setup project

1. First set up a environment of project. Create an folder of project.
   - setup environment with conda `conda create -p venv python==3.12 -y`.Creating a new environment allows you to isolate and manage dependencies for different projects or workflows. You can then install packages into this environment without affecting other environments or the system-wide Python installation.
   - activate environment. `conda activate venv/`
   - create a txt file in the project folder called `requirement.txt`
   - install mlflow with pip `pip install -r requirement.txt`. When add new dependencies, it should consider to use non-cache installation `cpip install --no-cache-dir -r requirement.txt`

### Deploy to dagshub

1. create an account and connect the repo about this project in github

### Run project

`python app.py`

#### Reference
