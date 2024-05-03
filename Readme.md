# EEG Visualization

Based extensively on [MIT Flower](https://github.com/NeoVand/Flower2)

## Installation

```shell
python -m venv env
source env/bin/activate
pip install -r requirements.txt
```

## Usage

```shell
python app.py
```

The UI will be available at `localhost:5000`.

Currently, the app is configured to support embeddings from our GNN model.
It was made with the original intent of taking an composed signals and visualizing them through ICA, that functionality can be restored by following instructions in TODOs (hopefully will be added as an option).

