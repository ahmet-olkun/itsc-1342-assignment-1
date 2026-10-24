# ITSC 1342 - Assignment 1: Access Control Check

Author: Ahmet Olkun

`code/solution.py` checks a username, password, and clearance level and returns
the corresponding access result.

From the repository folder, run the provided tests:

```powershell
python .\tests\test_solution.py
```

The terminal output is saved in `tests/test_output.txt`. The `screenshots`
folder contains the test execution screenshot.

The provided test file imported `verify_soc_access` but called `verify_access`.
The import was corrected to `verify_access` to match the unchanged starter
function definition. The provided test cases are unchanged.
