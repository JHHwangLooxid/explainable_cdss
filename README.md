# Explainable CDSS implementation



## Installation of virtual environment(optional)

Use python version 3.6.4.

```bash
pyenv virtualenv 3.6.4 cdss_test
pyenv activate cdss_test
```

## Installation of required python packages

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install packages.

```bash
pip install -r requirements.txt
```

## Usage

```bash
python main.py
```

Key binding
- tilde: Start visualizing
- q: End program
- Enter: Confirm the AI prediction
- Del + 0~4 + Enter: Reannotate
- Left/Right: Move along epochs
- Up/Down: EEG Scaling
- F: Show the current epoch
- I/O: Zoom in/out
- N + epoch#: Jump to the specific epoch

## Change the settings
In 'exp_setting/config_user#.json' file, you can change the paths of files, channels and number of epochs.
