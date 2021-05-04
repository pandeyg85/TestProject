I have automated 4 scenarios including various test cases as follows:
1: Validating Mandatory fields for user creation
2: successful user creation
3: Login validations
4: Successful login
These are included in 2 features files. 
The framework is using Maven Build, BDD, Cucumber, Java, Selenium, Web driver, Allure reporting, Cucumber reporting, Junit4.
The compilation is Java 1.7JRE
Steps to run on your machine 
Download in any IDE (I used Eclipse Oxygen)
Set up all  your preferences related to maven and Java compiler in eclipse
open port 4444
Install Selenium Webdriver
Download Chrome/ IE Driver
run the  test  cases using junit 4 with arguments as below (It is for running on the local machine, not on remote.)               
-DEnvironment=Test 
-Dbrowser=chrome 
-Dwebdriver.chrome.driver=C:/TEMP/chromedriver.ex

Attached is the Cucumber report (basic format from Master-thoughts) and junit execution all 4 test cases ran in 190seconds.

Please download the target file and open index.html it will show all results.

Please note Screenshot is also implemented as part of test evidence.

the framework also includes allure reporting hence Jenkins - allure report integration can be easily doneAll the pageactionHelper class to work on web elements are completely reusable code and feature file steps can also be used with parameterization.

