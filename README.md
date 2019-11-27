# snapshot-analyzer
Demo project to manage snapshots of AWS EC2 Instances

# About
This project is a demo and uses boto3 to manage AWS EC2 instance snapshots

# Configuring
snapshotanalyzer uses the configuration file created by AWS CLI. e.g:

`aws configure --profile snapshotanalyzer`

# Running

`pipenv run python snapshotanalyzer_profile/snapshotanalyzer.py`
