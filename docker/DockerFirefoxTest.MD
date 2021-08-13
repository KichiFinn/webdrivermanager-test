# [Docker_005](https://github.com/bonigarcia/webdrivermanager-examples/tree/master/src/test/java/io/github/bonigarcia/wdm/test/basic/DockerFirefoxTest.java)
## Test Case Name
* DockerFirefoxTest
## Test Case Description
* Webdrivermanager check Firefox version and download corresponding geckodriver automatically.
* Start Firefox in Docker and navigate to https://webrtc.github.io/samples/src/content/devices/input-output/.
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
		* Open Firefox in Docker and navigate to https://webrtc.github.io/samples/src/content/devices/input-output/ using Firefoxwebdriver.
	* Test Data
		* --use-fake-ui-for-media-stream
		* --use-fake-device-for-media-stream
	* Expected Results
		* Firefox open successully then navigate to https://webrtc.github.io/samples/src/content/devices/input-output/ (Element with id= "video" has tag= "video")
	* Actual Results
		* N/A
	* Pass / Fail / Not executed / Suspended
		* N/A
---
