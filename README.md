# ds3_excercise


## Environment Setup


### Python Installation Recommended
```bash
wget https://www.python.org/ftp/python/3.7.9/Python-3.7.9.tgz
tar xvfz Python-3.7.9.tgz
Python-3.7.9/configure
make
sudo make install
sudo apt-get install python-pip
```

### My Approach

```bash
conda create -n adp python=3.79
sudo apt-get install python3-pip
```

### ADP Package Installation
```bash
pip install scikit-learn==0.23.2
pip install seaborn==0.9.0
pip install matplotlib==3.0.3
pip install pandas==1.1.2
pip install imblearn==0
pip install pyjanitor
pip install pymc3
pip install statsmodels==0.13.2
```

#### 호환성 문제로 아래 추가
```bash
pip install imbalanced-learn==0.7.0
conda install -c anaconda netcdf4
```

### VS Code Setup @ conda 가상환경에서

```bash
conda install -n adp ipykernel --update-deps --force-reinstall
pip install --upgrade jupyter_client
```