## Install the virtualenv package

```bash
$ pip install virtualenv
```

## Create the virtual environment

```bash
$ python -m venv virtualenv
```

## Activate the virtual environment

> ### Mac OS / Linux

```bash
$ source virtualenv/bin/activate
```
---
> ### Windows

```bash
$ virtualenv\Scripts\activate
```
---
> ### Install jupeter notbook
```bash
$ python -m pip install --upgrade pip
$ pip install ipykernel
$ python -m ipykernel install --user --name=virtualenv
```

## Deactivate the virtual environment

```bash
$ deactivate
```
