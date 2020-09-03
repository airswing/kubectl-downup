# kubectl-downup
Reapply a yml and automatically generate helper scripts

## Features
`downup` will
- Automatically delete and apply a yaml file
- Get latest pod name based on app
- Use pod name to generate helper scripts (ex: logs, exec) to shortcut usage
- Every time `downup` is run, helper scripts will be regenerated

## Setup
Clone and `chmod +x downup`

## Usage
```
$ ./downup
$ ./logs
  logs.....
$ ./exec
  in container#
```
