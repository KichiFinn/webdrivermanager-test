# Introduction
* Contains all test case specifications and results (Markdown format) of [A Selenium test project](https://github.com/bonigarcia/webdrivermanager-examples.git)
* Uses Test Case Management Tool at https://github.com/KichiFinn/em-testcasemng-tool.git

# Steps
### 1. Generate test case specifications
* Test designer generate test case specification template using [Test Case Management Tool](https://github.com/KichiFinn/em-testcasemng-tool) as following:
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
  *  **Any change in "Test Case ID", "Test Case Script's location", "Test Case Name", "Test Case Description", "Pre-condition", "Post-Condition", "Step Details", "Test Step's Data", or "Test Step Expected Results" will be treated as Test Design changes.**
  * **Add or remove test steps will be treated as Test Design changes**
  * **Change in other fields will be treated as upload test results.**
  ![TestCaseMD](https://user-images.githubusercontent.com/25169430/129434364-4c60123e-9a68-40a6-bde1-d7210eecd3ae.png)

* Create Pull Request
* Wait for approval from other test designer to add it to project
### 3. Approve other test desiger's Pull Requests
* Approve and merge other Pull Requests
* GitHub user that do the Pull Requests will be treated as Approved person when convert Test Design to Excel
### 4. Update test results after running test
* Tester run tests then fill test results to test case specification files (Markdown)
* Commit test results to GitHub
* **Note:**
    * **"Date Tested (mm/dd/yy hh:mm:ss)" field is mandatory, tester must fill this field (Ex: 8/13/21 14:06:13)**
    * **"Test Case Results" field is mandatory, choose one of "Pass", "Fail", "Not executed" or "Suspended"**
### 5. Analyze
1. Analyze all test results in a directory
    * Check out the Git version that need to be analyzed
    * Run command ```java -jar em-testcasemng-tool.jar -a -f ./webdrivermanager-test/*.MD``` to analyze all test results in 'webdrivermanager-test' directory
    * Analyzed Results is in a generated Excel file named **TotalAnalysis.xlsx** as following:
    ![TotalAnalysis](https://user-images.githubusercontent.com/25169430/129434378-f0fb0014-2c15-4ec9-aab4-cc25d04a603f.png)

2. Analyze Historical Results of a Test Case
    * Check out or switch to the Git version that need to be analyzed (Historical data will be traced from Git history)
    * Run command ```java -jar em-testcasemng-tool.jar -a -f ./webdrivermanager-test/basic/InternetExplorerTest.MD``` to analyze  historical test results of file 'InternetExplorerTest.MD'
    * Analyzed Results is in a generated Excel file named **InternetExplorerTestAnalysis.xlsx** as following:
    ![ATestCaseAnalysis](https://user-images.githubusercontent.com/25169430/129434398-bf59bb8f-cfe7-4221-ba87-79bca3144c97.png)

### 6. Reports
1. Convert a Test Case Specification Markdown to Excel
    * Check out or switch to the  Git version that need to be converted
    * Run command ```java -jar em-testcasemng-tool.jar -c -f ./webdrivermanager-test/basic/InternetExplorerTest.MD``` to convert 'InternetExplorerTest.MD' to 'InternetExplorerTest.xlsx'
    * Rules: 
        * 'Created By', 'Create Date' are the author, date of first commit of Markdown file
        * 'Reviewed By', 'Reviewed Date' are the latest person and date that approve and do the design changes Pull Request
        * 'Version' is the hash code of the last commit in the current local Git
        * 'Log' is the last comment of  the last commit in the current local Git
    * Results look like:
    ![MarkdownToExcel](https://user-images.githubusercontent.com/25169430/129434408-6ed6c6aa-724f-4479-ac9f-ab1b5ec17771.png)

2. Convert an Excel Test Case Specification to Markdown
    * Run command ```java -jar em-testcasemng-tool.jar -c -f ./webdrivermanager-test/basic/InternetExplorerTest.xlsx``` to convert 'InternetExplorerTest.xlsx' to 'InternetExplorerTest.MD'
    * Rules:
        * Ignore 'Created By', 'Create Date', 'Reviewed By', 'Reviewed Date', 'Version' and 'Log' fields in Excel File
3. Convert Test Case Specification Markdown files in a directory to Excel
    * Run command ```java -jar em-testcasemng-tool.jar -c -f ./webdrivermanager-test/*.MD``` to convert all Markdown files in directory 'webdrivermanager-test' (recursive) to Excel
    * Output is a Excel files
4. Convert Test Case Specification Excel files in a directory to Markdown
    * Run command ```java -jar em-testcasemng-tool.jar -c -f ./webdrivermanager-test/*.xlsx``` to convert all Excels files in directory 'webdrivermanager-test' (recursive) to Markdown
    * Output is a Markdown files
### 7. Others
* Use any editor to edit Markdown file (may edit directly on browser with Github edit)
* Use any Git tools to compare, merge, log to check Test Case results, Test Case changes
* Remember use the backslash character \ to escape Markdown syntax characters: \\ \` \* \_ \{ \} \[ \] \( \) \# \+ \- \. \!
