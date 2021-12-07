### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the starter code for the "ND9991 - C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. This folder contains the following files:

### Files Description
#### infra.yml
CloudFormation code in this YAML template is for building the cloud infrastructure, as required for the project. 

#### servers.yml
CloudFormation code in this YAML template is for building the cloud servers as required for the project. 

#### infra-params.json
Contains parameter values for for `infra.yml` script


In YAML code, the `${EnvName}` would be substituted with `UdagramProject` accordingly. The same goes for other parameters in the file.

#### servers-params.json
Contains parameter values for for `servers.yml` script 

In YAML code, the `${EnvName}` would be substituted with `UdagramProject` accordingly. The same goes for other parameters in the file.

#### Server Specs

These are the specs for the EC2 instances used to run the Web App

- **Amazon Machine AMI:** Ubuntu Server 18.04 LTS (HVM), SSD Volume Type - ami-0279c3b3186e54acd (64-bit x86)

- **Instance Type**: t2.medium (vCPU=2, Memory=4GB)

- **Volume Size**: 15GB