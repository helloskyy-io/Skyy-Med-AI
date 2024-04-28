skyy-net
│
├── notebooks/                 # Jupyter notebooks for exploration and presentations
│   ├── exploratory/           # Initial exploratory data analysis
│   │   └── data_exploration.ipynb
│   ├── models/                # Model development and training notebooks
│   │   ├── model_v1.ipynb
│   │   └── model_v2.ipynb
│   └── reports/               # Notebooks for reports and visualizations
│       └── performance_evaluation.ipynb
│
├── src/                       # Source code for use in this project
│   ├── __init__.py            # Makes src a Python module
│   ├── data/                  # Scripts to download or generate data
│   │   └── data_loader.py
│   ├── features/              # Scripts to turn raw data into features for modeling
│   │   └── build_features.py
│   ├── models/                # Scripts to train models and then use trained models to make predictions
│   │   ├── train_model.py
│   │   └── predict_model.py
│   └── visualization/         # Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
├── models/                    # Trained and serialized models, model predictions, or model summaries
│   ├── model_v1.pkl           # Serialized model file
│   └── model_v2.pkl
│
├── data/                      # Data used for analysis
│   ├── raw/                   # Immutable, original data dumps
│   ├── processed/             # Cleaned data sets
│   └── external/              # Data from third party sources
│
├── docs/                      # A default Sphinx project; see sphinx-doc.org for details
│   ├── conf.py
│   ├── index.rst
│   └── ...
│
├── tests/                     # Test cases for the application
│   ├── __init__.py
│   ├── test_data.py
│   ├── test_features.py
│   ├── test_models.py
│   └── test_visualization.py
│
├── requirements.txt           # The requirements file for reproducing the analysis environment, e.g.
│                              # generated with `pip freeze > requirements.txt`
├── setup.py                   # makes project pip installable (pip install -e .) so src can be imported
├── Dockerfile                 # Dockerfile for building container environments
├── .gitignore                 # Specifies intentionally untracked files to ignore
└── README.md                  # The top-level README for developers using this project
