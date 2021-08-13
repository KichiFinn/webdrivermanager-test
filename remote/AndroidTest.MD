# [Remote_001](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/remote/AndroidTest.java)
## Test Case Name
* AndroidTest
## Test Case Description
* Webdrivermanager check Chrome version and download corresponding chromedriver automatically.
* Then using webdriver to connect to remote webdriver server at http://127.0.0.1:4444/wd/hub
* Start Chome on Android phone and navigate to https://bonigarcia.org/webdrivermanager/
## Pre-conditions
* The test machine must have internet connection
## Post-conditions
* Chrome browser on Android device must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* N/A
## Test Case Results
* N/A
---
## Test Steps
1. Step 1
	* Step Details
		* Connect to RemoteWebDriver at http://127.0.0.1:4444/wd/hub
	* Test Data
		* platformName= "Android"
		* browserName= "chrome"
		* deviceName= "Samsung Galaxy Note 20"
	* Expected Results
		* Connect to RemoteWebDriver successfully
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* N/A
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
		* N/A
2. Step 2
	* Step Details
		* Navigate to https://bonigarcia.org/selenium-jupiter
	* Test Data
		* N/A
	* Expected Results
		* Navigate to https://bonigarcia.org/selenium-jupiter successfully (Title contains "Selenium-Jupiter")
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* N/A
---
