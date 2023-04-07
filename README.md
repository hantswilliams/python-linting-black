# python-linting-black

## packages: 
- black 
- safety 
- pip-audit 

## instructions: 
- https://black.readthedocs.io/en/stable/usage_and_configuration/the_basics.html 

## simple BLACK tutorial 
-- install, ```pip install black` 
- we have 1: poorly lited python file called: `poorPythonfile.py` 
- in order to run, then need to call `black` or `python black` from the terminal command line 
- if we want to do directory, just ./ select the directory 
- if we want to see the changes, can add argument: ```--diff``` to the end 
    - as an example here: ```black ./directory --diff```

## simple SAFETY tutorial 
- install, ```pip install safety` 
- test: ```safety check --key <your_api_key> ```
- want to use this, is to have it just look at a specific requirements.txt file 
    - ```safety check -r <path-to-requirements-file> --key <YOUR-API-KEY>```
- saving output: 
    - v1: ```safety check -r <YOUR-REQUIREMENTS.TXT> --key <YOUR-API-KEY> --output screen > securityCheck.txt```
    - v2: ```safety check -r <YOUR-REQUIREMENTS.TXT> --key <YOUR-API-KEY> --output json > securityCheck.json```