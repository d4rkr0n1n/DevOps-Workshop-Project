# DevOps-Worksop-Project

## Contents

## Prerequisites

### Install eksctl,helm and awscli using package managers

#### MacOS & Linux Users

- Install homebrew from [here](https://brew.sh/)
- Run command:
  - `brew install eksctl`
  - `brew install helm`
  - `brew install awscli`
  - `brew install kubectl`

#### Windows Users

- Install chocolatey from [here](https://docs.chocolatey.org/en-us/choco/setup#installing-chocolatey-cli)
- Run command:
  - `choco install eksctl`
  - `choco install kubernetes-helm`
  - `choco install awscli`
  - `choco install kubernetes-cli`

### Create AWS IAM User with admin priviledges

- Create AWS account
- Create an IAM User
- Create access key in Security Credentials, select the use-case as CLI, for that User
- Download the CSV (**keep it safe**).
- Run command: `aws configure`
- Enter `AWS Access Key ID` and `AWS Secret Access Key` from the CSV
- Enter the default region
- Enter the output format (*json is preffered*)
