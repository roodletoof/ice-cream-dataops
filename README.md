# bootcamp-cdm
This is notes for myself for anything I did that goes outside the tutorial.

# Pushing data to CDF
Before running `cdf-tk deploy` I have to delete the cdf groups that have scoped
permissions via the Admin tab in Cognite Fusion.
This is due to some bug ¯\_(ツ)_/¯

# Setup

## MacOS
Poetry did not work for me, so I am using the venv method.

Make sure the we have the correct python version.
```zsh
brew install python@3.11
```
Or install it via pyenv as shown in the
[tutorial](https://docs.cdf-bootcamp.cogniteapp.com/content/data_foundation/setup_the_cdf_toolkit/#install-cdf-toolkit).

Create a virtual environment for python3.11, activate it and install the
requirements.
```zsh
python3.11 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

Fill out the .env file according to the
[tutorial](https://docs.cdf-bootcamp.cogniteapp.com/content/data_foundation/cdf_toolkit_modules/#configure-test-environment-configuration-file).
