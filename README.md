
# Preparation

## 1. clone this repository

```bash
git clone https://gitlab.com/7labs.ru/tutorials-dvc/dvc-1-get-started.git
cd dvc-1-get-started
```

## 2. Create and activate virtual environment

```bash
virtualenv venv
source venv/bin/activate
```

## 3. Install python libraries (including dvc)

```bash
pip install -r requirements.txt
```

    
## 4. Сheckout to a new branch in demo repository 
(to not wipe content of master branch)

```bash
git checkout -b dvc-tutorial
``` 

## 5. Run and follow Jupyter Notebook `tutorial.ipynb` for instructions:

```bash
jupyter notebook
```



## (OPTIONAL) Setup Table of Content (toc) extension for JupyterLab

### Install NodeJS

* Linux (Debian/Ubuntu)

```bash
apt-get install -y curl python3-software-properties
curl -sL https://deb.nodesource.com/setup_12.x | bash -
apt-get install -y nodejs
``` 

* MacOS

```
https://treehouse.github.io/installation-guides/mac/node-mac.html
```

### Install `toc` extension
 
```bash
jupyter labextension install @jupyterlab/toc
```
    
