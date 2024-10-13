Python API Automation Framework


Tech Stack
- Python 3.12
- Requests - HTTP Requests 
- PyTest - Testing Framework
- Reporting - Allure Report,PyTest HTML
- Test Data - CSV, Excel, JSON, Faker 
- Advance API Testcase - jsonschema
- Parallel Execution - x distribute (xdist)

How to Install Packages
 
```
pip install requests pytest pytest-html
```

How to run your Testcase Parallel 
```
pip install pytest-dist
```

How to run the Basic Test with Allure

```
pytest tests/tests/crud/test_create_bor
```