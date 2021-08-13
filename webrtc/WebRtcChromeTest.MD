# [Webrtc_002](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/webrtc/WebRtcChromeTest.java)
## Test Case Name
* WebRtcChromeTest
## Test Case Description
* Webdrivermanager check Chrome version and download corresponding Chromedriver automatically.
* Then using webdriver to open https://webrtc.github.io/samples/src/content/devices/input-output/
## Pre-conditions
* The test machine must have internet connection
* Chrome installed
## Post-conditions
* Webdriver and corresponding Chrome browser must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* 8/13/21 14:31:28
## Test Case Results
* Pass
---
## Test Steps
1. Step 1
	* Step Details
		* Open Chrome and navigate to https://webrtc.github.io/samples/src/content/devices/input-output/ using Chromewebdriver.
	* Test Data
		* media.navigator.permission.disabled= true
		* media.navigator.streams.fake= true
	* Expected Results
		* Chrome open successully then navigate to https://webrtc.github.io/samples/src/content/devices/input-output/
	* Actual Results
		* As expected
	* Pass / Fail / Not executed / Suspended
		* Pass
---
