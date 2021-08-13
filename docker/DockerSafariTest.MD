# [Docker_007](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/basic/DockerSafariTest.java)
## Test Case Name
* DockerSafariTest
## Test Case Description
* Webdrivermanager check Safari version and download corresponding Safaridriver automatically.
* Start Safari in Docker and navigate to https://bonigarcia.org/webdrivermanager/.
## Pre-conditions
* The test machine must have internet connection
* Safari installed
## Post-conditions
* Webdriver and corresponding Safari browser must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* 8/13/21 14:25:19
## Test Case Results
* Fail
---
## Test Steps
1. Step 1
	* Step Details
		* Open Safari in Docker and navigate to https://bonigarcia.org/webdrivermanager/ using Safariwebdriver.
	* Test Data
		* N/A
	* Expected Results
		* Safari open successully then navigate to https://bonigarcia.org/webdrivermanager/ (Title contains "WebDriverManager")
	* Actual Results
		* Exception
	* Pass / Fail / Not executed / Suspended
		* Fail
---
