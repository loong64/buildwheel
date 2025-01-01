# Wheel Builder

## Installing the Packages

The built wheels are hosted in the [package registry](https://gitlab.com/loong64/pypi/-/packages/) associated with the loong64/pypi/ project.  To install them, first upgrade pip to the latest version, e.g.,

```sh
python -m pip install --upgrade pip
```

and then pass the --index-url option to the install command to tell pip to pull packages from the registry associated with this project, e.g.,

```sh
python -m pip install poetry --index-url https://gitlab.com/api/v4/projects/loong64%2Fpypi/packages/pypi/simple
```