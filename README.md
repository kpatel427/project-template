# Cookiecutter Data Science

_A logical, reasonably standardized, but flexible project structure for doing and sharing data science work._


#### [Project homepage](http://drivendata.github.io/cookiecutter-data-science/)


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

    cookiecutter https://github.com/drivendata/cookiecutter-data-science


[![asciicast](https://asciinema.org/a/9bgl5qh17wlop4xyxu9n9wr02.png)](https://asciinema.org/a/9bgl5qh17wlop4xyxu9n9wr02)


### The resulting directory structure
------------

The directory structure of your new project looks like this: 

```
├── .gitignore
├── README.md
├── configs
│   └── README.md
├── data
│   ├── README.md
│   ├── SAMPLES.csv
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

## Contributing

We welcome contributions! [See the docs for guidelines](https://drivendata.github.io/cookiecutter-data-science/#contributing).

### Installing development requirements
------------

    pip install -r requirements.txt

### Running the tests
------------

    py.test tests
