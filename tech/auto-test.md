# Automation & Testing

## Auto testing
### Web browser
* selenium

##### Selenium {#selenium}
[Github Proj](https://github.com/sasa33k/s3a-selenium)

| | |
| :--- | :--- |
| Objective | Automate web browser testing with report and screen shots record<br>Allow QA team member write test cases in excel format|
| Enhancements | Alert Handling, App integrations, loop for testcases in folder, Auto Seq no. , properties setting|
| Limitation | Asian Character in MS Excel cannot use Utf8, validations |


csv columns

| # | Columns | Description |
| :--- | :--- | :--- |
| 0 | stepNo | Show in Report & screen cap file name <br>**Don't use special characters here <br>** use #### as a new subcase, show as new section for report, use with following columns only(stepNo, elementName) |
| 1 | name | Show in terminal log? |
| 2 | sequence | **No duplicates** |
| 3 | desc | comment for testcases csv only, not used? |
| 4 | url | for "FetchingPage" doType, use with following columns (stepNo, name, sequence, url, doType, takePhoto) |
| 5 | elementname | ?? |
| 6 | elementvalue | Correspond to "GET" type |
| 7 | elementgetType | Correspond to "GET" type |
| 8 | doType | "DO" something for the elements "GOT"|
| 9 | exceptvalue | Expected value for "getText" & Alert? |
| 10 | takePhoto | TRUE / FALSE|


### App
* Appium



##### Appium {#appium}



### Task Automation / RPA
`AutoIt (Windows application)`

`sikuli (image recognition)`
