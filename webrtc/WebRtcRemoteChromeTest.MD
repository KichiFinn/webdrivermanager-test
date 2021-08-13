# [Webrtc_003](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/webrtc/WebRtcRemoteChromeTest.java)
## Test Case Name
* WebRtcRemoteChromeTest
## Test Case Description
* Webdrivermanager check Chrome version and download corresponding chromedriver automatically.
* Using remotedriver to connect to  http://localhost:4444/wd/hub
* Then navigate to https://webrtc.github.io/samples/src/content/devices/input-output/
## Pre-conditions
* The test machine must have internet connection
* Chrome installed
## Post-conditions
* Webdriver and corresponding Chrome browser must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* 8/13/21 14:12:54
## Test Case Results
* Not executed
---
## Test Steps
1. Step 1
	* Step Details
		* Connect to remotewebdriver at http://localhost:4444/wd/hub
	* Test Data
		* --use-fake-ui-for-media-stream
		* --use-fake-device-for-media-stream
	* Expected Results
		* Connect to remotewebdriver successfully
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* Not executed
2. Step 2
	* Step Details
		* Open Chrome and navigate to https://webrtc.github.io/samples/src/content/devices/input-output/ using chromewebdriver.
	* Test Data
		* N/A
	* Expected Results
		* Chrome open successully then navigate to https://webrtc.github.io/samples/src/content/devices/input-output/
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* Not executed
---
