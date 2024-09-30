# Prowler Workshop

[Prowler Workshop](https://docs.google.com/presentation/d/1ar3M_ivwKJDviHea2u7qqNmhs1K6NH9Ktq3Cg8i6oI8/edit?usp=sharing)

## History
- Prowler was the first song on the first Iron Maiden album
- Each release follows an Iron Maiden song

## Report Formats Supported
- json
- csv
- ocsf (default format)

## Installation Recommendatoins
- ```pipx install prowler```
- ```pipx upgrade prowler```

## Usage
- ```prowler <provider> -f <region>```
- ```prowler aws -f us-east-1```
- ```prowler aws --status FAIL --severity critical```
- ```prowler dashboard``` #Prowler dashboard to review all findings
- ```prowler aws --categories encryption```
- ```prowler aws --list-categories```
- ```prowler aws --category threat-detection```
- ```prowler aws -c <name of check>``` #Run a single check
