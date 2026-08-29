```
Project Architecture
_____________________

Arabic-Sentiment-Analysis/
│
├── src/
│   ├── data/
│   │   ├── __init__.py
│   │   ├── load.py
│   │   └── preprocess.py
│   │
│   ├── models/
│   │   ├── __init__.py
│   │   ├── architecture.py
│   │   └── train.py
│   │
│   ├── inference/
│   │   ├── __init__.py
│   │   └── predictor.py
│   │
│   └── config.py
│
├── api/
│   ├── __init__.py
│   ├── main.py
│   └── schemas.py
│
├── notebooks/
│   └── experiments/
│
├── tests/
│   ├── test_model.py
│   └── test_api.py
│
├── artifacts/
│   ├── models/
│   └── tokenizers/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── Dockerfile
├── pyproject.toml
├── uv.lock
├── .gitignore
├── README.md
└── .dockerignore
```
