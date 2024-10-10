###Pre-commit Hooks:

In order for the committees to follow the format `DJ-<TASK_NUMBER>: <COMMIT_MESSAGE>`, a script has been added that checks the format of the committees. If the format is not saved, the committee will be rejected.


###Checking the code format:

To revise Python code, `ruff` is used. Before each cut, the linter starts and checks the code's consistency. If the code does not support the benefits, the committee will be eliminated.


###How to install:

1. pip install pre-commit ruff
2. Initialize pre-commit on your repository: (pre-commit install)
