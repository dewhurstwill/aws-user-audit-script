# Account Audit Script

## Prerequisites
- [Python 3](https://www.python.org/downloads/)
- [pip](https://www.w3schools.com/python/python_pip.asp)
- [awscli](https://aws.amazon.com/cli/)

## Installation and Usage

Install Pipenv. Instructions to install can be found [here](https://pipenv.pypa.io/en/latest/)

Launch the script by running `pipenv run python main.py` in it's installed directory.

This script uses the AWS boto3 SDK, information on how to configure credentials for use with boto can be found [here](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/quickstart.html#configuration)

This script ouputs the below to the working dir:
- console-access-audit.csv
- programmatic-access-audit.csv
