## Clone the repository
```
git clone https://github.com/AvisekNaug/VU_SmartCities.git
```

## Create the data directory
create a folder called "data" inside the VU_SmartCities folder

## Download the following files from "https://vanderbilt.app.box.com/folder/105397610826" into the created data folder
1. AH_Energy_Meter.csv
2. occupancyStatus.csv 


## Create a python environment at the terminal using

```
python36 -m venv energy_tutorial
```

## Activate the environment

### On linux or MacOS
```
source energy_tutorial/bin/activate
```
### On windows
source energy_tutorial\Scripts\activate

## Install requirements using
```
pip install requirements.txt
```

## Open notebook: Launch the notebook using
```
jupyter --notebook --port 8200
```
### Now you can type <127.0.0.1:8200>in your browser and interact with the notebook "Smart Cities Course Examples.ipynb"