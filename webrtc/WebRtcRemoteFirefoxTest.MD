# [Webrtc_004](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/webrtc/WebRtcRemoteFirefoxTest.java)
## Test Case Name
* WebRtcRemoteFirefoxTest
## Test Case Description
* Webdrivermanager check Firefox version and download corresponding geckodriver automatically.
* Using remotedriver to connect to  http://localhost:4444/wd/hub
* Then navigate to https://webrtc.github.io/samples/src/content/devices/input-output/
## Pre-conditions
* The test machine must have internet connection
* Firefox installed
## Post-conditions
* Webdriver and corresponding Firefox browser must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* N/A
## Test Case Results
* N/A
---
## Test Steps
1. Step 1
	* Step Details
		* Connect to remotewebdriver at http://localhost:4444/wd/hub
	* Test Data
		* media.navigator.permission.disabled= true
		* media.navigator.streams.fake= true
	* Expected Results
		* Connect to remotewebdriver successfully
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* N/A
2. Step 2
	* Step Details
		* Open Firefox and navigate to https://webrtc.github.io/samples/src/content/devices/input-output/ using Firefoxwebdriver.
	* Test Data
		* N/A
	* Expected Results
		* Firefox open successully then navigate to https://webrtc.github.io/samples/src/content/devices/input-output/
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* N/A
---
