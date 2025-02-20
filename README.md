# drt-sdk-py-core

Core components of the Dharitri Python SDK.

## Distribution
 
 - GitHub: `git+https://git@github.com/DharitriOne/drt-sdk-py-core.git@v{Version}#egg=drt_sdk_core`
 - [PyPi](https://pypi.org/user/xfactor.toml/)

## Documentation

[docs.dharitri.com](https://docs.dharitri.com/sdk-and-tools/moapy/moapy/)

## Development setup

### Virtual environment

Create a virtual environment and install the dependencies:

```
python3 -m venv ./venv
source ./venv/bin/activate
pip install -r ./requirements.txt --upgrade
```

Install development dependencies, as well:

```
pip install -r ./requirements-dev.txt --upgrade
```

Above, `requirements.txt` should mirror the **dependencies** section of `pyproject.toml`.

If using VSCode, restart it or follow these steps:
 - `Ctrl + Shift + P`
 - _Select Interpreter_
 - Choose `./venv/bin/python`.

### Tests

Run the tests as follows:

```
pytest .
```

### Linting

First, install [`pyright`](https://github.com/microsoft/pyright) as follows:

```
npm install --global pyright
```

Run `pyright`:

```
pyright
```

Run `flake8`:

```
flake8 drt_sdk_core
```
