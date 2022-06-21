# pyenv-venv

[pyenv](https://pyenv.run) plugin for create and activate Python venv.

This is a lightweight alternative to the default **pyenv-virtualenv** plugin.


## Usage

`pyenv venv` - create in local `venv` dir for current `python`.

`pyenv venv <dir>` - create in local `<dir>` for current `python`.

**Note:** call `exit` instead of `deactivate`, because it runs another 
`$SHELL` instance under the hood.

See `pyenv help venv`.


## Install

Place this repo contents in `<pyenv root>/plugins/pyenv-venv`, e.g.:

```bash
git clone https://github.com/reksar/pyenv-venv "`pyenv root`/plugins/pyenv-venv"
```
