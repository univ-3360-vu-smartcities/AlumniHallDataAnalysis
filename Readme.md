# VU Smart Cities Course: Alumni Hall Energy Project
The demo Jupyter Notebook can be seen here [Alumni Hall Data Analysis Demo](https://github.com/univ-3360-vu-smartcities/AlumniHallDataAnalysis/blob/master/Alumni%20Hall%20Data%20Analysis%20Demo.ipynb)

# Steps to run the notebook

## 1 Clone the repository
```
git clone https://github.com/univ-3360-vu-smartcities/AlumniHallDataAnalysis.git
```

## 2 Create the data directory
create a folder called "data" inside the VU_SmartCities folder

## 3 Download the following files from [VU Box Folder](https://vanderbilt.app.box.com/folder/105397610826) into the created data folder
1. AH_Energy_Meter.csv
2. occupancyStatus.csv 


## 4 Create a virtual environment at the terminal using

```
python36 -m venv energy_tutorial
```

## 5 Activate the virtual environment

### On Linux or MacOS
```
source energy_tutorial/bin/activate
```
### On Windows
```
energy_tutorial\Scripts\activate
```
## 6 Install requirements using
```
pip install requirements.txt
```

## 7 Open notebook: Launch the notebook using
```
jupyter --notebook --port 8200
```
### Now you can type <127.0.0.1:8200>in your browser and interact with the notebook "Smart Cities Course Examples.ipynb"