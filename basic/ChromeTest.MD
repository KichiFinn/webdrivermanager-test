# [Basic_001](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/basic/ChromeTest.java)
## Test Case Name
* ChromeTest1
## Test Case Description
* Webdrivermanager check Chrome version and download corresponding chromedriver automatically.
* Then using webdriver to open https://bonigarcia.org/webdrivermanager/ and click heading.
## Pre-conditions
* The test machine must have internet connection1
* Chrome installed1
## Post-conditions
* Webdriver and corresponding chrome browser must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* 8/13/21 14:06:47
## Test Case Results
* Pass
---
## Test Steps
1. Step 1
	* Step Details
		* Open chrome and navigate to https://bonigarcia.org/webdrivermanager/ using chromewebdriver.
	* Test Data
		* N/A
	* Expected Results
		* Chrome open successully then navigate to https://bonigarcia.org/webdrivermanager/
	* Actual Results
		* As expected
	* Pass / Fail / Not executed / Suspended
		* Pass
2. Step 2
	* Step Details
		* Click element has id = "examples"
	* Test Data
		* N/A
	* Expected Results
		* element tagName= "body" has text value = "WebDriverManager"
	* Actual Results
		* As expected
	* Pass / Fail / Not executed / Suspended
		* Pass
---
