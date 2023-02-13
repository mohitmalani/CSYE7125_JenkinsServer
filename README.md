# Building Jenkins AMI using Packer


The ami.json contains the instructions for building the AMI
RUN the below command to validate your AMI 
```
packer validate ami.json
```
To start building packer:
```
packer build -var-file='<PATH_TO VARIABLES_JSON_FILE>/vars.json' ami.json
```
or
```
packer build -var <variable>=<value> ami.json
```
