# [Basic_004](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/basic/InternetExplorerTest.java)
## Test Case Name
* InternetExplorerTest
## Test Case Description
* Webdrivermanager check InternetExplorer version and download corresponding IE webdriver automatically.
* Then using webdriver to open https://bonigarcia.org/webdrivermanager/ and click heading.
## Pre-conditions
* The test machine must have internet connection
* InternetExplorer installed
* All "Protected Mode" must Enable or Disable for all Security Zone: Tools>Internet Options>Security tab>Zone
## Post-conditions
* Webdriver and corresponding InternetExplorer browser must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* 8/18/21 18:36:31
## Test Case Results
* Pass
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
