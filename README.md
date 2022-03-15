# python-word-count-beam
## Checking the Python version
python --version

## Installing pip
pip --version

## Upgrade pip version
PS> python -m pip install --upgrade pip

## Creating a virtual environment
PS> python -m venv C:\path\to\directory

## Activating a virtual environment
PS> C:\path\to\directory\Scripts\activate.ps1

## Install the latest Python SDK from PyPI
PS> python -m pip install apache-beam

## Copy these files into your local
wordcount.py
sample.txt
## Executing the pipeline
python -m apache_beam.examples.wordcount --input /path/to/inputfile --output /path/to/write/counts

