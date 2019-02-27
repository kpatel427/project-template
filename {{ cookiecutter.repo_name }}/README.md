{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Abstract
-----------

Organization
------------
```
/mnt/isilon/{{cookiecutter.lab_dir}}/{{cookiecutter.project_name}}/
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
    ├── notebooks
    ├── rules
    ├── scripts
    └── tests
```
--------

## Help
Projects are version controlled, and on GitHub, the README.md can act as a project homepage. README.md should include a short project description/abstract, project members, and tags for experiment and organism.

<p><small>Project based on the <a target="_blank" href="https://github.com/samesense/project-template">CHOP project template</a>. #cookiecutterdatascience</small></p>
