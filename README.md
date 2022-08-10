# simple_web_app_test

Repository contains tests for simple web application http://uitestingplayground.com/sampleapp

'shared' folder contains base class, selectors and test data used commonly in all tests  
'test_cases' selector contains modules with test case classes

Scenarios can be found in scenarios.txt file. All test cases are gathered together into test suite in web_test_test_suite.py file

To execute tests:
1. Install python
2. Install selenium `pip install selenium` from command line
3. Start tests by typing command `python -m web_test_test_suite`