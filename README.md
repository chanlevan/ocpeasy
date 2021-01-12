# OCPeasy - Command Line Interface

## Introduction

OCPeasy consists in a CLI to facilitate the deployment of OpenShift applications, generating the configuration based on your project requirements.

## Installation

Poetry is required to use locally the CLI.

```bash
curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python -
```

### Appendix

The default install location is `~/.poetry/bin/poetry`

I added the following to my `.zshrc`

`export PATH=$PATH:$HOME/.poetry/bin`

## Roadmap

- Configuring Tests/Linting
- Generate Project yaml `ocpeasy.yml`
- Generate Stage yaml `<stage>.yml`
- Support SSH Keys for cloning (read: https://stackoverflow.com/questions/28291909/gitpython-and-ssh-keys)

## Examples

## License

## Credit