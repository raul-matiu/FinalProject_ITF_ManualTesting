# Final project for ITF Manual Testing Course #

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: [demo.opencart.com](https://demo.opencart.com/index.php?route=product/product&language=en-gb&product_id=43) - Product page section

* Original UI documentation: [link](http://docs.opencart.com/en-gb/store-front/) 
* I create my own documentation, in order to find bugs and static testing issues: [link](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/blob/main/Business-requirements_Product-page-section_full.pdf)
* API Documentation: [link](https://docs.opencart.com/en-gb/system/users/api/)

The final project will be split into 2 sections: Testing section and SQL section.

Tools used: Jira, Zephyr Squad and MySQL Workbench.

## Functional specifications ##
Product page section from demo.opencart.com. Business requirements can be found [here](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/blob/main/Business-requirements_Product-page-section_full.pdf) 

![Epic-00-1](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/c7b11019-f750-46be-85e4-fb237134719e)
![Epic-00-2](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/2bd037d6-df32-4577-884d-d15cf92cc6e3)

# 1 Testing section #

## 1.1 Test Planning ##
The Test Plan is designed to describe all details of testing for the Product page section from demo.opencart.com application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing and the risks associated with the plan.

### 1.1.1 Roles assigned to the project and persons allocated ###
I am the only person responsible for managing this testing-project. 
### 1.1.2 Entry criteria defined ###
* The environment is up and running
* User created and login
### 1.1.3 Exit criteria defined ###
* All test cases set in scope are executed
* At least 50% with status passed
* No critical defect opened
* Maximum 5 high priority defects opened
* Testing deadline 25.06.2023
### 1.1.4 Test scope ###
Tests in scope: Review and Functional Testing using Black-box testing and Experience-based testing as Test Design Techniques, GUI Testing.\
Tests not in scope: Performance Testing, Stress testing, Volume Testing, compatibility testing with multiple browsers, Mobile testing and Functional Testing using White-box Testing Techniques
### 1.1.5 Risks detected ###
Project risks: lack of knowledge, illness, insufficient testers, no developers available to fix the opened bugs, environment not functional and not available all the time as it is an open source, other peoples can change code for a short period of time and my designed test cases may fail.\
Product risks:
### 1.1.6 Evaluating entry criteria ###
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

## 1.2 Test Monitoring and Control ##
It will be done by generating periodic reports that reflect the current status of the test.
![PFI-Sprint1](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/aa15c7af-ea45-4358-81ff-842a945e1653)

## 1.3 Test Analysis ##
The testing process will be executed based on the above [requirements](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/blob/main/Business-requirements_Product-page-section_full.pdf) for the Product section. The following test conditions were found:

Enter test conditions here

## 1.4 Test Design ##
Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are:

Test cases: -> enter here test cases or at least the titles

The test cases with steps can be viewed here: 

## 1.5 Test Implementation ##
The following elements are needed to be ready before the test execution phase begins:

* Testing environment is up and running: [demo.opencart.com](https://demo.opencart.com/index.php?route=product/product&language=en-gb&product_id=43) 
* Access to the testing environment is given: Username: demo | Password: demo
* Cycle summary was created

## 1.6 Test Execution ##
Test cases are executed on the created test Cycle summary: link

Bugs have been created based on the failed tests.\
The complete bug reports can be found here: ...enter here bug titles

## 1.7 Test Completion ##
Exit criteria was evaluated and passed\
The traceability matrix was generated and can be found here:

![Tracebility-matrix-PFI-2_PFI8](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/76e47459-6ece-4485-9aa7-1677d1aa4499)

![Tracebility-matrix-detail-PFI-7_PFI-8](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/e9ceb167-bff5-4183-ada3-1d37f48d6d16)


Test execution chart was generated, the final report shows.... -> describe the final report
-> enter here test execution report/chart

# 2 SQL section ##