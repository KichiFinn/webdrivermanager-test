# [Remote_005](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/remote/SaucelabsTest.java)
## Test Case Name
* SaucelabsTest
## Test Case Description
* Using webdriver to connect to Saucelabs remote webdriver
* Start Chome on Saucelabs and navigate to https://bonigarcia.org/webdrivermanager/
## Pre-conditions
* The test machine must have internet connection
## Post-conditions
* Chrome browser on Saucelabs must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* 8/13/21 14:12:54
## Test Case Results
* Not executed
---
## Test Steps
1. Step 1
	* Step Details
		* Connect to RemoteWebDriver at "https://" + USERNAME + ":" + ACCESS_KEY + "@ondemand.saucelabs.com:443/wd/hub";
	* Test Data
		* USERNAME= "alice"
		* ACCESS_KEY= "172a5862b272700e25a86eb1cc58ec5e4bf7abe7"
		* platform= ""Windows 10"
		* version= "52.0"
	* Expected Results
		* Connect to RemoteWebDriver successfully
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* Not executed
2. Step 2
	* Step Details
		* Navigate to https://bonigarcia.org/webdrivermanager/
	* Test Data
		* N/A
	* Expected Results
		* Navigate to https://bonigarcia.org/webdrivermanager/ successfully (Title contains "WebDriverManager")
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* Not executed
---
