# Python-template
[![black](https://github.com/evroon/python-template/actions/workflows/black.yml/badge.svg)](https://github.com/evroon/python-template/actions/workflows/black.yml)
[![isort](https://github.com/evroon/python-template/actions/workflows/isort.yml/badge.svg)](https://github.com/evroon/python-template/actions/workflows/isort.yml)
[![mypy](https://github.com/evroon/python-template/actions/workflows/mypy.yml/badge.svg)](https://github.com/evroon/python-template/actions/workflows/mypy.yml)
[![pytest](https://github.com/evroon/python-template/actions/workflows/pytest.yml/badge.svg)](https://github.com/evroon/python-template/actions/workflows/pytest.yml)
[![nix](https://github.com/evroon/python-template/actions/workflows/nix.yml/badge.svg)](https://github.com/evroon/python-template/actions/workflows/nix.yml)

Basic template repository for Python 3.9 projects.
This repo includes black, mypy, pytest and isort configurations and github workflows.

Additionally, using [mach-nix](https://github.com/DavHau/mach-nix), a Nix environment can be activated. Simply add python modules to [nix/requirements.txt](nix/requirements.txt) and activate the Nix shell using `nix-shell nix` to start using the environment.
