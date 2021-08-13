# [Multiple_002](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/multiple/MultipleBrowsersTest.java)
## Test Case Name
* MultipleBrowsersTest
## Test Case Description
* Webdrivermanager check Chrome version and download corresponding chromedriver automatically.
* Webdrivermanager check Firefox version and download corresponding geckodriver automatically.
* Then using webdriver to open https://bonigarcia.org/webdrivermanager/ in Chrome and Firefox
## Pre-conditions
* The test machine must have internet connection
* Chrome installed
* Firefox installed
## Post-conditions
* Webdriver and corresponding browsers must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* 8/13/21 13:59:05
## Test Case Results
* Fail
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
		* Open Firefox and navigate to https://bonigarcia.org/webdrivermanager/ using geckodriver.
	* Test Data
		* N/A
	* Expected Results
		* Firefox open successully then navigate to https://bonigarcia.org/webdrivermanager/
	* Actual Results
		* java.lang.NullPointerException
	* Pass / Fail / Not executed / Suspended
		* Fail
3. Step 3
	* Step Details
		* Compare title of Chrome and Firefox
	* Test Data
		* N/A
	* Expected Results
		* Chome and Firefox has the same title
	* Actual Results
		* java.lang.NullPointerException
	* Pass / Fail / Not executed / Suspended
		* Fail
---
