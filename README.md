# Simple flask example

### Install dependencies

```
pip install -r requirements.txt --no-cache-dir
```

### Run server

```
flask --app flaskr run --debug
```

### Database instanse

```
flask --app flaskr init-db
```

### Tests

Run test files in /tests

```
pytest
```

Measure the code coverage of tests

```
coverage run -m pytest
```

Simple coverage report

```
coverage report
```

**See report in html**
Generate report in htmlcov/ directory.

```
coverage html
```

Cli to see it in browser.

```
htmlcov/index.html
```
