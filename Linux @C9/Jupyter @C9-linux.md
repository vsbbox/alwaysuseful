## How to install 'Jupyter Notebook' in Cloud9

### Installing miniconda
    1. bash wget "https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh"
    2. bash chmod a+x Miniconda3-latest-Linux-x86_64.sh
    3. bash ./Miniconda3-latest-Linux-x86_64.sh

### Installing Jupyter
    1. bash conda install jupyter
    2. bash jupyter notebook --ip=0.0.0.0 --port=8080 --no-browser

### Creating alias
    1. bash cd ~/
    2. bash nano .bash_aliases
    3. bash alias jupyter='jupyter notebook --ip=0.0.0.0 --port=8080 --no-browser'
    4. ^X 
        "to exit"
    5. Y 
        "save the file"
    6. Enter
        "back terminal"
    7. exec bash
        "Reload bash"