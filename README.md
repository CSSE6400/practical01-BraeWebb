# TODO API
[![GitHub Classroom Workflow](https://github.com/CSSE6400/practical01-BraeWebb/actions/workflows/classroom.yml/badge.svg)](https://github.com/CSSE6400/practical01-BraeWebb/actions/workflows/classroom.yml)

A Flask HTTP server that forms the backend for a todo list application.

Completed as a practical exercise for the UQ Software Architecture course.

## Installation

The Python environment is managed with `pipenv`.
First install `pipenv` with
```bash
python3 -m pip install pipenv
```

Then install dependencies with
```bash
pipenv install
```

## Running

The application can be run with `pipenv`, as below:

```bash
pipenv run flask --app todo run
```

Specify the port to listen on, as below:

```bash
pipenv run flask --app todo run -p 6400
```

Run the application in debug mode to auto-reload on file change, as below:

```bash
pipenv run flask --app todo --debug run
```

## Testing

You can run the CI tests locally with the following commands:

*Project structure*
```bash
./.csse6400/bin/validate_structure.sh
```

*Clean repository*
```bash
./.csse6400/bin/clean_repository.sh
```

*Health endpoint*
```bash
./.csse6400/bin/health.sh
```

*Unit tests*
```bash
./.csse6400/bin/unittest.sh
```
