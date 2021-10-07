## What it does
- Query the metadata of an ec2 instance within AWS and provide a json formatted output. 
- Retrieve the value of a particular data key.

## How to install
- [Create an EC2 Centos Linux instance on AWS]
- [SSH into the instance]
- Install Python 3 and git on your instance 
    - 'sudo yum install python3 git'
- Clone the git repo
- Install pipenv
  - 'sudo pip3 install pipenv'
- Open the repository on your instance using cd command
- Install project dependancies
  - 'pipenv install'


## How to run
- Open the 'src' folder
  - 'cd fetch-aws-instance-metadata/src'
- Run whichever script you need:
  - 'python3 get_metadata.py'
  - 'python3 get_key.py'
