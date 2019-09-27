# shots

Small project to experiment with automaking AWS EC2 snapshots

## About

Uses boto3 to manange AWS EC2 instance snapshots

## Configuring

shots uses config file created by AWS CLI e.g.:

`aws configure --profile shots`

## Running

`pipenv run python shot/shot.py <command> <--project=PROJECT>"`

_command_ is list, start, or stop
_project_ is optional
