# replace-script

## replace
This script will look recursively through a given path. It will find and relpace a specified "oldpattern" with a "newpattern". In order to run this script, the proper syntax is "./replace path oldpattern newpattern". Do not for get to make the script excecutable by running the command "chmod 700 replace"

## run-test
This script creates and removes an example directory for the replace script. The run-test script has two modes, setup and teardown. The setup mode creates a directory with the following structure:

test

test/edu

test/edu/bvu

test/edu/bvu/cs

test/edu/bvu/cs/WebApp.java

test/edu/bvu/cs/WebAppMain.java
If the test directory already exists then it will overwrite the previous directory. When using the setup mode, prompt with the command "./run-test setup"

The teardown mode gets rid of the test directory. If the test directory does not exist, it will inform the user that it does not exist. Run the teardown mode by using the command "./run-test teardown". Make sure to make this script excecutable by running the command "chmod 700 run-test".

