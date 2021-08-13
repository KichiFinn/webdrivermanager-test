# [Remote_004](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/remote/RemoteWebRtcFirefoxTest.java)
## Test Case Name
* RemoteWebRtcFirefoxTest
## Test Case Description
* Using webdriver to connect to remote webdriver server at http://127.0.0.1:4444/wd/hub
* Start Firefox on remote and navigate to https://webrtc.github.io/samples/src/content/devices/input-output/
## Pre-conditions
* The test machine must have internet connection
## Post-conditions
* Firefox browser on remote must close successfully.
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
		* media.navigator.permission.disabled= true
		* media.navigator.streams.fake= true
	* Expected Results
		* Connect to RemoteWebDriver successfully
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* N/A
2. Step 2
	* Step Details
		* Navigate to https://webrtc.github.io/samples/src/content/devices/input-output/
	* Test Data
		* N/A
	* Expected Results
		* Navigate to https://webrtc.github.io/samples/src/content/devices/input-output/
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* N/A
---
