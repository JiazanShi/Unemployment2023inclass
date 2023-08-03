# Unemployment2023inclass


## Setup

Obtain an [AlphaVantage API Key](https://www.alphavantage.co/support/#api-key). A normal key should be fine, but alternatively you can use one of the prof's "premium" keys.

```sh
# this is the ".env" file (in the root directory of the repo)

ALPHAVANTAGE_API_KEY="____________"
```

Create a virtual environment:

```sh
conda create -n unemployment-env python=3.10
```

```sh
conda activate unemployment-env
```

Install third-party packages:

```sh
pip install -r requirements.txt
```

## Usage

Run the report:

```sh
python app/unemploy.py

python -m app.unemploy
```

## Testing

Run tests:

```sh
pytest
```
## Web App
Run the web app:

```sh
FLASK_APP=web_app flask run
```

