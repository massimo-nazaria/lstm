# Predicting the Accuracy of Early-est Earthquake Magnitude Estimates with an LSTM Neural Network: A Preliminary Analysis

**Paper:** [https://arxiv.org/abs/2104.05712](https://arxiv.org/abs/2104.05712)

**Jupyter Notebook:** [LSTM.ipynb](LSTM.ipynb)


## How to run the notebook

*The following commands were tested on recent versions of Ubuntu Linux and can be applied to other systems provided that the indicated packages are installed.*

### 1) Install pip and venv packages

```
sudo apt-get install python3-pip
sudo apt-get install python3-venv
```

### 2) Download the repository with the notebook

```
git clone https://github.com/massimo-nazaria/lstm.git
```

### 3) Create a virtual environment in the downloaded folder `lstm`

```
cd lstm/
python3 -m venv env
```

### 4) Activate the virtual environment

```
source env/bin/activate
```

### 5) Upgrade pip

```
pip install --upgrade pip
```

### 6) Install the required packages via pip

```
pip install -r requirements.txt
```

### 7) Launch the notebook

```
jupyter notebook LSTM.ipynb
```

## Useful readings

* [What is pip](https://realpython.com/what-is-pip/)
* [Python Virtual Environments](https://realpython.com/python-virtual-environments-a-primer/)
* [Jupyter Notebook Introduction](https://realpython.com/jupyter-notebook-introduction/)
* [Keras Overview](https://www.tensorflow.org/guide/keras/overview)
* [LSTM Example](https://www.tensorflow.org/tutorials/structured_data/time_series)
