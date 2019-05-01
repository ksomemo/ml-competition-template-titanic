# ml-competition-template-titanic
## Requirements
- Python
- `pip install cookiecutter`

## references
- <https://github.com/uberwach/cookiecutter-kaggle/README.md>
- <https://github.com/upura/ml-competition-template-titanic>

## structure
```
{{\ cookiecutter.repo_name\ }}
├── LICENSE
├── README.md
├── configs
│   └── default.json
├── data
│   ├── input
│   └── output
├── features
│   ├── __init__.py
│   ├── base.py
│   ├── create.py
│   └── importances
├── logs
│   └── logger.py
├── models
│   └── lgbm.py
├── notebooks
│   └── eda.ipynb
├── run.py
├── scripts
│   └── convert_to_feather.py
├── tox.ini
└── utils
    └── __init__.py
```

