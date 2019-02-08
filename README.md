CHOP project template
-----------

### Requirements to use the cookiecutter template:
-----------
 - Python 2.7 or 3.5
 - [Cookiecutter Python package](http://cookiecutter.readthedocs.org/en/latest/installation.html) >= 1.4.0: This can be installed with pip by or conda depending on how you manage your Python packages:

``` bash
$ pip install cookiecutter
```

or

``` bash
$ conda config --add channels conda-forge
$ conda install cookiecutter
```

### To start a new project, run:
------------

    cookiecutter https://github.com/samesense/project-template

### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
/mnt/isilon/lab_dir/project/
├── .gitignore
├── README.md
├── configs
│   └── README.md
├── data
│   ├── EXPERIMENT.csv
│   ├── README.md
│   ├── endpoints
│   │   ├── MANIFEST.csv
│   ├── interim
│   ├── raw
│   │   ├── MANIFEST.csv
│   └── ref-data
├── models
│   └── README.md
├── notebooks
│   └── README.md
├── references
│   └── README.md
├── reports
│   ├── README.md
│   ├── figures
│   ├── log.md
│   ├── methods.md
│   └── tables
├── requirements
│   └── project_requirements.txt
└── src
    ├── README.md
    ├── rules
    ├── scripts
    └── tests
```
