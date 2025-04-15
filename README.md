# airlock
A management tool for python virtual environments  
__Note:__ currently only supports `osx` and `linux`

## Installation
To install `airlock`, clone this repo and run `make install`

This will install `airlock` to `/usr/local/bin`

## Usage
#### Quick Start
Once installed, just run `airlock` for usage instructions

#### Commands

__Note:__ the `select` command is to be used in conjunction with `source`. See command table below for example.

| Command | Arg(s) | Description | example |
| ------- | ------ | ----------- | ------- |
|  `init` | `env`  | initialize a new virtual env for management by airlock | `airlock init my-venv` |
| `select`| `env`  | select an airlock-managed virtual environment for use (note the usage of source) | `source airlock select my-venv` |
| `reset` | `env` | reset a virtual environment entirely | `airlock reset my-venv` |
| `clear` | N/A   | clear out all existing virtual environments managed by airlock | `airlock clear` |
| `list`  | N/A   | list all existing virtual environments managed by airlock | `airlock list` |
| `del`   | `env` | delete an existing virtual environment managed by airlock | `airlock del my-venv` |
| `help`  | N/A   | show usage | `airlock help` |
| `config-pip` | `env` `path/to/pip.config` | configure and airlock-managed virtual env with a pip config file | `airlock config-pip my-env /path/to/pip.conf` |

