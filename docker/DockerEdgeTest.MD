# [Docker_004](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/basic/DockerEdgeTest.java)
## Test Case Name
* DockerEdgeTest
## Test Case Description
* Webdrivermanager check Edge version and download corresponding Edgedriver automatically.
* Start Edge in Docker and navigate to https://bonigarcia.org/webdrivermanager/.
## Pre-conditions
* The test machine must have internet connection
* Edge installed
## Post-conditions
* Webdriver and corresponding Edge browser must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* 8/13/21 14:31:41
## Test Case Results
* Fail
---
## Test Steps
1. Step 1
	* Step Details
		* Open Edge in Docker and navigate to https://bonigarcia.org/webdrivermanager/ using Edgewebdriver.
	* Test Data
		* N/A
	* Expected Results
		* Edge open successully then navigate to https://bonigarcia.org/webdrivermanager/ (Title contains "WebDriverManager")
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* Fail
---
