# FIT2107 Assignment repository (Lab 04 - Team 1)

## Run our program
In order to run our program, users can either execute the [MyEventManager.py](MyEventManager.py) file or the [MyEventManagerApp.py](MyEventManagerApp.py) file.


## Test Suites
All test suites can be found under [MyEventManagerTest.py](MyEventManagerTest.py) file.

## Test Strategy
All test strategies can be found in the [testStrategy.md](testStrategy.md) file.

## Issue with GitLab CI
Our test cases are able to run successfully and the coverage report would also be displayed during the testing job in the CI pipeline. However, our pipeline testing job does not seem to terminate after that and it is just stuck there. We have also made sure that our MyEventManagerTest.py does not run into an infinite loop, and since the coverage report is displayed, this means MyEventManagerTest.py definitely has finished running. Thus, we are not sure why this occurs.


