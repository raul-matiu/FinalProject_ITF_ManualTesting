# Final project for ITF Manual Testing Course #

The scope of the final project for [ITF](https://www.itfactory.ro/) Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: [demo.opencart.com](https://demo.opencart.com/index.php?route=product/product&language=en-gb&product_id=43) - Product page section

* Original UI documentation: [link](http://docs.opencart.com/en-gb/store-front/) 
* I create my own documentation, in order to find bugs and static testing issues: [link](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/blob/main/Business-requirements_Product-page-section_full.pdf)
* API Documentation: [link](https://docs.opencart.com/en-gb/system/users/api/)

Tools used: Jira and Zephyr Squad.

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
* requirements are defined
* project risks are identified and reduced
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
Project risks: lack of knowledge, illness, insufficient testers, no developers available to fix the opened bugs, Problems with test tools (Zephyr Squad trial version), environment not functional and not available all the time as it is an open source, other peoples can change code for a short period of time and my designed test cases may fail.

Product risks: The app doesn't work consistently, Product incapacity
to meet customer all expectations
### 1.1.6 Evaluating entry criteria ###
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

## 1.2 Test Monitoring and Control ##
It will be done by generating periodic reports that reflect the current status of the test.
![Executions-list](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/beb331b8-8137-40a4-89d4-9569d1eb91c5)

## 1.3 Test Analysis ##
The testing process will be executed based on the above [requirements](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/blob/main/Business-requirements_Product-page-section_full.pdf) for the Product section. The following test conditions were found:

Test conditions defined:
* Create test case to access to product section
* Create test case for Image product display 
* Create test case for the product details display
* Create test case for the functionality of Brand Name field
* Create test case for Cart subsection quantity field
* Create test case for Cart subsection Add to cart button
* Create test case for Cart subsection Add to Wishlist button
* Create test case for Cart subsection Compare this product button
* Create test case for Cart subsection Reviews link button
* Create test case for Cart subsection Write a review link button
* Create test case for Rating button
* Create test case for Sharing buttons
* Create test case for Description tab
* Create test case for Specification tab
* Create test case for Reviews tab
* Create test case for "Your Name" field in the Review tab
* Create test case for "Your Review" field in the Review tab 
* Create test case for rating options from the Review tab
* Create test case for "Continue" button in the Review tab 
* Create test case for Cart status notification when adding to cart
* Create test case for Cart status when adding to cart
* Create test case for Description tab content window
* Create test case for Specification tab content window

## 1.4 Test Design ##
Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are:

* Black box testing : boundary values, use case testing.
* Experience based testing: exploratory testing and check list based testing.

Test cases (the titles):
* Checking access to product section
* Checking Image product display 
* Checking the product details display
* Checking the functionality of Brand Name field
* Checking Cart subsection quantity field 
* Checking Cart subsection Add to cart button
* Checking Cart subsection Add to Wishlist button
* Checking Cart subsection Compare this product button
* Checking Cart subsection Reviews link button
* Checking Cart subsection Write a review link button
* Checking Rating button
* Checking Sharing buttons
* Checking Description tab
* Checking Specification tab
* Checking Reviews tab
* Checking "Your Name" field in the Review tab
* Checking "Your Review" field in the Review tab 
* Checking rating options from the Review tab
* Checking "Continue" button in the Review tab 
* Checking Cart status notification when adding to cart 
* Checking Cart status when adding to cart
* Checking Description tab content window 
* Checking Specification tab content window

The test cases with steps can be viewed here: 

## 1.5 Test Implementation ##
The following elements are needed to be ready before the test execution phase begins:

* Testing environment is up and running: [demo.opencart.com](https://demo.opencart.com/index.php?route=product/product&language=en-gb&product_id=43) 
* Access to the testing environment is given: Username: demo | Password: demo
* Cycle summary was created

## 1.6 Test Execution ##
Test cases are executed on the created test Cycle summary: link

* Product image section was tested in cycle:
![Cycle-sum_Image-section](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/384342b4-0ba6-424d-99aa-c7185d4ba1a3)
* Product details was tested in cycle:
![Cycle-sum_Product-details](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/79268b3c-1c0e-43bc-8779-7fde87cffc35)
* Cart subsection was tested in cycle:
![Cycle-sum_Cart-subsection](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/860c12e5-c5fb-42b8-bf04-6eebd51cb93a)
* Rating/ Sharing was tested in cycle:
![Cycle-sum_Rating-Sharing](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/f82973d3-9a6f-46b0-a884-70834d13efe0)
* Description tab was tested in cycle:
![Cycle-sum_Description-tab](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/2cdbf1c2-304e-4410-9d5f-456896cdccfe)
* Specification tab was tested in cycle:
![Cycle-sum_Specification-tab](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/3c232a84-9789-4949-808a-26587a9d6de6)
* Reviews tab was tested in cycle:
![Cycle-sum_Reviews-tab](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/a7b30965-cf2a-4d7e-90fa-4ee5213a3917)
Bugs have been created based on the failed tests.\
The complete bug reports can be found here: \
Bugs title:
* Expected product images are missing from underneath the main image
* Users are allowed to type any type of characters in Quantity field
* Users can add more than 100 products in cart or write all type of characters in quantity field and receive a confirmation message 
* Review link button does not open Review tab
* Write a review link button does not open Review tab
* Rating stars button is not an embossed button link
* Sharing button links are missing
* All types of characters including specials characters (&@},~.....) are allowed in Your Name field
* HTML are allowed in the Your Review field

Full regression testing is needed after the bugs are fixed.

## 1.7 Test Completion ##
Exit criteria was evaluated and passed.\
The traceability matrix was generated and can be found here:

![Tracebility-matrix-PFI-2_PFI8](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/cae8e664-f25b-498a-b9d9-49f53c227573)

![Tracebility-matrix-detail-PFI-7_PFI-8](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/18dbbada-5ee4-4f36-8961-93fd572940fb)

Test execution chart was generated:
![Test-Execution-Chart-1](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/11c40f78-7a8f-4c8d-8fbf-3cc2a47136bd)

![Pie-Chart-1](https://github.com/raul-matiu/FinalProject_ITF_ManualTesting/assets/112497081/22fcc018-5606-4739-8d5b-862edd568bcf)

the final report shows.... -> describe the final report
