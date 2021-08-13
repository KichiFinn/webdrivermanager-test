# Introduction
* Contains all test case specifications and results (Markdown format)
* Uses Test Case Management Tool at https://github.com/KichiFinn/em-testcasemng-tool.git

# Steps
### 1. Generate test case specifications
* Test designer generate test case specification template using [Test Case Management Tool]() as following:
``` 
    java -jar em-testcasemng-tool.jar -i -f ./Login.MD
    java -jar em-testcasemng-tool.jar -i -f ./Home/NavigateHome.MD
    java -jar em-testcasemng-tool.jar -i -f ./Dashboard/CreateTask.MD
    java -jar em-testcasemng-tool.jar -i -f ./Dashboard/EditTask.MD
    java -jar em-testcasemng-tool.jar -i -f ./Dashboard/DeleteTask.MD
```
### 2. Create  pull request
* Test designer add contents to test case specification files (Markdown) then create a pull request
* Wait for approval from other test designer to add it to project
### 3. Update test results when running
* Tester run tests then fill test results to test case specification files (Markdown)
* Push test results to GitHub (Markdown files)
### 3. Analyze and Report
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