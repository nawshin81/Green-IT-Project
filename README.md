# Green-IT-Project
A project to assess the accuracy of the energy and carbon estimation by CodeCarbon compared to the hardware power-meter measurements.


## Prerequisites

Your system needs to have Python installed to run the experiment. This document assumes the usage of Python 3

## Environment set-up

### Install Python3-tk

sudo apt-get install python3-tk

### Install virtualenv if it is not installed
pip3 install virtualenv

### Create a virtual environment in the current directory
virtualenv venv

## Activate the virtual environment
On macOS and Linux

source venv/bin/activate

pip install -r requirements.txt

python3 experiment-runner/code_carbon_accuracy_measurement/RunnerConfig-921f0e68-8c73-11ef-8a74-e6df4daffa1e.py

deactivate
