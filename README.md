# MultiModal Sentiment Analysis on Indian Languages

Implementation of Dense Fusion Network with
MultiModal Residual (DFMR) for native indian languages like Malayalam
by integrating multimodal information comprising of transcripts, videos and
audios for sentiment analysis. By utilizing various modalities, the goal is
to boost the precision and resilience of sentiment analysis models, thereby
mitigating biases and enhancing overall performance, particularly in intricate
or unclear scenarios.

For More Information, refer [docs](./docs/)

### Project Structure
```
MSA/
├── data/
│   ├── raw/                 # Raw, unprocessed data
│   ├── processed/           # Processed data ready for model training
│   ├── external/            # External data, such as pre-trained models or additional datasets
│   ├── interim/             # Intermediate data stages
│   └── README.md            # Documentation for data folder
│
├── notebooks/
│   ├── exploration/         # Notebooks for initial data exploration and visualization
│   ├── preprocessing/       # Notebooks for data preprocessing steps
│   ├── modeling/            # Notebooks for model training and evaluation
│   └── README.md            # Documentation for notebooks folder
│
├── src/
│   ├── data/                # Scripts to download or generate data
│   │   ├── make_dataset.py  # Script to make final dataset
│   ├── features/            # Scripts for feature engineering
│   │   ├── build_features.py # Script for building features
│   ├── models/              # Scripts to train models and make predictions
│   │   ├── train_model.py   # Script for training model
│   │   ├── predict_model.py # Script for making predictions
│   ├── visualization/       # Scripts for visualizations
│   │   ├── visualize.py     # Script for visualizing data and results
│   ├── utils/               # Utility scripts
│   └── README.md            # Documentation for src folder
│
├── reports/
│   ├── figures/             # Generated plots and figures
│   ├── results/             # Generated reports and result files
│   └── README.md            # Documentation for reports folder
│
├── models/                  # Trained models and model checkpoints
│   └── README.md            # Documentation for models folder
│
├── config/                  # Configuration files
│   ├── config.yaml          # Configuration file for the project
│   └── README.md            # Documentation for config folder
│
├── tests/                   # Unit tests and test scripts
│   ├── test_data.py         # Tests for data scripts
│   ├── test_features.py     # Tests for feature engineering scripts
│   ├── test_models.py       # Tests for model scripts
│   └── README.md            # Documentation for tests folder
│
├── scripts/                 # Standalone scripts for running the entire pipeline or specific tasks
│   ├── run_pipeline.sh      # Shell script to run the entire pipeline
│   └── README.md            # Documentation for scripts folder
│
├── logs/                    # Logs generated from running scripts and models
│   └── README.md            # Documentation for logs folder
│
├── environment.yml          # Conda environment file for dependencies
├── requirements.txt         # Pip requirements file for dependencies
├── README.md                # Main project documentation
└── .gitignore               # Git ignore file
```

### References
- [Dense Fusion Network with MultiModal Residual (DFMR)](https://ieeexplore.ieee.org/document/9428321)