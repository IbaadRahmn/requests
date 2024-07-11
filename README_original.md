Report for Assignment 1 resit
Project chosen
Name: Requests

URL: https://github.com/IbaadRahmn/requests

Number of lines of code and the tool used to count it: <TODO>

Programming language: Python

Coverage measurement with existing tool
Tool Used: Coverage.py
I used coverage.py, a Python tool, to measure test coverage for the requests project.

Execution:
Installation:

Installed coverage.py using pip:
bash
Copy code
pip install coverage
Running Tests with Coverage:

Changed directory to the tests folder:
bash
Copy code
cd path/to/requests/tests
Ran tests with coverage:
bash
Copy code
coverage run -m pytest
Generating Coverage Report:

Viewed coverage report in terminal:
bash
Copy code
coverage report
Coverage Results:
Screenshot of Coverage Report:

<Insert screenshot of the coverage report here>
Coverage improvement
Individual tests
Function 1: TestRequests.test_POSTBIN_SEEKED_OBJECT_WITH_NO_ITER.TestStream.read
Patch/Commit:

<Provide a link to the commit or a diff showing the changes made for this function>
Old Coverage Results:

<Screenshot of the old coverage results for read function>

New Coverage Results:

<Screenshot of the new coverage results for read function>

Coverage Improvement:

Coverage Improvement: Improved from X% to Y%.
Reason: Added tests to cover both branches (if size: and else:) within the read function, ensuring that different code paths are now tested.

Overall
Screenshot of the old coverage results:

<Insert screenshot of the overall coverage results before making modifications>
Screenshot of the new coverage results:

<Insert screenshot of the overall coverage results after making modifications>
