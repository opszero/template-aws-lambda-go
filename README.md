# <name>

# Handlers

# Workflow

 - Develop on Branches
 - Merge into `qa` this will deploy the qa stage
 - Merge into `master` this will deploy the prod stage

# Testing

```
pytest
```

All files should have a cooresponding test_<name>.py file within the same
directory. There is no separate test directory and this will allow us to keep
the tests and code in sync.