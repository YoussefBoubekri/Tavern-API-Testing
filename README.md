## About: 
Using Tavern api testing framework example

## API's URL
URL: https://swapi.co/documentation

## requires:
tavern
pytest

## run tests:
test specs file needs to be prefixed with 'test_'*.yaml
```python
pytest test_status.tavern.yaml

#to store results in xml JUnit format

py.test --junitxml results.xml test_status.tavern.yaml
