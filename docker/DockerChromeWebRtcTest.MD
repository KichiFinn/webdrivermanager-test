# [Docker_002](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/basic/DockerChromeWebRtcTest.java)
## Test Case Name
* DockerChromeWebRtcTest
## Test Case Description
* Webdrivermanager check Chrome version and download corresponding chromedriver automatically.
* Start Chrome in Docker and navigate to https://webrtc.github.io/samples/src/content/devices/input-output/.
## Pre-conditions
* The test machine must have internet connection
* Chrome installed
## Post-conditions
* Webdriver and corresponding chrome browser must close successfully.
## Date Tested (mm/dd/yy hh:mm:ss)
* 8/13/21 14:06:52
## Test Case Results
* Fail
---
## Test Steps
1. Step 1
	* Step Details
		* Open Chrome in Docker and navigate to https://webrtc.github.io/samples/src/content/devices/input-output/ using chromewebdriver.
	* Test Data
		* --use-fake-ui-for-media-stream
		* --use-fake-device-for-media-stream
	* Expected Results
		* Chrome open successully then navigate to https://webrtc.github.io/samples/src/content/devices/input-output/ (Element with id= "video" has tag= "video")
	* Actual Results
		* Exception
	* Pass / Fail / Not executed / Suspended
		* Fail
---
