# Introduction
* Contains all test case specifications and results (Markdown format)
* Uses Test Case Management Tool at https://github.com/KichiFinn/em-testcasemng-tool.git

# Steps
### 1. Generate test case specifications
* Test designer generate test case specification template using [Test Case Management Tool]() as following:
``` 
    java -jar em-testcasemng-tool.jar -i -f ./basic/ChromeTest.MD
    java -jar em-testcasemng-tool.jar -i -f ./basic/EdgeTest.MD
    java -jar em-testcasemng-tool.jar -i -f ./basic/FirefoxTest.MD
    java -jar em-testcasemng-tool.jar -i -f ./basic/InternetExplorerTest.MD
    ...
    java -jar em-testcasemng-tool.jar -i -f ./webrtc/WebRtcRemoteFirefoxTest.MD
```
### 2. Design Test Case
* Test designer add contents to test case specification files (generated Markdown files in step 1) will following rules
  *  **Any change in "Test Case ID", "Test Case Script's location", "Test Case Name", "Test Case Description", "Pre-condition", "Post-Condition", "Step Details", "Test Step's Data", or "Test Step Expected Results" will be treated as Test Design chnages.**
  * **Add or remove test steps will be treated as Test Design change**
  * **Change in other fields will be treated as upload test results.**
* Create Pull Request
* Wait for approval from other test designer to add it to project
### 3. Approve other test desiger's Pull Request
* Approve and merge other Pull Request
* GitHub user that do the Pull Request will be treated as Approved person when convert Test Design to Excel
### 4. Update test results when running
* Tester run tests then fill test results to test case specification files (Markdown)
* Commit test results to GitHub
* **Note: "Date Tested (mm/dd/yy hh:mm:ss)" field is mandatory, tester must fill this field (Ex: 8/13/21 14:06:13)**
* **Note: "Test Case Results" field is mandatory, choose one of "Pass", "Fail", "Not executed" or "Suspended"**
### 5. Analyze and Report
* Convert a Markdown test case specification file to Excel
```java -jar em-testcasemng-tool.jar -c -f ./Home/NavigateHome.MD```
* Convert all Markdown test case specification files to Excel
```java -jar em-testcasemng-tool.jar -c -f ./Home/*.MD```
* Convert a Excel test case specification file to Markdown
```java -jar em-testcasemng-tool.jar -c -f ./Home/NavigateHome.xlsx```
* Convert all Excel test case specification files to Markdown
```java -jar em-testcasemng-tool.jar -c -f ./Home/*.xlsx```
* Analyze a test case results
```java -jar em-testcasemng-tool.jar -a -f ./Home/NavigateHome.MD```
all test results of test case "NavigateHome.MD" will be analyzed (from created to current branch)
* Analyze all testcase results at a point
```java -jar em-testcasemng-tool.jar -a -f ./Home/*.MD```
all test results of test case at "/Home" will be analyzed (current branch)