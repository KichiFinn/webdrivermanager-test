# [Basic_004](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/basic/InternetExplorerTest.java)
## Test Case Name
* InternetExplorerTest
## Test Case Description
* Webdrivermanager check InternetExplorer version and download corresponding IE webdriver automatically.
* Then using webdriver to open https://bonigarcia.org/webdrivermanager/ and click heading.
## Pre-conditions
* The test machine must have internet connection
* InternetExplorer installed
## Post-conditions
* Webdriver and corresponding InternetExplorer browser must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* 8/13/21 16:30:10
## Test Case Results
* Fail
---
## Test Steps
1. Step 1
	* Step Details
		* Open InternetExplorer and navigate to https://bonigarcia.org/webdrivermanager/ using IE webdriver.
	* Test Data
		* N/A
	* Expected Results
		* InternetExplorer open successully then navigate to https://bonigarcia.org/webdrivermanager/
	* Actual Results
		* Exception: Unexpected error launching Internet Explorer. Protected Mode settings are not the same for all zones. Enable Protected Mode must be set to the same value (enabled or disabled) for all zones.
	* Pass / Fail / Not executed / Suspended
		* Fail
2. Step 2
	* Step Details
		* Click element has id = "examples"
	* Test Data
		* N/A
	* Expected Results
		* element tagName= "body" has text value = "WebDriverManager"
	* Actual Results
		* Exception: Unexpected error launching Internet Explorer. Protected Mode settings are not the same for all zones. Enable Protected Mode must be set to the same value (enabled or disabled) for all zones.
	* Pass / Fail / Not executed / Suspended
		* Fail
---
