# AWS Scripts
Our collection of scripts to ease automation of AWS interactions.

## Dependencies
- jq

  #### Installation
  ##### OS X
      brew install jq

  ##### Ubuntu
      sudo apt install jq

- aws cli

  #### Installation
  ##### Pip
      pip install awscli

## aws-iam-keys
- list-keys: List all access keys in the format "<username> <access key id> <status> <create date> <last used date>"
- disable-unused-keys: Disable all access keys which are Active but have never been used
