# kubectl-downup
Reapply a yml and automatically generate helper scripts

## Features
`downup` will
- Automatically delete and apply a yaml file
- Get app name from YAML
- Get latest pod name based on app
- Get all container names
- Use pod name to generate helper scripts (ex: logs, exec) to shortcut usage
- Every time `downup` is run, helper scripts will be regenerated

## Setup
Clone and `chmod +x downup`

## Usage
```
$ ./downup deploy.yaml
$ ./logs-container-name-1
  logs.....
$ ./exec-container-name-2
  in container#
```
