# python-environment

## For Creating virtual environment and managing it

1. python3 -m venv modules ----- Create's a virtual environment inside moduules folder that stores it configuration packages and python dependencies
2. source modules/bin/activate ----- Activate's the virtual environment after that install packages using pip
3. deactivate ----- Deactivate's the virtual environment

## For Managaing python packages

1. pip freeze > requirements.txt ----- Create's a file called requirements.txt where all the packages with their version are shown this helps others to install the same version of a package.
2. pip install -r requirements.txt ----- Install's the package described in requirements.txt and updates bin inside modules as per that

## Run project

bash run.sh
