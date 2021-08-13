# [Webrtc_002](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/webrtc/WebRtcFirefoxTest.java)
## Test Case Name
* WebRtcFirefoxTest
## Test Case Description
* Webdrivermanager check Firefox version and download corresponding geckodriver automatically.
* Then using webdriver to open https://webrtc.github.io/samples/src/content/devices/input-output/
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
		* Open Firefox and navigate to https://webrtc.github.io/samples/src/content/devices/input-output/ using Firefoxwebdriver.
	* Test Data
		* media.navigator.permission.disabled= true
		* media.navigator.streams.fake= true
	* Expected Results
		* Firefox open successully then navigate to https://webrtc.github.io/samples/src/content/devices/input-output/
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* N/A
---
