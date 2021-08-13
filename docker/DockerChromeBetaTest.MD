# [Docker_001](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/basic/DockerChromeBetaTest.java)
## Test Case Name
* DockerChromeBetaTest
## Test Case Description
* Webdrivermanager check Chrome version and download corresponding chromedriver automatically.
* Start Chrome Beta in Docker and navigate to https://bonigarcia.org/webdrivermanager/.
## Pre-conditions
* The test machine must have internet connection
* Chrome installed
## Post-conditions
* Webdriver and corresponding chrome browser must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* N/A
## Test Case Results
* N/A
---
## Test Steps
1. Step 1
	* Step Details
		* Open Chrome Beta in Docker and navigate to https://bonigarcia.org/webdrivermanager/ using chromewebdriver.
	* Test Data
		* browserVersion= "beta"
	* Expected Results
		* Chrome open successully then navigate to https://bonigarcia.org/webdrivermanager/ (Title contains "WebDriverManager")
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* N/A
---
