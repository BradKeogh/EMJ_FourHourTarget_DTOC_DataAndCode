# EMJ_FourHourTarget_DTOC_DataAndCode

This repository contains all data and analysis code used in the Emergency Medicine Journal (EMJ) paper publication: "The impact of Delayed Transfers of Care on Emergency Departments: common sense arguments, evidence and confounding" by authors B.Keogh & T.Monks. This paper completes a statistical analysis of the relationship between breaches of the four-hour emergency department target and numbers of reported patient delayed transfers of care within English hospitals. 

## Data
The data originates from open NHS England data which can be downloaded here: https://www.england.nhs.uk/statistics/

The specific data we have used in the study is provided data in csv format ('NHSE_data.csv').

## installing python
If are new to python then the easiest way to get up and running is to download
the anaconda distribution of python:
https://www.anaconda.com/download/

## Creating a python environment
Creating an environment should be the easiest way to ensure that you can run
our code sucessfully. To do this:
- navigate to your directory which should contain the downloaded files (.csv, .yml, .ipynb)
- open command prompt (terminal in mac)
- type: 'conda env create'
- type: 'activate DTOC' ('source activate DTOC' in mac)

## Running the script
- in command prompt type: 'jupyter notebook' (this will open in your browser)
- use the new browser window to open the 'AppendixA.ipynb' & 'AppendixB.ipynb' files
- from here you can use the drop down menu to run the entire script: 'Cell -> Run All'
- or you can re-run each cell individually using: Shift + Return
